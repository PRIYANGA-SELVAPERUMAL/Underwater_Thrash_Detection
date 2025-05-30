````markdown
# 🌊 Underwater_Thrash_Detection

This project focuses on detecting trash in underwater environments using state-of-the-art object detection models including **YOLOv5**, **YOLOv8**, **YOLOv10**, and **YOLOv11**. The models are trained and evaluated with various configurations including **5-fold cross-validation** for enhanced performance analysis.

## 📂 Repository Structure

- `Underwater_Trash_Detection_Yolo10n.ipynb` — YOLOv10 nano implementation notebook.
- `Yolov5.ipynb` — YOLOv5 baseline model.
- `Yolov5Fold.ipynb` — YOLOv5 with 5-fold cross-validation.
- `Yolov8.ipynb` — YOLOv8 model implementation.
- `Yolov8_5Fold.ipynb` — YOLOv8 with 5-fold validation.
- `yolo11.ipynb` — Experimental YOLOv11 model.
- `yolo10n_5fold.ipynb` — YOLOv10n with 5-fold training.

## 🧠 Models Used

- ✅ **YOLOv5** — Efficient and proven object detector.
- 🚀 **YOLOv8** — Latest Ultralytics model with better speed & accuracy.
- 🧪 **YOLOv10n** — Lightweight model optimized for edge devices.
- 🔬 **YOLOv11** — Experimental setup for benchmarking.

## 📊 Features

- Underwater object detection with real-time inference.
- Cross-validation for model robustness.
- Model comparisons to evaluate performance.
- Lightweight YOLO variants for resource-constrained environments.

## 🔧 Installation

```bash
# Clone the repo
git clone https://github.com/PRIYANGA-SELVAPERUMAL/Underwater_Thrash_Detection.git
cd Underwater_Thrash_Detection

# Install dependencies
pip install -r requirements.txt
````

> Note: YOLOv5 and YOLOv8 dependencies (Ultralytics or PyTorch Hub) should be installed accordingly in notebooks.

## 🖼️ Sample Results

* **Bounding boxes** on underwater images identifying plastic, cans, and other debris.
* **Precision-Recall curves**, **mAP** scores included in notebooks.

## 📁 Dataset

> Dataset not included due to size. Please link your dataset path in the respective notebooks before running.

## 📈 Evaluation Metrics

* **mAP (mean Average Precision)**
* **Precision / Recall**
* **F1-Score**
* **MSE (Mean Squared Error)**
* **Cross-validation performance**

