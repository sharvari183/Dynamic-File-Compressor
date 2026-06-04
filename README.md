# Dynamic File Compressor

## 📌 Overview
Dynamic File Compressor is a Python-based tool that automatically selects the best lossless compression technique based on file type and content. It reduces file size efficiently while ensuring complete data recovery during decompression.

---

## ⚙️ Features
- Automatic compression algorithm selection
- Supports lossless compression and decompression
- File size optimization
- Integrity check (ensures original data is restored)
- Saves compressed and decompressed outputs
- Simple and lightweight implementation

---

## 🧪 Sample Output
Original Size: 704 bits  
Compressed Size: 378 bits  
Compression Ratio: 0.54  
Original Text Restored: True  
Files Saved Successfully

---

## 📁 Project Structure
Dynamic-File-Compressor/
│
├── samples/               # Input test files
├── src/                   # Core logic (compression & decompression)
├── outputs/               # Generated compressed & decompressed files
├── screenshots/           # Project screenshots
├── main.py                # Main program entry point
├── requirements.txt       # Dependencies
└── README.md              # Project documentation

---

## 🚀 How to Run

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
2️⃣ Run the project
python main.py
