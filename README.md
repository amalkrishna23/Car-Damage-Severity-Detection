# 🚗 Car Damage Severity Detection

A TensorFlow.js web-based deep learning model that classifies the severity of car damage into four categories — **None, Low, Medium, and High**. Built using **MobileNetV2** as the base model for fast and efficient inference directly in the browser.

## 🧠 Overview

This project allows users to upload an image of a car and instantly get a prediction of the **damage severity** using a pre-trained AI model. The model runs entirely in the browser — no backend required!

**Model Architecture:**

* **Base Model:** MobileNetV2
* **Framework:** TensorFlow.js
* **Output Classes:** None, Low, Medium, High

## ⚙️ How It Works

1. **Load the Model:**
   The `model.json` and associated `.bin` weight files are loaded using TensorFlow.js.

2. **Preprocess the Image:**
   The uploaded image is resized to 224x224 pixels and normalized for MobileNetV2 compatibility.

3. **Predict the Damage Severity:**
   The model outputs a probability distribution across the four classes.

4. **Display the Result:**
   The predicted class with the highest confidence is displayed to the user.

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/<your-github-username>/Car-Damage-Severity-Detection.git
cd Car-Damage-Severity-Detection
```

### Run the Project

* Simply open `index.html` in your browser — no additional setup required!
* Ensure all model files (`model.json` and `.bin` files) are in the same directory.
* Upload a car image and click **Predict** to see the damage severity.

