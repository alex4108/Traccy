# How will Traccy work?

When traccy starts up, it will stay running for as long as it's able to poll data from the stream.

If the stream ends, we should shut down Traccy.

While the stream is running, Traccy will collect clips of media to send to ACRCloud

Traccy will provide an interface so that an outside service can query Traccy for it's recognition history.

So first, strap to the stream using [streamlink](https://www.godo.dev/tutorials/python-record-twitch/) and start grabbing audio.

Then, in another thread (python asyncio?), slice up the audio and send it to [ACRCloud](https://github.com/acrcloud/acrcloud_sdk_python).  By using a different thread, we won't block the stream from continuing to capture.

once ACRCloud comes back with a response, we should store that on a DB (redis? postgres? sqlite?)
