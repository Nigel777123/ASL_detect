# American Sign Language (ASL) Detector

A lightweight, browser-based American Sign Language (ASL) detector built entirely with web technologies. This application captures real-time video feed via the webcam, processes hand landmarks using Google MediaPipe, and uses OpenCV.js for image processing and feature classification entirely on the client side—no external backend server required.

## 🚀 Features

* **100% Client-Side:** Runs completely inside the browser using HTML, CSS, and JavaScript. 
* **Real-Time Hand Tracking:** Leverages Google MediaPipe Hands to detect and track 21 distinct hand landmarks instantly.
* **OpenCV.js Integration:** Uses the WebAssembly build of OpenCV to handle canvas manipulation, matrix operations, and region-of-interest (ROI) processing.
* **Live ASL Alphabet Classification:** Translates hand gestures into static ASL characters (A-Z) on the fly.
* **Zero Installation for Users:** Since it is plain HTML/JS, it can be hosted directly on GitHub Pages with one click.

## 🛠️ Built With

* **HTML5 & CSS3:** Core application structure and responsive UI.
* **Vanilla JavaScript (ES6+):** Application logic and webcam streaming.
* **Google MediaPipe Hands:** Machine learning solution for high-fidelity hand and finger tracking.
* **OpenCV.js:** WebAssembly-compiled OpenCV library for real-time computer vision tasks in the browser.

## ⚙️ Getting Started

Because this project is built entirely on standard frontend technologies, getting it running locally is incredibly simple.

### Prerequisites

You do not need to install Node.js, Python, or any heavy compilers. You only need:
* A modern web browser (Chrome, Firefox, Edge, or Safari).
* A working webcam.
* A local server environment (optional, but highly recommended for loading external assets or CDNs properly due to CORS security policies).

### Running Locally

1. **Clone the repository:**
```bash
   git clone [https://github.com/yourusername/asl-detector-html.git](https://github.com/yourusername/asl-detector-html.git)
