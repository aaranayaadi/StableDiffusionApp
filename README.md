# StableDiffusionApp
Stable Diffusion python app for text to image generation
![Screenshot 2024-07-10 225255](https://github.com/aaranayaadi/StableDiffusionApp/assets/37096846/bf1ee593-2176-4c64-a2d2-447b2a788ebf)
![Screenshot 2024-07-10 225329](https://github.com/aaranayaadi/StableDiffusionApp/assets/37096846/79a7c3fa-9f24-4383-bf9c-404a82d2aa27)

This repository contains a desktop application for text-to-image generation using the Stable Diffusion model. The application is built with `tkinter` and `customtkinter` for the GUI, `pytorch` for deep learning, and the `stablediffusion` pipeline. The model used is `CompVis/stable-diffusion-v1-4`, which is available on HuggingFace.

## Features

- **Text-to-Image Generation**: Input a text prompt and generate an image based on that description.
- **Offline Processing**: The model runs offline, ensuring privacy and quick generation times.
- **User-Friendly Interface**: Simple and intuitive GUI with an input bar and a generate button.

## Requirements

- `python` (>= 3.7)
- `tkinter`
- `customtkinter`
- `pytorch`
- `transformers`
- `PIL`
- `auth_token`
- `diffusers`
- `huggingface_hub`

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/aaranayaadi/StableDiffusionApp.git
    cd StableDiffusionApp
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```sh
    all mentioned in the file

## Usage

1. **Run the application**:
    ```sh
    open terminal and type 'python app.py'
    ```

2. **Enter a text prompt** in the input bar at the top of the application window.

3. **Click the 'Generate' button** to generate an image based on the input text.

## Model

The application uses the `CompVis/stable-diffusion-v1-4` model from HuggingFace. This model is capable of generating high-quality images from text prompts.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Acknowledgements

- [HuggingFace](https://huggingface.co/)
- [CompVis](https://github.com/CompVis)
- [Stable Diffusion](https://github.com/CompVis/stable-diffusion)
- [Learning how to build](https://www.youtube.com/@NicholasRenotte)
