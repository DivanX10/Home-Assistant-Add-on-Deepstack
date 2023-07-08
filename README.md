# Home Assistant Add-on: DeepStack

### [DeepStack Server](https://registry.hub.docker.com/r/deepquestai/deepstack/)

![amd64][amd64-shield]

[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg


**DeepStack Server** - This is the server part of artificial intelligence, which will allow you to recognize faces and objects, and you can also create your own custom models.

[DeepStack Documentation](https://docs.deepstack.cc/index.html#)


### [DeepStack Trainer](https://github.com/t0mer/deepstack-trainer)

![amd64][amd64-shield]

[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg

**DeepStack Trainer** - this is the client part and has a web interface where you can train Deep Stack by uploading photos and assigning a name, as well as check the recognition of faces and objects by photo

[DeepStack Trainer Documentation](https://github.com/t0mer/deepstack-trainer)


### Installation

Go to the external interface of your home assistant in Settings -> Add-ons -> Store -> click on the 3 dots (top right) and add this URL to the repository:

```
https://github.com/DivanX10/Home-Assistant-Add-on-Deepstack
```

### Additions in this repository

DeepStack CPU: The server part for working with the processor

DeepStack GPU: Server part for working with a video card

DeepStack Trainer: The client part


### Integration into Home assistant
[HASS-DeepStack-Face](https://github.com/robmarkcole/HASS-Deepstack-face): face recognition, registration and recognition

[HASS-DeepStack-Object](https://github.com/robmarkcole/HASS-Deepstack-object): discovery of shared and custom objects

[HASS-DeepStack-Scene](https://github.com/robmarkcole/HASS-Deepstack-scene): scene recognition
