# Vision-bot-Ai-for-image-and-code-Generation.
#### Date:June24 -2025

- **Import models:**
Import AI models from Hugging face.

- **Model names:**
*Start with small models:*
Image generate - "runwayml/stable-diffusion-v1-5"
code generate - "Salesforce/codegen-350M-mono"

- **Dependencies:**
First to download dependencies
1.`transformers` - use for text generation,summarization,translation,tokenization .This library contains pre trained language models so easy to use them.
2.`diffusers` -use for generate image and ai art.This library contains code for image generation pipelines like StableDiffusion.
3.`Torch` -use for tensors on cpu/gpu. transformers ,diffusers depend on pytorch as their compute engine.
4.`IPython.display` for image display.

- **Hugging face had 42+ tasks models:**
1.Any-to-Any
2.Image-Text-to-Text
3.Image-to-Text
4.Image-to-Image
5.Text-to-Image
6.Text-to-Video
7.Text-to-Speech ...

- **Output image:**
![boy_with_ai](https://github.com/user-attachments/assets/5b411674-1000-4771-8b21-d538c015b25d)

- **API token to load model:**
Huggingface to login get api token then  use huggingface_hub - InferenceClient library to access multiple ai models.

- **Advantages:**
1.Free and easy to use for all the Hugging face ai models locally.
2.Google colab to change run type GPU to download fast.
3.Save a models in google drive then easy to reload again.

- **Disadvantages:**
1.Downloading and storing them takes a time and space
2.Without GPU,models runs very slowly.
3.Needs a stable internet.

- **Tools & Techniques:**
Google colab,
transformers,
diffusers,
torch
IPython.display










