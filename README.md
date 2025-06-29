# 🎧 Music Genre Classification and Recommendation System

This project uses machine learning to classify audio tracks into music genres using extracted features such as MFCCs, spectral contrast, roll-off, and more. It also includes a genre-based recommendation feature to suggest similar songs.

Built using Python, scikit-learn, and Librosa, this system was developed as a college mini-project and won top honors at the **Technovation Hackathon**.

---

## 📌 Problem Statement

With millions of songs available online, manually organizing and searching them by genre is inefficient. This project provides a solution by:
- Automatically classifying uploaded music files by genre
- Recommending other songs of similar genres based on classification

---

## 🧠 Methodology

- **Dataset**: GTZAN Genre Collection (10 genres, 1000 audio clips, 30s each)
- **Feature Extraction**:  
  - MFCCs  
  - Spectral Centroid  
  - Zero-Crossing Rate  
  - Spectral Roll-off  
  - Chroma Frequencies  
- **Preprocessing**: Scaled features, split into train-test sets
- **Models Used**:  
  - Support Vector Machines (various kernels)  
  - Decision Tree  
  - Random Forest  
  - Naive Bayes  
  - KNN  
- **Best Performance**: Random Forest with ~66% accuracy

---

## 📂 Files Included

- `MusicGenreClassification.ipynb` – Complete Python notebook with feature extraction, model training, and evaluation  
- `/screenshots` – Interface and result screenshots (web UI built using Django)

---

## 💡 Key Features

- Upload any `.wav` audio file and get predicted genre  
- Simple Django-based frontend (web interface)  
- Recommendations for similar genre tracks  
- Modular ML pipeline: feature extraction → model training → prediction

---

## 📊 Results

- **Best Model**: Random Forest  
- **Accuracy**: ~66% on GTZAN test set  
- **Insights**: Accuracy improves with more feature combinations and hyperparameter tuning

---

## 🛠 Tech Stack

- Python  
- scikit-learn  
- Librosa  
- Matplotlib, Seaborn  
- Django (for the web interface)

---

## 📌 Future Improvements

- Tune hyperparameters (GridSearchCV)  
- Try deep learning (CNNs on spectrograms)  
- Deploy via Streamlit or Flask for live demos

---

## 📝 License

This project is available under the [MIT License](LICENSE).

---
