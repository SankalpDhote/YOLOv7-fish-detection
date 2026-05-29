# YOLOv7-fish-detection

🚀 **Features:**
- Real-time object detection
- Custom dataset training
- Image, video, and webcam inference
- Pretrained YOLOv7 weights support

---

📂 **Dataset Structure:**
- dataset/
- raw_images/     # Original fish images
- cropped/        # Cropped fish images
- numbered/       # Processed/numbered fish images

---

📦 **Installation:**
- git clone https://github.com/your-username/yolov7-project.git
- cd yolov7-project
- pip install -r requirements.txt

---

🏋️ **Training:**
-- python train.py --img 640 --batch 16 --epochs 50 --data data/custom.yaml --weights yolov7.pt

---

🔍 **Inference:**

- Run detection on images: python detect.py --weights yolov7.pt --source inference/images

- Run webcam detection: python detect.py --weights yolov7.pt --source 0

---

📊 **Evaluation:**  python test.py --data data/custom.yaml --weights best.pt

---

📁 **Project Structure:**
- data/
-  models/
- utils/
- train.py
- detect.py
- test.py
- requirements.txt
