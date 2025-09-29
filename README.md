# Action Recognition using Deep Learning  

This repository implements an **Action Recognition system** on the [UCF50 dataset](https://www.crcv.ucf.edu/data/UCF50.php) using **TensorFlow/Keras**.  
The project demonstrates how to preprocess video data, extract **spatio-temporal features**, and train deep learning models to classify human actions.  

---

## 📌 Features  

Multiple architectures implemented for action recognition:  

- [ConvLSTM](https://github.com/Rydhi-Dadigamuwa/action-recognition-multi-architectures/blob/main/ConvLSTM.png)  
- [LRCN (Long-term Recurrent Convolutional Networks)](https://github.com/Rydhi-Dadigamuwa/action-recognition-multi-architectures/blob/main/LRCN.png)  
- [Deep3DCNN](https://github.com/Rydhi-Dadigamuwa/action-recognition-multi-architectures/blob/main/Deep3DCNN.png)  
- [DeepRes3D](https://github.com/Rydhi-Dadigamuwa/action-recognition-multi-architectures/blob/main/DeepRes3D.png)  
- [SeqNet3D](https://github.com/Rydhi-Dadigamuwa/action-recognition-multi-architectures/blob/main/SeqNet3D.png)  

Additional Features:  
- Notebook for **low-RAM environments** (optimized data pipeline).  
- End-to-end training: preprocessing, model building, training, evaluation, prediction.  
- Visualization of dataset and training metrics.  

---

## 📂 Project Structure  

- `Action_Recognition.ipynb` → Main notebook with all model implementations  
- `Action_Recognition_LowRAM.ipynb` → Optimized version with data pipelining  
- `README.md` → Project documentation  
- `requirements.txt` → Python dependencies  


---

## 📊 Dataset  

- **UCF50 Dataset**: 50 human action categories, each with at least 100 video clips.  
- Source: [UCF Center for Research in Computer Vision](https://www.crcv.ucf.edu/data/UCF50.php).  
- Actions include **sports, musical instrument playing, exercise, daily activities**, etc.
- To download the dataset: [Use this link](https://www.crcv.ucf.edu/data/UCF50.rar)

---

## 🚀 Usage  

1. Open **Action_Recognition.ipynb** to train and evaluate all models.  
2. If running on **low-resource hardware (e.g., 8GB RAM)**, use **Action_Recognition_Using_Data_pipeline.ipynb** for memory-efficient data pipelining.  

---

## 📈 Results  

Each model was tested on subsets(test data) of UCF50. Confusion matrices for each model is given below:  

- [ConvLSTM Results](https://github.com/Rydhi-Dadigamuwa/action-recognition-multi-architectures/blob/main/Confusion_Matrix_ConvLSTM.png)  
- [LRCN Results](https://github.com/Rydhi-Dadigamuwa/action-recognition-multi-architectures/blob/main/Confusion_Matrix_LRCN.png)  
- [Deep3DCNN Results](https://github.com/Rydhi-Dadigamuwa/action-recognition-multi-architectures/blob/main/Confusion_Matrix_Deep3DCNN.png)  
- [DeepRes3D Results](https://github.com/Rydhi-Dadigamuwa/action-recognition-multi-architectures/blob/main/Confusion_Matrix_DeepRes3D.png)  
- [SeqNet3D Results](https://github.com/Rydhi-Dadigamuwa/action-recognition-multi-architectures/blob/main/Confusion_Matrix_SeqNet3D.png)  

---
