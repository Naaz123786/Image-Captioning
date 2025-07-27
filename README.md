# 📸 Image Captioning Generator

This project is a deep learning-based **Image Captioning Generator**, developed and executed in **Google Colab**. It combines **Computer Vision** and **Natural Language Processing (NLP)** to automatically generate descriptive captions for images using a combination of **CNN (Convolutional Neural Networks)** and **RNN (LSTM)** architectures.

---

## 🚀 Features

- Built and tested using **Google Colab** for cloud-based execution
- Utilizes **CNNs (e.g., InceptionV3, VGG16)** for image feature extraction
- Applies **LSTM-based RNNs** for generating textual captions
- Trains on popular datasets like **Flickr8k, Flickr30k, MSCOCO**
- Includes data preprocessing, training, and caption generation pipeline
- Uses **Matplotlib** for result visualization and evaluation

---

## 🧠 Technologies Used

- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [NumPy](https://numpy.org/)
- [OpenCV](https://opencv.org/)
- [Matplotlib](https://matplotlib.org/)
- Google Colab (for development and testing)

---

## 📁 Project Structure

📂 image-captioning-generator/

├── 📓 Image_Captioning_Colab_Notebook.ipynb # Main Colab notebook

├── 📁 images/ # Folder for input/test images

├── 📁 captions/ # Captions file (Flickr or MSCOCO)

├── 📄 requirements.txt # Python dependencies

├── 📄 README.md # Project documentation


---

## 📦 Dataset

Supported datasets:

- **Flickr8k**
- **Flickr30k**
- **MSCOCO**

> Ensure the dataset includes images and a captions file (usually `.txt` or `.json`).

You can download the datasets from:

- !wget -q https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip
- !wget -q https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip
- !unzip -qq Flickr8k_Dataset.zip
- !unzip -qq Flickr8k_text.zip
- !rm Flickr8k_Dataset.zip Flickr8k_text.zip

---

📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

🙌 Acknowledgments

- Datasets: Flickr8k, MSCOCO

- TensorFlow/Keras documentation and tutorials

- Open-source research papers on Image Captioning
