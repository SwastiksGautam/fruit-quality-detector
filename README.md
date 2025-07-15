# 🍎 Rotten Fruit Detection using YOLOv8

This project uses the **YOLOv8 object detection model** to detect and classify **fresh and rotten fruits** including apples, bananas, and oranges. It involves data preparation, model training, and image inference to identify fruit quality in real-world scenarios.

---

## 📁 Dataset

The dataset consists of images of:
- Fresh Apples
- Rotten Apples
- Fresh Bananas
- Rotten Bananas
- Fresh Oranges
- Rotten Oranges

Each fruit class has associated label files in YOLO format. The data was organized into validation folders and split into training and validation sets.

---

## 🛠️ Project Structure

```bash
├── yolov8_dataset.yaml          # Dataset config file for YOLOv8
├── /train
│   ├── /images                  # Training images
│   └── /labels                  # Training labels
├── /val
│   ├── /images                  # Validation images
│   └── /labels                  # Validation labels
├── yolov8_trained_model.pt     # Trained model (saved weights)
└── inference_code.ipynb        # Contains training and prediction pipeline
