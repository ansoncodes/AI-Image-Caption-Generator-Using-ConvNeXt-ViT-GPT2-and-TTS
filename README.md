# 🧠 AI Image Caption Generator

This project uses a Vision Transformer-based deep learning model to generate descriptive captions for uploaded images. The final caption is also converted into spoken audio using built-in Python audio tools, making the system useful for accessibility and assistive technologies.

---

## ✅ What It Does

### 🖼️ Image Captioning
- Uses the **ViT-GPT2 model** (`VisionEncoderDecoderModel`) from [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
- Images are preprocessed using `ViTFeatureExtractor`
- The model outputs descriptive captions like:  
  > *"a cat sitting on a couch"*

### 🔊 Audio Playback
- Captions are converted to **speech audio (.wav)** using built-in audio recording methods (not Glow-TTS)
- The audio is played directly within the notebook using `IPython.display.Audio`

### 🎛️ Interactive Interface
- Created with `ipywidgets` for user-friendly image uploads
- Automatically displays:
  - Uploaded image
  - Generated caption
  - Audio playback of the caption

---

## 📂 File Overview

```
├── AI_Image_Caption_Generator.ipynb   # Main notebook
├── README.md                          # This file
```

---

## 🧠 Technologies Used

| Purpose              | Library/Tool |
|----------------------|--------------|
| Model Architecture   | ViT-GPT2 (`VisionEncoderDecoderModel`) |
| Image Processing     | `ViTFeatureExtractor` |
| Audio Playback       | `IPython.display.Audio` |
| Interactive Upload   | `ipywidgets.FileUpload`, `widgets.Image`, etc. |
| Language             | Python |
| Platform             | Jupyter Notebook |

---

## 🚀 How to Run

1. **Install dependencies**:

```bash
pip install torch torchvision transformers pillow ipywidgets
```

2. **Start the notebook**:

```bash
jupyter notebook AI_Image_Caption_Generator.ipynb
```

3. **Upload an image** using the widget  
   → View the caption  
   → Hear the audio narration

---

## 🎯 Use Cases

- 🧑‍🦯 **Accessibility**: Describes images for visually impaired users
- 🧑‍🏫 **Education**: Helps children or non-readers understand image content
- 📸 **Narrative content**: Adds spoken descriptions to photos

---

## 📝 Notes

- An earlier **ConvNeXt model** is included in the notebook but is not used in the final captioning pipeline.
- No external TTS (e.g., Glow-TTS) library is currently used.
- Audio is generated using native Python tools, not deep learning-based synthesis.

---

## 📃 License

This project is for educational and academic use only.
