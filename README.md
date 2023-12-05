# ConfyUI Workflows

Experimental workflows for Comfy UI sometime slightly modified from the original ones. Most of them are inpired by other awesome projects (people) and are just a way to test, learn and have fun with Comfy UI.

## Requirements

This is my personal experimental setup to run Comfy UI. It is not meant to be used by anyone else. If you want to use simply Comfy UI you can follow the instructions on the [Comfy UI](https://github.com/comfyanonymous/ComfyU) repository.

### 1.Install [Stability Matrix](https://github.com/LykosAI/StabilityMatrix)

Follow the instructions on the repository. This is my choice of environment to run Comfy UI, because it is easy to install and it comes with sharing downloaded models and packages across different workflows like A1111, Comfy UI, Fooocus, Invoke AI etc. And I like to experiment with all of them. Stability Matrix also comes with a nice UI to install packages, models via [CivitAI](https://civitai.com).

### 2.Download [SDXL Turbo Model](https://huggingface.co/stabilityai/sdxl-turbo) model

Simply do it via Stability Matrix UI or download it manually from [Hugging Face](https://huggingface.co/stabilityai/sdxl-turbo/tree/main). You need to download the

- `sd_xl_turbo_1.0.safetensors`
- `sd_xl_turbo_1.0_fp16.safetensors`

and place them in the `models` folder of `StabilityMatrix/Models/StableDiffusion'.

### 3.Install [Comfy UI](https://github.com/comfyanonymous/ComfyUI)

Stability Matrix `Packages` tab is a magic. You can install Comfy UI with a single click.

### 4.Install [Comfy UI Manager](https://github.com/ltdrdata/ComfyUI-Manager)

Clone `ComfyUI-Manager` repository (https://github.com/ltdrdata/ComfyUI-Manager) inside `StabilityMatrix/Packages/ComfyUI/custom_nodes` folder.

## Workflows

Now you can install the workflows present in this repository. To do so, you can drag and drop the workflow files into the Comfy UI canvas.

### 🗨️ sdxl-turbo-promt

Simple workflow to run Stable diffusion XL and generate images in real time.

### 🖼️ sdxl-turbo-painting

Real time painting with Stable diffusion XL. There is custom node [PainterNode](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet) which needs to be installed by Comfy UI Manager button `Install via Git URL`.

## Supporting/Sponsoring this project

If you like this repository, you can support me by buying me a coffee.

[<img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50">](https://www.buymeacoffee.com/eudardt)
