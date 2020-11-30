# Traccy

[!License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

# Description

Traccy (pronounced _Trackie_) is a python script that allows a user to capture a live stream, and automatically parse the audio data from the stream, submitting it to ACRCloud for recognition.

The idea is for this project to create a "Now Playing" type of integration that can be used elsewhere.

# License notes

The CC-BY-NC license prohibits commercial use.  This script may be used by streamers in the community or affiliates of the streaming community to produce effective works that help streamers increase the quality of their work.  It is NOT intended to be used to aide in the creation of DMCA notices, lawsuits, or otherwise negatively affect a streamer's production.

# What does it use?

* [Docker](https://docker.io) to run the application
* [ACRCloud](https://github.com/acrcloud/acrcloud_sdk_python) for music recongition
* [python-record-twitch](https://www.godo.dev/tutorials/python-record-twitch/) to capture a Twitch stream.


# Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

