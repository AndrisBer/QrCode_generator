# QR Code Generator

## 📌 Overview
This is a **Windows Forms Application (C#)** that generates QR codes from user input using the **QRCoder** library.

## 🛠 Technologies Used
- **C# (.NET Framework)**
- **Windows Forms (WinForms)**
- **QRCoder Library**

## 🚀 Features
✅ Converts text input into a **QR Code**
✅ Uses **QRCoder** for high-quality QR code generation
✅ Displays the QR code in a **PictureBox**
✅ Simple and intuitive **Windows Forms UI**

## 📥 Installation & Usage
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/QR-Code-Generator.git
cd QR-Code-Generator
```

### **2️⃣ Open in Visual Studio**
- Open `QR-Code-Generator.sln` in **Visual Studio**
- Ensure you have **.NET Framework** installed

### **3️⃣ Install QRCoder Package**
To ensure the QR code library is installed, run:
```bash
Install-Package QRCoder
```

### **4️⃣ Run the Application**
- Click the **Run** button (`F5`) in Visual Studio
- Enter text into the **TextBox**
- Click **Generate QR Code**
- The QR code will appear in the **PictureBox**

## 📸 Screenshot

![qr1](https://github.com/user-attachments/assets/b4db1338-0faf-4d04-950f-fa66dca75182)

![qr2](https://github.com/user-attachments/assets/73915764-16a1-40ae-b9f2-23ee6ff3c1b8)



## 🔧 How It Works
- Uses **QRCoder** to generate a QR code from input text
- Sets the QR code as an image inside a `PictureBox`
- Uses **ECC Level Q** for error correction

## 🐛 Known Issues
- The QR code size is fixed (can be made adjustable in future updates)
- Currently, only **text input** is supported

## 📜 License
This project is open-source under the **MIT License**.

## 👨‍💻 Author
Developed by **Andris Bernatovichs**

---
💡 *Feel free to contribute or suggest improvements!* 🚀
