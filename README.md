# stable-diffusion-webui-mac
Personal notes for running Stable Diffusion successfully with M1/M2 macs.

Useful threads:

- [How to improve performance on M1 / M2 Macs](https://github.com/AUTOMATIC1111/stable-diffusion-webui/discussions/7453)

## mediapipe installation error

You’ll need to install `mediapipe-silicon` which is for Apple Silicon.

https://github.com/cansik/mediapipe-silicon

Works for me if you just install directly inside virtualenv. I use `pyenv` so can’t suggest how to do it by modifying the webui scripts, which uses `venv`

## Others

Worthy to look at if can’t solve M1 / M2 issues, but changing configs are the easiest. 
- [https://github.com/brkirch/stable-diffusion-webui/releases](Offline M1/M2 releases) - https://github.com/brkirch/stable-diffusion-webui/releases
