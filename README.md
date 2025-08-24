

This project demonstrates a complete pipeline for automatic license plate detection and recognition from video footage using [YOLOv8](https://github.com/ultralytics/ultralytics) and [EasyOCR](https://github.com/JaidedAI/EasyOCR). It includes frame extraction, model training, plate detection, and OCR-based text extraction—all packaged into a video output with annotated results.

---

<p align="left"> 📁 Project Structure<br><br><br>├── frame/                      # Extracted frames from input video ├── runs/detect/train/         # YOLOv8 training outputs ├── data.yaml                  # Custom dataset configuration ├── plaue.mp4                  # Input video file ├── output_with_plates.mp4     # Final annotated video ├── main.py                    # Full pipeline script └── README.md                  # Project documentation<br><br>---<br><br>🧠 Technologies Used<br><br>- **YOLOv8** – Object detection for license plates<br>- **EasyOCR** – Optical character recognition for plate text<br>- **OpenCV** – Video processing and annotation<br>- **Python** – Core scripting language<br><br>---<br><br>🛠️ Setup Instructions<br><br>1. **Clone the repository**  <br>   <br>   git clone https://github.com/your-username/license-plate-detection.git<br>   cd license-plate-detection<br><br><br>- Install dependencies<br>pip install ultralytics easyocr opencv-python<br>- Prepare your dataset<br>- Annotate license plates using Roboflow or LabelImg<br>- Export in YOLO format and update data.yaml<br>- Train YOLOv8 model<br>from ultralytics import YOLO<br>model = YOLO("yolov8n.pt")<br>model.train(data="data.yaml", epochs=100, imgsz=640)<br><br><br>- Run the full pipeline<br>python main.py<br><br><br><br>🎯 Output Example<br>Each frame is processed to:<br>- Detect license plates using YOLOv8<br>- Apply OCR to extract readable text<br>- Annotate the frame with bounding boxes and recognized plate numbers<br>Final output: output_with_plates.mp4<br><br>📌 Notes<br>- OCR confidence threshold is set to 0.3 to filter unreliable predictions.<br>- You can adjust YOLO model size (yolov8n, yolov8s, etc.) based on your hardware.<br>- For better OCR accuracy, consider fine-tuning EasyOCR or preprocessing cropped plates.<br><br><br>🧳 Migration & Portfolio Impact<br>This project is designed for real-world deployment and resume visibility. It showcases:<br>- End-to-end ML/CV pipeline design<br>- Modular, reproducible code<br>- Professional documentation and output formatting<br>Ideal for freelance proposals, GitHub branding, and USA(NYC) migration portfolios.<br><br>📫 Contact<br>Feel free to reach out via LinkedIn or GitHub for collaboration or freelance opportunities.<br>\https://www.linkedin.com/in/alireza-sobhani-385134245</p>

###

<h2 align="left">I code with</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" height="40" alt="linkedin logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg" height="40" alt="opencv logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="40" alt="jupyter logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" alt="linux logo"  />
</div>

###
