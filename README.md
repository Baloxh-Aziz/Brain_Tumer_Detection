# 🧠 Brain Tumor Detection with YOLOv11n

A simple web app that finds brain tumors in MRI images using a YOLOv11n model.

You upload an image. The app looks at it and shows where the tumor may be.

👉 [Live Demo](https://brain-tumer-detection-with-yolov11n.streamlit.app/)

---

## ⚠️ Important Note

This project is for **learning and study only**.
It is **not a medical tool**. Do not use it to make health decisions.
Always ask a real doctor.

---

## What It Does

- Lets you upload a brain MRI image (`.jpg` or `.jpeg`)
- Shows the image you uploaded
- Runs the YOLOv11n model on it
- Shows the result with a box around the detected tumor

---

## Files in This Project

| File | What it is |
|------|------------|
| `brain_app.py` | The main Streamlit app |
| `best.pt` | The trained YOLOv11n model |
| `requirements.txt` | Python libraries the app needs |
| `packages.txt` | System packages needed for OpenCV on Streamlit Cloud |


## Author

Made by **Azizullah Asad**

---

## License

Free to use for learning. Add a license file if you want to share it more widely.
