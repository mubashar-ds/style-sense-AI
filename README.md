# StyleSense: AI-Based Fashion Design System

**StyleSense** is an AI-powered fashion design platform that generates new and creative clothing styles by blending trending fashion imagery. It enables users to experiment with fashion concepts using both scraped and custom-uploaded content through an interactive web interface.

---

## Features

- **Image Scraping:** Automatically extracts trending fashion images from e-commerce platforms.
- **Custom Uploads:** Upload your own clothing images and descriptive prompts.
- **AI Style Blending:** Combine two images using alpha sliders to influence the resulting design.
- **Interactive Interface:** Powered by Gradio for an intuitive, browser-based experience.

---

## Installation & Usage (Google Colab)

StyleSense is designed to run directly in **Google Colab** — no setup or installation required on your local machine.

### Prerequisites

- A **Google Account** to access and run notebooks on [Google Colab](https://colab.research.google.com/).

### Quick Start

1. **Open the Colab Notebook:**
   - Upload or access the `.ipynb` file from this repository.
   - Open it in Google Colab (right-click → _Open with_ → Google Colaboratory).

2. **Run the Notebook:**
   - Execute all setup cells to:
     - Install dependencies
     - Scrape trending clothing images
     - Initialize the AI design generator
     - Launch the Gradio app

### Dependencies

The following packages are automatically installed:

```bash
!pip install -r requirements.txt
!pip install selenium webdriver-manager torch torchvision diffusers gradio beautifulsoup4 requests Pillow
```

## Gradio Web App

Once setup is complete, Colab will generate a public URL to the Gradio web interface.

### Key Features

- **Gallery View:** Browse curated or user-uploaded clothing images.
- **Upload Image:** Add custom images with descriptive text to guide the AI.
- **Image Selection & Blending:** Choose two images and use alpha sliders to control blending intensity.
- **Generate New Design:** Click **Generate** to produce a unique AI-powered fashion concept.

---

## Example Workflow

1. **Select Images:** Pick two images (from the gallery or your uploads).
2. **Adjust Blend:** Use alpha sliders to control the influence of each image.
3. **(Optional)** Enter a descriptive prompt to guide the generation.
4. **Generate:** Click **Generate** to view your new, AI-crafted design.

---

## Learn More

Read the full project article on Medium:  
[StyleSense: AI-Based Fashion Design System for New Clothing Styles](https://medium.com/@mubashar.cui/stylesense-ai-based-fashion-design-system-for-new-clothing-styles-7309189a296e)


## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this project with proper attribution.
