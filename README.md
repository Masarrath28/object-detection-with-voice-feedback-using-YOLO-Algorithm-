# Real-Time Object Detection with Voice Feedback (YOLOv3)

A lightweight computer vision mini-project that detects objects in real-time using a laptop or external webcam and provides instant, automated audio announcements of the detected items.

By combining the speed of the YOLOv3 architecture with gTTS (Google Text-to-Speech), this system acts as an assistive tool capable of "seeing" the environment and reading it aloud.

## 🚀 Key Features
* **Real-Time Detection**: Processes live camera frames seamlessly using OpenCV's deep learning module .

* **YOLOv3 Architecture**: Utilizes pre-trained YOLOv3 weights trained on the COCO Dataset to accurately identify 80 everyday object classes (e.g., people, cars, chairs, cell phones).

* **Voice Feedback**: Converts detected labels into spoken audio dynamically using the gTTS library.


## 🛠️ Tech Stack & Dependencies
* **Python** — Core programming language.

* **OpenCV** — Handles webcam streams, frame pre-processing, and drawing bounding boxes.

* **gTTS (Google Text-to-Speech)** — Generates high-quality spoken audio feedback from text strings.

* **NumPy** — Powers mathematical array manipulations for handling bounding boxes.
