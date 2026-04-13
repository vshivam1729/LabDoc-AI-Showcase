<div align="center">

# 🚀 LabDoc AI
### *AI-Powered Automated Document Processing Engine for Engineering Students*

<p align="center">
  <a href="https://lab-doc-ai.vercel.app/">
    <img src="https://img.shields.io/badge/🔴_Live_Demo-Try_Now-FF0000?style=for-the-badge" />
  </a>
  <img src="https://img.shields.io/badge/Next.js-Frontend-black?style=for-the-badge&logo=next.js" />
  <img src="https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-Processing-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-Cloud_Runtime-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

### ⚡ Transform messy practical files into print-ready PDFs in 20 seconds
### 📱 Mobile-first • 📄 Perfect headers • 💧 Smart watermarks

</div>

---

## ✨ Preview (Watch it in Action)



<div align="center">

  <video src="https://github.com/user-attachments/assets/1668e5dc-3250-45a1-becc-938236b7b356" width="280" controls></video>

</div>



> ⚡ Upload your `.docx` from your phone → LabDoc AI auto-fixes formatting → Get **college-ready PDF in 20 seconds!**

---

# 🚨 The Problem: The 10:40 AM Panic

Every engineering student knows this exact struggle.

It’s **10:40 AM**. Submission is at **11:00 AM**. The queue for the college lab dot-matrix printer is a mile long.

The only backup? Running to the local stationery shop to print.

But local shops only have **plain A4 paper**, not the official pre-printed **"Thakur Sheets"** with college logos.

Rushing to print here brings **two massive roadblocks**:

## 1) 🧩 The Manual Struggle
Finding a free PC (or awkwardly opening your laptop in a crowded shop), manually inserting the college watermark, aligning it without breaking Word formatting, exporting as PDF, and WhatsApp-ing the shopkeeper easily burns **10–15 precious minutes**.

## 2) 🕰️ Outdated Headers
Many standard experiment templates still carry the old **2019 header**.

Manually replacing it with the **2023 standard** while panicking about time is incredibly frustrating.

---

# 🚀 The Solution: LabDoc AI

Instead of complaining about the friction, I built **LabDoc AI** — a cloud-native, entirely **mobile-friendly intelligent document processing pipeline**.

No need to boot up a laptop.

Stand right outside the stationery shop, use your phone, and get a **print-ready PDF in just 20 seconds**.

## 🛠️ Built for Two Specific Scenarios

### ✅ Scenario A — The Lab Print
You braved the lab queue, but your document has the old 2019 header.

Toggle **"Update Header"**.

The tool instantly updates the header to **2023**.

> *(No watermark added, since the Thakur Sheet already has one.)*

### ✅ Scenario B — Emergency Print Mode
Out of official sheets?

At the stationery shop with plain A4 paper?

Hit **"Emergency Print Mode"**.

The tool instantly applies the **2023 header AND a perfectly aligned translucent college watermark**.

---

# 🔥 Core Features

## 📏 Smart Header Injection
- Removes legacy / broken headers safely
- Injects standardized 2023 college-approved headers
- Preserves `.docx` XML integrity

## 💧 Pixel-Perfect Watermark Engine
- Intelligent RGB thresholding `>240`
- Applies **45% translucent watermark underlay**
- Keeps text **100% crisp black** without layout breaking

## 📄 Cloud PDF Conversion
- Dockerized **headless LibreOffice**
- Reliable `.docx → .pdf` auto-conversion
- No manual exporting required
- Print-shop friendly output

---

# ⚙️ System Architecture

```mermaid
flowchart LR
    A[📤 User Uploads DOCX via Mobile] --> B[⚛️ Next.js Frontend]
    B --> C[⚡ FastAPI Backend]
    C --> D[🧠 python-docx XML Parser]
    D --> E[📏 Header Injection Engine]
    E --> F[🐳 Dockerized LibreOffice]
    F --> G[📄 PDF Render Engine]
    G --> H[🖼️ PyMuPDF + Pillow]
    H --> I[💧 Watermark Underlay]
    I --> J[✅ Final Print Ready PDF in 20s]
```

---

# 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js, Tailwind CSS, Shadcn UI |
| Backend | FastAPI |
| Processing | python-docx, PyMuPDF, Pillow |
| Conversion | LibreOffice Headless |
| Deployment | Docker, Vercel |
| Language | Python, TypeScript |

---

# 💻 Local Setup

## 🔹 Clone Repository
```bash
git clone https://github.com/vshivam1729/LabDoc-AI.git
cd LabDoc-AI
```

## 🔹 Backend Setup
```bash
cd backend
python -m venv venv
```

### ▶️ Activate Virtual Environment
**Windows**
```bash
venv\Scripts\activate
```

**Linux / Mac**
```bash
source venv/bin/activate
```

### ▶️ Install Dependencies & Run
```bash
pip install -r requirements.txt
uvicorn main:app --reload
```

## 🔹 Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

---

# 🌟 Why This Project Stands Out

This is not just another CRUD app.

It demonstrates:

- 🧠 Real-world product thinking & problem-solving
- 📱 Mobile-first constraint-based design
- ⚙️ Backend architecture & document processing
- 🐳 Docker production workflows
- ☁️ Cloud deployment knowledge

---

# 👨‍💻 Developed By

**Shivam Vishwakarma**  
🚀 2nd-year Computer Engineering Student  
💻 Full Stack Developer  
⚡ Building real-world solutions

---

# 🌐 Connect With Me

- 💼 LinkedIn: https://www.linkedin.com/in/shivam-vishwakarma-932166371/
- 🔴 Live Demo: https://lab-doc-ai.vercel.app/

---

<div align="center">

## ⭐ If this project impressed you, please star the repo

Your one ⭐ motivates more real-world builds 🚀

</div>