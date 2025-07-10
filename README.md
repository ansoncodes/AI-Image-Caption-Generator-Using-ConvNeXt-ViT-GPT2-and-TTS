# Image Caption Generator with Text-to-Speech

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/image-caption-generator/blob/main/image_caption_generator.ipynb)

A Python application that generates descriptive captions for uploaded images using Vision Transformer (ViT) and GPT-2 models, with integrated text-to-speech functionality to read the captions aloud.

## 🚀 Quick Start

1. **Click the "Open in Colab" badge above**
2. **Run all cells in sequence** (Ctrl+F9 or Runtime → Run all)
3. **Upload your image** using the widget that appears
4. **Enjoy AI-generated captions with speech!**

## Manual Start
1. Go to this GitHub repository and **download** the file `AI-Image-Caption-Generator-Using-ViT-GPT2-and-TTS.ipynb`  
   - Click on the file name  
   - Then click the **“Download raw file”** button (or right-click → Save As)
2. Open [Google Colab](https://colab.research.google.com)
3. Click **Upload** and select the downloaded `.ipynb` file
4. Once the notebook opens, **run each cell one by one in order**
5. **Upload your image** and get captions with speech!

   No installation required - everything runs in your browser with free GPU access!

## Features

- **Image Caption Generation**: Uses pre-trained ViT-GPT2 model to generate descriptive captions
- **Text-to-Speech**: Converts generated captions to audio
- **Interactive Interface**: Simple upload widget for easy image processing
- **GPU Acceleration**: Automatically uses Colab's free GPU for faster processing
- **Multiple Formats**: Supports JPEG, PNG, and other common image formats

## How It Works

1. **Upload Image**: Use the file upload widget to select your image
2. **AI Processing**: The Vision Transformer analyzes your image
3. **Caption Generation**: GPT-2 model generates a natural language description
4. **Speech Synthesis**: TTS model converts the caption to speech
5. **Results**: View your image with caption and play the audio

## Model Information

- **Vision Model**: `nlpconnect/vit-gpt2-image-captioning`
- **TTS Model**: `tts_models/en/ljspeech/glow-tts`
- **Architecture**: Vision Transformer + GPT-2 for captioning, Glow-TTS for speech

## Usage Tips

- **Better Results**: Use clear, well-lit images for more accurate captions
- **Audio**: Click the audio player to hear your caption spoken aloud
- **GPU**: Colab automatically provides free GPU acceleration
- **Multiple Images**: Upload different images to generate new captions

## Example Output

Upload an image and get results like:
- **Image**: Your uploaded photo
- **Caption**: "A cat sitting on a wooden table"
- **Audio**: Spoken version of the caption

## Features Breakdown

### Image Processing
- Automatic format conversion and optimization
- Handles various image sizes and orientations
- Real-time processing feedback

### Caption Generation
- State-of-the-art Vision Transformer technology
- Natural language descriptions
- Context-aware captioning

### Text-to-Speech
- High-quality speech synthesis
- Automatic audio file generation
- Built-in audio player

## Troubleshooting

**Common Issues:**

1. **Slow Processing**: 
   - Enable GPU: Runtime → Change runtime type → GPU
   - Wait for model downloads on first run

2. **Upload Issues**:
   - Try smaller image files (< 10MB)
   - Use common formats (JPEG, PNG)

3. **Audio Not Playing**:
   - Check browser audio permissions
   - Ensure speakers/headphones are connected

## Technical Details

- **Framework**: PyTorch with Transformers library
- **Models**: Pre-trained Hugging Face models
- **Processing**: Runs entirely in Google Colab
- **Storage**: Temporary files in Colab session

## Contributing

1. Fork the repository
2. Make your changes
3. Test in Google Colab
4. Submit a pull request

## License

This project is licensed under the MIT License.

## Acknowledgments

- [Hugging Face](https://huggingface.co/) for the vision and language models
- [TTS Library](https://github.com/coqui-ai/TTS) for text-to-speech functionality
- [Google Colab](https://colab.research.google.com/) for free GPU access

## Support

If you encounter issues:
1. Check the troubleshooting section above
2. Restart the Colab runtime
3. Open a GitHub issue with details

---

**Ready to try it?** Click the Colab badge at the top and start generating captions in seconds!
