
# 🧥 Invisible Cloak using OpenCV

## 📖 Overview
This project implements **Harry Potter-style invisibility** using **OpenCV and color detection**. It works by capturing the background first and then replacing the selected color (like a red cloak) with the stored background, creating an "invisible" effect.

## 🚀 Features
- **Creates an invisibility effect using OpenCV**
- Uses **color detection & background subtraction**
- Works in **real-time with a webcam**
- Simple & efficient **Python implementation**

## 🛠️ Technologies Used
- **Python** 🐍
- **OpenCV** 👀 (for image processing)
- **NumPy** 🔢 (for array manipulation)

## 📂 Project Structure
```
📁 Invisible-Cloak
│── 📄 invisible_cloak.ipynb  # Jupyter Notebook for running the project
│── 📂 examples               # Folder for example images & results
│── 📄 README.md              # Project documentation (this file)
```

## 🔧 Installation & Setup

### **1️⃣ Install Dependencies**
Make sure you have **Python 3.7+** installed, then install the required libraries:

```bash
pip install opencv-python numpy
```



### **3️⃣ Run the Project**
#### ✅ **Jupyter Notebook (Recommended)**
```bash
jupyter notebook
```
Then open **invisible_cloak.ipynb** and run the cells.

#### ✅ **Python Script (If converted to `.py`)**
```bash
python invisible_cloak.py
```

---

## 🎥 How It Works
1. **Capture the Background:** The program first captures a few frames of the background **without the cloak**.
2. **Detect the Cloak:** A specific color (e.g., red) is detected in each frame.
3. **Replace the Cloak:** The detected color is replaced with the previously captured background, creating the **invisibility effect**.


---

## 📝 To-Do / Future Enhancements
- [ ] **Improve cloak color detection with HSV tuning** 🎨  
- [ ] **Allow dynamic color selection instead of fixed red color** 🎭  
- [ ] **Enhance background capture using Gaussian averaging** 🏞️  

---

## 👏 Acknowledgments
- **OpenCV** for real-time image processing.
- Inspired by the **Harry Potter invisibility cloak concept**.

---

## 📜 License
This project is **open-source** under the **MIT License**. Feel free to use, modify, and share! 🚀  
