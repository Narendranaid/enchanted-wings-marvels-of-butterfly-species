# enchanted-wings-marvels-of-butterfly-species

This project focuses on creating a robust butterfly image classification model using transfer learning techniques. Leveraging a dataset comprising diverse butterfly species, including 75 classes with a total of 6499 images, the dataset is partitioned into training, validation, and test sets. Transfer learning utilizes pre-trained convolutional neural networks (CNNs) to accelerate model training by extracting relevant features from butterfly images. This method enhances classification accuracy while reducing computational resources and training time, ensuring efficient and effective species identification.

---

## 📅 Project Development Phase: Model Performance Test

| **Date**           | **Team ID**             | **Project Name** |
|--------------------|--------------------------|------------------|
| 29th June 2025   | LTVIP2025TMID59361      |  enchanted wings: marvels of butterfly species    |

---

## 🧠 Model Performance Testing

| S.No | Parameter                | Values                                  | 
|------|--------------------------|------------------------------------------|------------|
| 1    | **Model Summary**        | CNN ,Vgg16.h5 model | 
| 2    | **Accuracy**             | Training Accuracy: `96.80%`<br>Validation Accuracy: `92.75%` | 
| 3    | **Fine-Tuning Result**   | Validation Accuracy after fine-tuning: `94.10%` |

---

## 📁 Project Structure

Enchanted Wings /
├── Summer Internship/
│ ├── app.py # Flask API to serve the model
| ├── Vgg16_model.h5
| ├── class_labels.json
│ ├── static/
│ │ └── uploads/ # Folder for user-uploaded images
| | └── backgrounds/
| | └── css/style.css
│ ├── templates/
│ │ └── index.html # HTML template for the frontend
| | └── input.html
| | └── output.html
---

## 🚀 Features

- 🌸 Detects and classifies **fabric patterns** using CNN.
- 🖼️ Web interface to upload an image and see the prediction.
- 🔁 Pre-trained model using TensorFlow and Keras.
- 📈 High validation accuracy (~94% with fine-tuning).
- 🔄 Upload > Classify > Get Results instantly.

---

## ⚙️ Installation & Running the App

1. **Clone the Repository:**
git remote add origin https://github.com/Narendranaid/enchanted-wings-marvels-of-butterfly-species
git branch -M main
git push -u origin main


Install Required Packages:
pip install -r requirements.txt
Run Flask App:
python app.py
Access in Browser:
http://127.0.0.1:5000
🧪 Sample Workflow
Navigate to the app in your browser.
