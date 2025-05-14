# 🎨 Real-Time Pencil Sketch with OpenCV

This project turns your webcam feed into a real-time pencil sketch using Python and OpenCV. It applies a sketch effect to the live video and lets you save images by pressing the spacebar.

## 📸 Features

- Real-time webcam capture
- Pencil sketch filter using dodge blend
- Press **spacebar** to save sketch as an image
- Press **'q'** to quit the application
- Automatically saves sketches to the `Sketches/` folder

## 🧰 Requirements

- Python 3.x
- OpenCV (`opencv-python`)

Install dependencies using pip:
pip install opencv-python

🚀 How to Run
Clone the repository:
git clone https://github.com/yourusername/real-time-pencil-sketch.git
cd real-time-pencil-sketch
Make sure a folder named Sketches exists (create it manually if needed):

mkdir Sketches
Run the script:
python sketch.py

🖼 Example Output
The webcam feed will look like a hand-drawn sketch. You can capture snapshots by pressing spacebar, and they will be saved in the Sketches/ folder.

📂 File Structure
real-time-pencil-sketch/
├── sketch.py
├── README.md
└── Sketches/

📝 License
This project is open-source and available under the MIT License.

✨ Author
pulkit jain
