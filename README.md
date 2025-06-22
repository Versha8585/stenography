# stenography
# 📷🔐 Image Steganography using LSB in Python

This project implements a simple and effective **Image Steganography** technique using the **Least Significant Bit (LSB)** method in Python. It allows you to securely hide secret text messages inside grayscale images without any visible distortion.

---

## 📌 Features
- Hide text messages inside images using LSB manipulation.
- Grayscale image processing for simplicity and faster computation.
- Stego image appears visually identical to the original image.
- Save and display both original and stego images.
- Clean, beginner-friendly Python implementation using:
  - `NumPy`
  - `Pillow (PIL)`
  - `Matplotlib`

---

## 📜 How It Works

1. **Convert image to grayscale and resize to 512×512.**
2. **Convert secret message to binary (8 bits per character).**
3. **Replace the Least Significant Bits (LSBs) of image pixels with message bits.**
4. **Save the modified image as the stego image.**
5. **Optional decoder can retrieve the message from the stego image.**

---

## 📸 Sample

| Original Image | Stego Image |
|:---------------|:------------|
| ![original](originalImage.png) | ![stego](stegoImage.png) |

Both images appear identical visually, but the stego image securely contains your secret message.

---

## 🛠️ Technologies Used
- **Python 3.x**
- **NumPy**
- **Pillow (PIL)**
- **Matplotlib**

---

## 📈 Future Scope
- Support for RGB color images.
- Encrypt messages before embedding.
- Web or mobile application interface.
- Embed images or files within images.
- Defend against steganalysis attacks.
- Optimize large image processing.
- Dynamic message length handling.

---

## 📑 Project Report & Presentation
You can find the detailed project report and presentation slides in the `/docs` folder.

---

## 📎 References
- https://numpy.org/
- https://pillow.readthedocs.io/en/stable/
- https://matplotlib.org/

---


