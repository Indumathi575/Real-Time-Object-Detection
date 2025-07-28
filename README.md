# 🧠 Real-Time Object Detection using YOLOv8

This project performs real-time object detection using a webcam feed with the **YOLOv8** model from [Ultralytics](https://github.com/ultralytics/ultralytics) and displays results live with OpenCV.

## 🧾 Features
- Real-time object detection from webcam
- Uses **YOLOv8n.pt** (Nano model) for lightweight and fast inference
- Bounding boxes with class labels and confidence scores
- Display of real-time FPS (frames per second)

---

## 📁 Project Structure

```bash
├── Source_Code.py        # Main script for object detection
├── yolov8n.pt            # Pretrained YOLOv8 Nano model
├── coco.names            # List of COCO dataset object class names


✅ Requirements
1.Python 3.8+
2.OpenCV
3.Ultralytics (YOLOv8)


Install them using:
pip install ultralytics opencv-python


▶️How to Run
1. Clone this repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2.Make sure your webcam is connected and functional.
3.Run the script:
python Source_Code.py
4.Press ESC to stop the detection.


📦Model Used:
This project uses the YOLOv8n (Nano) model for fast and efficient detection. You can switch to other variants like yolov8s.pt or yolov8m.pt by replacing the model file.
Download pretrained models from: Ultralytics YOLOv8 Models


🧠Classes:
Object categories are based on the COCO dataset. The coco.names file includes 80 common objects like:
Person
Bicycle
Car
Dog
Cell Phone
... and many more.


📌Notes:
Make sure your webcam is not being used by another application.
To use a video file instead of a webcam, replace:
cap = cv2.VideoCapture(0)
with:
cap = cv2.VideoCapture('video.mp4')
