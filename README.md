🎬 AI Character Detector

An AI-powered tool that detects specific characters in videos and generates timestamps for their appearances. It can also integrate with DaVinci Resolve to automatically place timeline markers, making video editing faster and more efficient.

---

🚀 Features

- 🔍 Face detection from video frames
- 🎯 Character recognition (e.g., Gojo, Sukuna)
- ⏱️ Automatic timestamp generation
- 🎬 DaVinci Resolve marker integration
- ⚡ Optimized processing (frame skipping + smart filtering)

---

🧠 How It Works

1. The video is sampled at a fixed rate (e.g., 1–2 frames/sec)
2. Faces are detected in selected frames
3. Detected faces are matched with reference images
4. Timestamps are recorded where the character appears
5. Markers are added to the timeline in DaVinci Resolve

---

📁 Project Structure

ai-character-detector/
│
├── dataset/        # Character reference images (not uploaded)
├── videos/         # Input videos (not uploaded)
├── output/         # Generated timestamps
├── src/            # Core scripts
├── main.py         # Main pipeline
├── requirements.txt
└── README.md

---

⚙️ Installation

git clone https://github.com/your-username/ai-character-detector.git
cd ai-character-detector
pip install -r requirements.txt

---

▶️ Usage

1. Add your video to the "videos/" folder
2. Add reference images to "dataset/"
3. Run:

python main.py

4. Output timestamps will be saved in "output/"
5. Markers will be added in DaVinci Resolve

---

🔧 Tech Stack

- Python
- OpenCV
- face_recognition
- NumPy
- DaVinci Resolve Python API

---

⚠️ Notes

- Large files (videos/datasets) are not included in this repository
- For best results, use clear reference images
- Processing speed depends on system performance

---

📈 Future Improvements

- Multi-character detection
- Scene-based optimization
- Auto clip extraction
- GUI application

---

📜 License

This project is licensed under the MIT License.