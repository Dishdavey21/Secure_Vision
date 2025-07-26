# Secure Vision: Deepfake Detection Using MobileNet & PyTorch

Secure Vision is a robust deepfake detection framework built using PyTorch and MobileNet, designed to address the rising threat of synthetic media in digital ecosystems. With the growing prevalence of AI-generated videos that can manipulate reality, Secure Vision aims to detect manipulated content with precision, speed, and efficiency.

## 🚀 Project Highlights

- **Model Architecture**: Leveraged MobileNet for its lightweight and high-performance capabilities, making the solution suitable for real-time applications.
- **Training Pipeline**: Custom training loop implemented in PyTorch using a curated dataset of real and fake videos.
- **Visualization**: Annotated sample videos and overlays highlight detection outputs frame-by-frame.
- **User Interface**: Integrated web application allows easy upload and analysis of suspect videos.
- **Optimized Assets**: All large files (models, video outputs) managed using Git LFS for seamless version control and collaboration.

## 📁 Repository Structure

```
Secure_Vision/
│
├── Dataset/                   # Training and testing dataset (Git LFS)
├── trained_model.pth         # Trained MobileNet model weights (Git LFS)
├── WebApp/                   # Flask-based web application for demo
├── SV_MObilenet.ipynb        # Training notebook for MobileNet model
├── Playground.ipynb          # Testing and inference notebook
├── video_with_overlay.mp4    # Output video with prediction overlays
├── annotated_image.jpg       # Sample prediction frame with annotation
├── output.mp4                # Final output video
├── lcc-train04b-weight_all/  # Additional training weights
└── README.md                 # Project documentation
```

## 🔍 How It Works

1. **Preprocessing**: Each frame from a video is extracted and resized to MobileNet input dimensions.
2. **Inference**: Frames are passed through the trained model which predicts the likelihood of tampering.
3. **Post-processing**: Results are overlaid onto video frames, producing an annotated video output.
4. **Web Interface**: Users can upload videos and view results directly through a simple front-end.

## 🧠 Tech Stack

- **Languages**: Python
- **Libraries**: PyTorch, OpenCV, NumPy, Flask, Matplotlib
- **Model**: MobileNet (custom-trained)
- **Tools**: Git LFS, Google Colab, Jupyter Notebooks

## 📊 Results

Secure Vision achieves high accuracy in detecting facial manipulations, tested across multiple synthetic datasets. The model demonstrates strong generalization with real-world spoofed content and can be fine-tuned further for enterprise-grade applications.

## 🧩 Future Enhancements

- Expand to detect audio-based deepfakes
- Deploy on edge devices for mobile forensics
- Incorporate facial landmark heatmaps for interpretability

## 📌 Credits

Developed by **Disha H. Davey**, a final year Data Science student passionate about secure AI, computer vision, and ethical technology.

---

> Protecting reality in a world of illusions — one frame at a time.
