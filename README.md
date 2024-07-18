# AI-Image-Generator
# Stable Diffusion Image Generator

This repository contains code for a web application that generates images using the Stable Diffusion model. The application is built with the Gradio library for creating a user-friendly interface. 

## Installation
 Install the required libraries:
    ```bash
    pip install diffusers
    pip install transformers
    pip install gradio==3.48.0
    ```

## Usage

1. Run the script:
    ```bash
    python app.py
    ```

2. Open your web browser and go to `http://localhost:7860` to access the web application.

3. Enter a prompt in the text box to generate an image. For example:
    - "astronaut, riding a horse, on mars"
    - "children, playing in disneyland, view from a distance"
    - "baby llama, wearing red muffler, grazing, open field, sunset"

## Code Overview

- `app.py`: Main script to run the web application.
- `requirements.txt`: List of required libraries.

## Example Prompt

```python
prompt = "astronaut, riding a horse, on mars, human colony"
```

Here provided with the screenshot of the web browser to generate images
![Screenshot 2024-07-18 214343](https://github.com/user-attachments/assets/652cf33d-5576-450e-bd12-5466f84b8ba2)

