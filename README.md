In God We Trust
# 🎬 Subtitle Extractor & Summarizer

This project automatically **extracts hardcoded (burned-in) subtitles** from videos using computer vision and **summarizes** them using an LLM (Large Language Model).

## 🔧 Features
- Extracts hardcoded subtitles using OpenCV + Tesseract OCR
- Removes duplicate or overlapping captions
- Summarizes subtitle text using LLMs (e.g., BART via Hugging Face Transformers)
- Includes a simple and interactive [Gradio](https://gradio.app) web UI

## 🚀 Run on Google Colab
1. Open the `subtitle_extractor_and_summarizer.ipynb` notebook in Google Colab.
2. Upload a video with burned-in subtitles.
3. Run all cells or use the Gradio UI to extract and summarize subtitles.

## 📦 Installation (Local Setup)
```bash
pip install opencv-python pytesseract transformers gradio

Make sure Tesseract OCR is installed on your system.

🎥 Sample Video for Testing
You can download a sample video with hardcoded subtitles using yt-dlp:

pip install yt-dlp
yt-dlp https://www.youtube.com/watch?v=YInY5GSey-Q -o sample_hardsub.mp4

📄 License
MIT License

Yahyazadeh.

