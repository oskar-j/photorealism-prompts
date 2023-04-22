# Photorealistic AI-generated images

Workflows (with prompts) for creating high quality photorealism (using AI)

# List of models

1. [Realistic vision V2.0](https://civitai.com/models/4201/realistic-vision-v13)
2. [Dreamlike Photoreal 2.0](https://civitai.com/models/3811/dreamlike-photoreal-20)
3. [Analog Madness v3](https://civitai.com/models/8030/analog-madness)

# List of tools

1. [Draw Things for Mac](https://apps.apple.com/us/app/draw-things-ai-generation/id6444050820)
2. [AUTOMATIC1111 UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

# Examples of prompts

## Realistic model with "Analog Madness"

### Model

Model named [Analog Madness v3](https://civitai.com/models/8030/analog-madness) and based on SD 1.5

### Framework

Use the Dreambooth library.

### Workflow

Use DPM Adaptative with a very low CFG (2 or 3), at 40 steps.

The prompt is very simple, just add terms like "good lighting", "dimly lit", "camera flash", "depth of field", 
and always use the LORA epiNoiseoffset_v2 to have a better contrast in the lighting.

### Prompt

*The prompt is*: "your subject" (selfie), 4k, sharp focus, living room, dimly lit, (sunrays), black shirt, camera flash, depth of field, <lora:epiNoiseoffset_v2:1>

*Negative prompt*: blur, blurry, low quality, drawing, painting, photoshop, hdr, old, b&w

### Extra settings

Steps: 38, Sampler: DPM adaptive, CFG scale: 2, Seed: 3535069355, Size: 640x832

#### Acknowledgment

https://www.reddit.com/r/StableDiffusion/comments/12sbyc5/true_to_life_photorealism_v2/ 
