Requirements Document for Text-to-Image Generator

Install Required Packages:
Upgrade huggingface_hub.
Install diffusers and transformers libraries.

Login to Hugging Face:
Use the notebook_login() function from huggingface_hub.

Import Libraries:
Import StableDiffusionPipeline from diffusers.
Import torch.

Initialize the Model:
Load the pre-trained model runwayml/stable-diffusion-v1-5 using StableDiffusionPipeline.
Generate Image:

Set a text prompt, e.g., "A white cat sitting next to a Christmas tree".
Pass the prompt to the model.
Retrieve and display the generated image.