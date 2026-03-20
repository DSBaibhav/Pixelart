🎨 PixelArt – Video to ASCII Art Converter

A Python project that converts video frames into ASCII art using OpenCV and NumPy.
It transforms visual media into text-based art in real-time.

---

🚀 Features

- 🎥 Convert video into ASCII frames
- ⚡ Real-time frame processing
- 🎯 Adjustable resolution and scaling
- 🔤 Custom ASCII character mapping
- 🧠 Uses OpenCV for image processing

---

🛠️ Tech Stack

- Python
- OpenCV ("cv2")
- NumPy

---

📂 Project Structure

pixelart/
│── index.py          # Main script
│── vid.mp4           # Input video
│── requirements.txt  # Dependencies
│── .gitignore        # Ignored files
│── README.md         # Project documentation

---

⚙️ Installation

1. Clone the repository

git clone https://github.com/DSBaibhav/pixelart.git
cd pixelart

2. Create virtual environment

python -m venv venv

3. Activate it

Mac/Linux

source venv/bin/activate

Windows

venv\Scripts\activate

4. Install dependencies

pip install -r requirements.txt

---

▶️ Usage

Run the script:

python index.py

Make sure your video file is in the project folder.

---

🧠 How it Works

1. Reads video frame-by-frame using OpenCV
2. Resizes frames for better ASCII fitting
3. Converts frames to grayscale
4. Maps pixel intensity → ASCII characters
5. Displays ASCII output

---

🔤 Example ASCII Characters Used

 .:-=+*#%@

Darker pixels → denser characters
Lighter pixels → sparse characters

---

📸 Output Preview

(You can add a screenshot or GIF here later)

---

📌 Future Improvements

- 🎞️ Export ASCII video as file
- 🌈 Colored ASCII output
- 🖥️ GUI interface
- 🔊 Add audio sync

---

👨‍💻 Author

Baibhav

---

⭐ Contribute

Feel free to fork this repo and improve it. Pull requests are welcome!

---

📜 License

This project is open-source and available under the MIT License.