

This project demonstrates a complete pipeline for automatic license plate detection and recognition from video footage using [YOLOv8](https://github.com/ultralytics/ultralytics) and [EasyOCR](https://github.com/JaidedAI/EasyOCR). It includes frame extraction, model training, plate detection, and OCR-based text extraction—all packaged into a video output with annotated results.

---

## 📁 Project Structure


├── frame/                      # Extracted frames from input video ├── runs/detect/train/         # YOLOv8 training outputs ├── data.yaml                  # Custom dataset configuration ├── plaue.mp4                  # Input video file ├── output_with_plates.mp4     # Final annotated video ├── main.py                    # Full pipeline script └── README.md                  # Project documentation

---

## 🧠 Technologies Used

- **YOLOv8** – Object detection for license plates
- **EasyOCR** – Optical character recognition for plate text
- **OpenCV** – Video processing and annotation
- **Python** – Core scripting language

---

## 🛠️ Setup Instructions

1. **Clone the repository**  
   
   git clone https://github.com/your-username/license-plate-detection.git
   cd license-plate-detection


- Install dependencies
pip install ultralytics easyocr opencv-python
- Prepare your dataset
- Annotate license plates using Roboflow or LabelImg
- Export in YOLO format and update data.yaml
- Train YOLOv8 model
from ultralytics import YOLO
model = YOLO("yolov8n.pt")
model.train(data="data.yaml", epochs=100, imgsz=640)


- Run the full pipeline
python main.py



## 🎯 Output Example
Each frame is processed to:
- Detect license plates using YOLOv8
- Apply OCR to extract readable text
- Annotate the frame with bounding boxes and recognized plate numbers
Final output: output_with_plates.mp4

## 📌 Notes
- OCR confidence threshold is set to 0.3 to filter unreliable predictions.
- You can adjust YOLO model size (yolov8n, yolov8s, etc.) based on your hardware.
- For better OCR accuracy, consider fine-tuning EasyOCR or preprocessing cropped plates.


## 🧳 Migration & Portfolio Impact
This project is designed for real-world deployment and resume visibility. It showcases:
- End-to-end ML/CV pipeline design
- Modular, reproducible code
- Professional documentation and output formatting
Ideal for freelance proposals, GitHub branding, and USA(NYC) migration portfolios.

## 📫 Contact
## Feel free to reach out via LinkedIn or GitHub for collaboration or freelance opportunities.
## https://www.linkedin.com/in/alireza-sobhani-385134245

```bash
