# Glacier Motion Estimation using CNN

## 📌 Project Overview
This project estimates glacier motion using satellite images. It combines image processing techniques with a Convolutional Neural Network (CNN) to predict displacement between image pairs and generate a velocity map.

## 🧠 Approach
- Load satellite images (.tif) using Rasterio  
- Extract image patches  
- Generate displacement labels using phase correlation  
- Filter noisy data  
- Train a CNN model (PyTorch) to predict motion (dx, dy)  
- Convert displacement into velocity  

## 🛠️ Technologies Used
- Python  
- NumPy, Pandas  
- OpenCV  
- Rasterio  
- PyTorch  
- Matplotlib  

## 📊 Output
- Predicted displacement vectors  
- Glacier velocity map visualization  

## 🚀 How to Run
1. Upload dataset (.tif images)
2. Run the notebook step by step
3. Train the CNN model
4. Visualize results

## 📁 Files
- `notebook.ipynb` – main project code  
- `README.md` – project description  

## 📌 Note
This project was developed for learning purposes and demonstrates basic machine learning and image processing techniques. Thia is ongoing project, i still working on it.

## 👤 Author
Rohit Sharma

