# Real-Time Object Detection for IoT Devices

![GitHub repo size](https://img.shields.io/github/repo-size/MadhavDGS/Real-Time-Object-Detection-YOLOv9)
![GitHub last commit](https://img.shields.io/github/last-commit/MadhavDGS/Real-Time-Object-Detection-YOLOv9)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![YOLOv9](https://img.shields.io/badge/YOLOv9-Object%20Detection-green)

## 📌 **Project Overview**  
This project implements **real-time object detection** using **YOLOv9** and integrates it with a **Telegram bot**.  
- Users can send an image to a Telegram bot.  
- The **YOLOv9 model** detects objects and returns a processed image with labels.  
- Designed for **IoT applications**, security, and automated monitoring.  

---

##  **Features**  
✅ Train **YOLOv9** on a **custom dataset**  
✅ Use **Google Colab** for training and deployment  
✅ Telegram bot **accepts images and returns detected objects**  
✅ Low latency and **real-time detection**  
✅ Extendable for **new IoT components**  

---

## 🛠️ **Tech Stack**  
- **Programming Language:** Python 🐍  
- **Deep Learning Framework:** PyTorch ⚡  
- **Computer Vision:** OpenCV 👁️  
- **Model:** YOLOv9 🏆  
- **Dataset Management:** Roboflow 📊  
- **Deployment:** Google Colab 🚀  
- **Messaging API:** Telegram Bot API 📩  

---


## 📦 **Installation**
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/MadhavDGS/Real-Time-Object-Detection-YOLOv9.git
cd Real-Time-Object-Detection-YOLOv9
```
### **2️⃣ Install Dependencies**

``` pip install -r requirements.txt
```
---

### **Model Training in Google Colab**

- Open Google Colab.

- Upload and run the yolov9_custom.ipynb notebook.

- Train the YOLOv9 model with your dataset.

- Download the best.pt model file.

## **Using YOLOv9 for Object Detection**

Run Object Detection:
```sh
python detect.py --weights model/best.pt --source path/to/image.jpg
```
## View the Processed Image:

The detected objects will be highlighted in the image.

Results will be saved in the outputs/detected_images/ folder.

Telegram Bot Integration
Create a Telegram bot using BotFather.

Copy the API Token.

Run the bot:
python telegram_bot.py

Send an image to the bot, and it will return a processed image with detected objects.

📊 Results
Here is an example of object detection output:

Example Output

![image](https://github.com/user-attachments/assets/98b5d67c-c177-4aca-8d63-90a4528661ec)

---
## **License**

This project is MIT licensed.
---
**Contributing**

Contributions are welcome!

- Fork the repo.
- Create a feature branch.

- Submit a pull request 🚀.

---

**References**

- YOLOv9 GitHub
- Roboflow
- Telegram Bot API
