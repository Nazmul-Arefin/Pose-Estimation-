
# 🕺 Human Pose Estimation with OpenPose & OpenCV

This project demonstrates real-time human pose estimation using OpenPose with OpenCV's DNN module in Python. It detects and draws skeletons for major human joints (e.g., shoulders, elbows, knees) on input images or videos.

---

## 🚀 Features

- 🔍 Detects 18 key body points using OpenPose TensorFlow model (`graph_opt.pb`)
- 🧍‍♂️ Supports image and video input
- 🧠 Confidence thresholding for more accurate results
- 🖼️ Visual skeleton overlay using OpenCV drawing tools

---

## 📂 File Structure

```

## 🖥️ Usage

```bash
# Run on image
python pose_estimation.py --image input.jpg

# Run on video
python pose_estimation.py --video input.mp4
```

---

## 🧩 Requirements

- Python 3.7+
- OpenCV
- NumPy
- Matplotlib (optional)

Install with:
```bash
pip install opencv-python numpy matplotlib
```

---

## 📈 Keypoint Map (COCO Model)

| ID | Part        |
|----|-------------|
| 0  | Nose        |
| 1  | Neck        |
| 2  | R Shoulder  |
| 3  | R Elbow     |
| ...| ...         |
| 17 | L Ankle     |

---

## 🧠 Future Improvements

- Multi-person support  
- Web-based live demo  
- Export keypoints as JSON

---
