AI Image Generator with LLaMA + Stable Diffusion (Google Colab)
A Google Colab-powered pipeline that combines LLaMA language models and Stable Diffusion to generate images from natural language prompts — all in one notebook, no local setup required.


Features
Runs fully on Google Colab with GPU acceleration

Uses llama-cpp-python for language model processing (optional or in progress)

Uses Hugging Face’s diffusers for text-to-image generation

Powered by PyTorch, Transformers, Accelerate

Includes image preprocessing and display via Pillow and OpenCV

Setup (Auto-installed in Notebook)
bash
Copy code
pip install llama-cpp-python diffusers torch torchvision transformers accelerate numpy pillow opencv-python
The notebook installs everything automatically. Just run the cells in order on Google Colab.

How to Use
Open the notebook in Colab.

Enable GPU from Runtime > Change runtime type.

Run all cells.

Enter a custom prompt to generate an image.

Dependencies
llama-cpp-python

diffusers

torch, transformers, accelerate

numpy, pillow, opencv-python

Sample Prompt
python
Copy code
prompt = "A dreamy mountain landscape under the stars, in watercolor style"
image = generate_image(prompt)
image.show()
References
Diffusers Documentation

LLaMA on GitHub

Google Colab Guide

License
This project is intended for educational and research use only. Be sure to follow the licenses of all used libraries and models.

