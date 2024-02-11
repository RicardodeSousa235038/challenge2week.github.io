This work had the objective to create a model trained on 2d swords with stable diffusion. We used this github as a resource to our work: https://github.com/AUTOMATIC1111/stable-diffusion-webui

Also, in this work I had some troubles for some erros, so my web ui user notes is like this:

@echo off

set PYTHON="C:\Users\rjrso\AppData\Local\Programs\Python\Python310\python.exe"
set GIT=
set VENV_DIR=
set COMMANDLINE_ARGS= --disable-safe-unpickle --opt-sub-quad-attention --lowvram --disable-nan-check --skip-torch-cuda-test --no-half

call webui.bat
