# Home Assistant Add-on: CodeProject.AI

### [CodeProject.AI Server](https://hub.docker.com/r/codeproject/ai-server)

![amd64][amd64-shield]
![aarch64][aarch64-shield]

[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg


**CodeProject.AI Server** - This is the server part of artificial intelligence, which will allow you to recognize faces and objects, and you can also create your own custom models.

[CodeProject.AI Documentation](https://www.codeproject.com/ai/docs/index.html)


### Installation

Go to the external interface of your home assistant in Settings -> Add-ons -> Store -> click on the 3 dots (top right) and add this URL to the repository:

```
https://github.com/judahrand/hassio-addon-CodeProject.AI
```

### Additions in this repository

CodeProject.AI CPU: The basic CPU-only server

CodeProject.AI GPU: A GPU (Nvidia CUDA) enabled version x64 systems. This image will also run on non-GPU systems.

CodeProject.AI Raspberry Pi: A version specifically for Raspberry Pi Arm64 devices. This contains an object detection module suited for low resource systems.


### Integration into Home assistant
[HASS-CodeProject.AI-Object](https://github.com/codeproject/CodeProject.AI-HomeAssist-ObjectDetect): discovery of shared and custom objects
