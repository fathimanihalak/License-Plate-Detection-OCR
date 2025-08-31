# 🚘 License Plate Detection & OCR  

## 📌 Overview  
This project demonstrates **automatic license plate detection and recognition** using:  
- **YOLOv5** for object detection (detecting plates in images)  
- **Tesseract OCR** for text recognition (reading alphanumeric content)  

---

## 🛠️ Tools & Technologies  
- Python (NumPy, Pandas, OpenCV, Matplotlib)  
- Jupyter Notebook  
- YOLOv5 (object detection)  
- Tesseract OCR (text extraction)  

---

## 🚀 Workflow  

1. **Environment Setup**  
   - Imported essential libraries (`numpy`, `pandas`, `cv2`, `matplotlib`, `os`)  
   - Verified setup with OpenCV test  

2. **Dataset Loading**  
   - Loaded annotation CSV (`Licplatesdetection_train.csv`)  
   - Inspected structure of bounding box data  

3. **Data Visualization**  
   - Displayed training images  
   - Verified bounding boxes drawn on images  

4. **YOLO Dataset Preparation**  
   - Converted bounding boxes to YOLO format  
   - Created train/val split (80-20)  
   - Organized dataset into YOLO directory structure  

5. **YOLO Training**  
   - Trained YOLOv5 model on license plate dataset  
   - Validated results with bounding box predictions  

6. **OCR with Tesseract**  
   - Cropped detected plates  
   - Preprocessed with grayscale + thresholding  
   - Extracted alphanumeric text using Tesseract  

---

## 📊 Results  
- ✅ YOLOv5 detected license plates with high accuracy  
- ✅ Tesseract OCR extracted readable text from plates  
- ✅ End-to-end pipeline worked successfully on test images  

---

## 📷 Sample Outputs  
<img width="1366" height="768" alt="2025-08-31" src="https://github.com/user-attachments/assets/c1ae565f-d6b8-4f3d-a618-6fc814061f0c" />

<img width="1366" height="768" alt="Screenshot (98)" src="https://github.com/user-attachments/assets/7eb46f41-a5d5-4c99-9d85-39a326be75c7" />

---


## 🔗 References  
- [YOLOv5](https://github.com/ultralytics/yolov5)  
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)  

---

👩‍💻 Author: **Fathima Nihala**  
