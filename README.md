# Text-to-3D-image
# Gradio UI : https://df3a85d18f67a946b6.gradio.live/

## https://www.kaggle.com/code/meruvajashuva/notebooke76d783247/edit
# 🌀 Text-to-3D Generator using Kandinsky 2.1 + Shap-E

This project allows you to generate **3D-style rotating objects** from simple text prompts. It uses:
- **Kandinsky 2.1** (by community) to generate high-quality 2D images from text
- **Shap-E Img2Img** (by OpenAI) to convert 2D images into rotating 3D-like GIFs
- **Gradio** for a simple web UI

---

## ✨ Features

- Input a natural language prompt
- Generate realistic 2D image using Kandinsky
- Automatically convert the image into a rotating 3D-style animation (GIF)
- View and download the final output directly from the web UI

---

## 🖼️ Demo Flow

1. Input Prompt → `"A cheeseburger, white background, 3D"`
2. Kandinsky 2.1 generates a 2D image of a cheeseburger
3. Shap-E creates a 360° rotation animation of the generated burger
4. Final output is a `.gif` file like `burger_3d.gif`

---

## 🧠 Technologies Used

| Component       | Library             |
|----------------|---------------------|
| Text-to-Image   | `diffusers` (Kandinsky 2.1) |
| Image-to-3D GIF | `diffusers` (Shap-E Img2Img) |
| UI              | `gradio`            |
| Image Handling  | `PIL`, `export_to_gif`      |

---

## 🛠 Installation

```bash
git clone https://github.com/your-repo/text-to-3d-generator
cd text-to-3d-generator

# Create environment if needed
# python -m venv venv && source venv/bin/activate

pip install -r requirements.txt
