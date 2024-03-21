# Use dreambooth to generate incomplete sculptural arms
The project focuses on the phenomenon of "Art restoration errors" and uses incomplete sculpture images as a pre-training dreambooth database to generate "outrageous" sculpture images. The reason why I say "outrageous" images is that these sculpture images with complete bodies have changed the specific culture and art style represented by the original sculptures, and the AI methods used now are just fake. The purpose of the project is to critically think about the disrespect of modern absurd aesthetics to traditional aesthetics in art restoration.

The project uses public Github and the Google Colab platform:
source: https://colab.research.google.com/github/TheLastBen/fast-stable-diffusion/blob/main/fast-DreamBooth.ipynb


## Special Thanks
Project comes from TheLastBen's Github files, thanks to TheLastBen.
Dreambooth paper : https://dreambooth.github.io/
SD implementation by @XavierXiao : https://github.com/XavierXiao/Dreambooth-Stable-Diffusion


## Code Run
When running in google colab, you need to note that because it is running on the website, it may sometimes be unstable. At this time, you need to change the code and run it again.
If it doesn't work, try Test The Trained Model by typing:

```sh
pip install gradio==4.20.1
```
```sh
!pip install --upgrade pydantic
```
```sh
!pip install fastapi
```
```sh
!pip install anyio==3.6.2
```
```sh
!pip cache purge
```
```sh
!pip install cchardet
```

