# OCR with EasyOCR and OpenCV

This project demonstrates Optical Character Recognition (OCR) using [EasyOCR](https://github.com/JaidedAI/EasyOCR) combined with **OpenCV** and **PIL** for text detection, visualization, and annotation.
It supports **multiple languages** (English, Portuguese, French, Chinese, etc.) and shows results directly on images using bounding boxes and labels.

---

## 🚀 Features

* Detects and extracts text from images using EasyOCR.
* Supports multiple languages (e.g., English, Portuguese, French, Chinese).
* Visualizes results with bounding boxes and annotated text.
* Custom text rendering with **PIL + TrueType fonts** (handles Unicode properly).
* Option to draw text with background highlights for better visibility.
* Google Colab–ready notebook (`.ipynb`).

---

## 🛠️ Tools & Libraries

* [Python 3.12](https://www.python.org/)
* [EasyOCR](https://github.com/JaidedAI/EasyOCR) – text detection & recognition
* [OpenCV](https://opencv.org/) – image processing
* [Pillow (PIL)](https://python-pillow.org/) – font rendering
* [Google Colab](https://colab.research.google.com/) – cloud environment

---


---

## ⚡ How to Run

1. Clone the repository

2. Install dependencies

3. Run in Colab or locally


## ⚠️ Challenges Faced

* **Font issues**: Rendering non-English characters required correct `.ttf` or `.ttc` fonts (e.g., `simsun.ttc` for Chinese).
* **Colab environment conflicts**: Needed to downgrade `opencv-python-headless` to a compatible version (`4.12.0.88`).
* **Text positioning**: Adjusting text baseline alignment with bounding boxes.
* **Background rendering**: Ensuring text visibility on bright images.

---

## 📈 Skills Learned

* Using **EasyOCR** for multi-language OCR.
* Handling **custom fonts** in Python (PIL + TrueType).
* Image annotation with **OpenCV** and **PIL**.
* Debugging package version conflicts in Google Colab.
* Combining multiple CV tools into a single pipeline.


---

## 📜 License

This project is open-source under the MIT License.
