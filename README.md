# 🖼️ Image to ASCII Art Converter  

### 🎨 Convert Images into ASCII Art with Python  

Tired of ordinary images? Transform them into stunning ASCII art with this Python-powered tool! This Flask-based web application allows users to upload images and generate ASCII representations with enhanced contrast for better visibility.  

---

## 🔹 Features  

✔️ Upload an image and convert it into ASCII  
✔️ Automatic grayscale conversion  
✔️ Adjustable contrast for better output  
✔️ Web-based interface using Flask  
✔️ Efficient character mapping for detailed ASCII rendering  

---

## 🏗️ Initial Approach: Basic Image Processing  

The system follows a structured approach to convert images into ASCII characters:  

1️⃣ **Resize Image** – Maintains aspect ratio for optimal ASCII rendering  
2️⃣ **Grayscale Conversion** – Converts images to black and white for better ASCII mapping  
3️⃣ **Contrast Enhancement** – Adjusts image contrast for clearer character distinction  
4️⃣ **Character Mapping** – Maps pixel brightness to ASCII symbols  

---

## 🎯 A Better Approach: Optimized Character Mapping  

To improve ASCII rendering, the system uses a predefined set of characters ranked by brightness levels:  

```
@ # $ % ? * + ; : , . ! &
```

Each pixel is normalized and mapped accordingly for a sharper ASCII output.  

---

## 🚀 Key Takeaways  

📌 **Contrast and aspect ratio adjustments significantly improve ASCII output.**  
📌 **Using a predefined ASCII set ensures optimal brightness mapping.**  
📌 **Flask enables seamless web-based interaction for easy image uploads.**  
📌 **Optimized pixel-to-character conversion speeds up execution.**  

---

## 🛠️ How to Run the Project  

1️⃣ **Install Dependencies**  

```bash
pip install flask pillow numpy
```

2️⃣ **Run the Flask Server**  

```bash
python app.py
```

3️⃣ **Access the Web App**  

Navigate to `http://127.0.0.1:5000/` in your browser.  

---

🚀 Start converting your images to ASCII today! 🎨  

---

