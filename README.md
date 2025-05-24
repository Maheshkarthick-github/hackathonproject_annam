# Hackathon Project: hackathonproject_annam

## project is a submission for the Hackathon Preliminary Round, designed to classify soil images using deep learning. The project contains two tasks:


1. **Multi-class Classification**: Predict the correct **soil type** 
2. **Binary Classification**: Determine whether an image **contains soil or not**.

Both tasks utilize **Convolutional Neural Networks (CNNs)** built using **TensorFlow/Keras**. The work was developed in **Google Colab**.

---

## 📁 Repository Structure

- `README.md` – Overview and instructions.
- `competition_soil_classification2.ipynb` – Multi-class classification notebook.
- `soil_classification_part_2.ipynb` – Binary classification notebook.
  
> ⚠️ **Note**: The dataset is **not included** in the repository due to file size limitations. Instructions for uploading in Colab are provided below.

---

## ✅ How to Run in Google Colab (Recommended)

### 1. Open Notebooks in Colab

- Download from GitHub:
  - [`competition_soil_classification2.ipynb`](https://github.com/Maheshkarthick-github/hackathonproject_annam/blob/main/competition_soil_classification2.ipynb)
  - [`soil_classification_part_2.ipynb`](https://github.com/Maheshkarthick-github/hackathonproject_annam/blob/main/soil_classification_part_2.ipynb)
- Open Google Colab → **File > Upload Notebook** → Select the `.ipynb` file.

### 2. Upload the Dataset

- You will need:
  - Folders: `train/`, `test/` (with images)
  - Files: `train_labels.csv`, `test_ids.csv`
- Upload using:
  - Google Colab’s file upload panel, or
  - Mount Google Drive and access the files from a shared folder.

### 3. Run the Notebooks

Each notebook includes:
- Image preprocessing
- CNN model architecture
- Model training and validation
- Performance evaluation
- Prediction export as `.csv`
- Training history plots (accuracy/loss)

