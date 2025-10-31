# HTIC_Deep-Learning_seq2seq-model
Transliteration model built using a Seq2Seq architecture with LSTM encoder–decoder. Trained on Aksharantar dataset for accurate character-level mapping.
This project implements a Sequence-to-Sequence (Seq2Seq) model using LSTM networks to transliterate English text into Tamil. It is based on the Aksharantar dataset, developed and trained in Google Colab, and version-controlled using GitHub.

📂 Dataset

Source: Aksharantar Dataset (IIT Madras)

Files Used: ori_train.csv, ori_valid.csv, ori_test.csv

The dataset contains paired English and Tamil text for transliteration.

⚙️ Project Workflow

Data Preparation

Extract the dataset from aksharantar_sampled.zip

Load ori_train.csv, ori_valid.csv, and ori_test.csv

Preprocess data (tokenization, padding, character mapping)

Model Building

Encoder-Decoder architecture using LSTM layers

Implemented with Keras (TensorFlow backend)

Uses start (\t) and end (\n) tokens for training

Training

Trained on paired sequences from the dataset

Validation and test evaluation for accuracy

Prediction

Input: English word

Output: Tamil transliteration

🧠 Technologies Used

Python

TensorFlow / Keras

Pandas, NumPy

Google Colab

GitHub for version control

🚀 How to Run in Google Colab

Upload the dataset (aksharantar_sampled.zip) to Colab

Run the extraction code:

!unzip aksharantar_sampled.zip -d aksharantar_data


Run the preprocessing, training, and evaluation cells.

Save and push your notebook to GitHub:

!git add .
!git commit -m "Added Seq2Seq transliteration model"
!git push

🧾 Results

The model learns character-level transliteration efficiently.

Achieves good accuracy on validation and test sets.
