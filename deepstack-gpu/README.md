# Home assistant add-on: DeepStack GPU - Server

Using Deep Stack with NVIDIA GPUs. The Deep Stack GPU version handles requests 5-20 times faster than the CPU version if you have an NVIDIA GPU.

### Installation
Install and run the DeepStack addon(server). You don't need to make any settings. After launching the DeepStack addon(server), click on the web interface. If the DeepStack(server) home page has opened, then DeepStack(server) is running and ready to work. It remains to install DeepStack Trainer(client) for DeepStack training (server) and face and object recognition testing.

DeepStack(server) is available on port 7000. You can access it by clicking on the web interface button

4 options have been added to DeepStack(server) and they are enabled by default:
* VISION-FACE - face recognition
* VISION-DETECTION - object recognition
* VISION-SCENE - scene recognition
* MODELSTORE-DETECTION - recognition of user models


### Sources

[Deep Stack Documentation](https://docs.deepstack.cc)

[Download images](https://registry.hub.docker.com/r/deepquestai/deepstack/tags)


### Integration into Home assistant
[HASS-DeepStack-Face](https://github.com/robmarkcole/HASS-Deepstack-face): face recognition, registration and recognition

[HASS-DeepStack-Object](https://github.com/robmarkcole/HASS-Deepstack-object): discovery of shared and custom objects

[HASS-DeepStack-Scene](https://github.com/robmarkcole/HASS-Deepstack-scene): scene recognition

-----

<details>
  <summary><b>Текст на русском</b></summary>


Использование DeepStack с графическими процессорами NVIDIA. Версия DeepStack GPU обслуживает запросы в 5-20 раз быстрее, чем версия CPU, если у вас графический процессор NVIDIA.


### Установка
Устанавливаем и запускаем аддон DeepStack(сервер). Никаких настроек делать не нужно. После запуска аддона DeepStack(сервер) нажимаем на веб-интерфейс. Если открылась стартовая страница DeepStack(сервер), значит DeepStack(сервер) запущен и готов к работе. Осталось установить DeepStack Trainer(клиент) для обучения DeepStack(сервер) и проверки распознавания лиц и объектов.



</details>
