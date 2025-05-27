# Handwritten Bangla Character Recognition using CNN

## Introduction

Handwritten character recognition is essential for digitizing documents and building OCR systems. Recognizing Bangla script is particularly challenging due to its complex structure and diverse handwriting styles. This project applies a Convolutional Neural Network (CNN) to recognize handwritten Bangla characters, aiming to improve accuracy and efficiency in processing Bangla text using deep learning techniques.

Recognizing Bangla handwritten characters is especially important because:

- 📝 It plays a crucial role in digitizing historical documents, automating postal services, and developing OCR systems for regional languages.
- 📄 Many government forms, academic papers, and historical records are still written by hand.
- 📚 Automatic recognition helps in digitizing archives, aiding accessibility, and preserving cultural content.

---

## Dataset Description

We used the **CMATERdb 3.1.2** dataset, which contains 32,000 grayscale images of handwritten Bangla basic characters (50 classes). Each image is 32×32 pixels, captured from various writers to ensure style diversity.

- ✅ Includes both vowels and consonants
- ✅ Suitable for character-level classification tasks
- ✅ Images are preprocessed via normalization and reshaped for CNN input

🔗 **Dataset Link**: [CMATERdb 3.1.2](https://code.google.com/archive/p/cmaterdb/)

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib (for visualization)

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/dev-smashik/Application-of-CNN-Model-to-recognize.git
