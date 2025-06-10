# 🕶️ Fashion Accessory Detection with YOLOv8

This project uses YOLOv8 to detect fashion accessories such as **sunglasses**, **eyeglasses**, and **face coverings** from real-world images.

## 📁 Dataset

- [Kaggle: Glasses and Coverings Dataset](https://www.kaggle.com/datasets/huafengzheng/glasses-and-coverings)
- Includes folders: `plain`, `eyeglasses`, `sunglasses`, `sunglasses-imagenet`

## 🔧 Technologies Used

- Python
- OpenCV
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- Matplotlib
- Jupyter Notebook

## 📂 Project Structure
## 📂 Dataset Access
The dataset is stored in Google Drive for easy access:
[🔗 Download Dataset](your_google_drive_shareable_link_here)

Please download the dataset and place it inside:




fashion-accessory-detector/
├── data/ # Contains the dataset (ignored in Git)
├── notebooks/ # Main Jupyter notebook
├── visuals/ # Detection output images
├── README.md
├── .gitignore




## 🚀 How to Run

1. Install requirements:

pip install ultralytics opencv-python matplotlib

markdown
Copy
Edit

2. Download dataset and place it in:
data/glasses_dataset/

markdown
Copy
Edit

3. Run the notebook:
notebooks/accessory_detection.ipynb

markdown
Copy
Edit

4. View YOLO detection results in:
visuals/sunglasses_detected_clean/

yaml
Copy
Edit

## 📌 Output Sample

The model draws bounding boxes on faces to classify sunglasses, eyeglasses, or no accessory.

---




