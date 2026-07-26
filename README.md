<div align="center">

# 🚀 LabDoc AI 2.0

### *Automated Document Formatting Platform for Practical Files*

<p>

<a href="https://lab-doc-ai.vercel.app/">
<img src="https://img.shields.io/badge/🚀_Live_Demo-Try_Now-FF0000?style=for-the-badge"/>
</a>

<img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js"/>

<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>

</p>

### 📱 Mobile-First • 📄 Supports DOCX & PDF • 🏫 Supports All 11 TCET Departments

### ⚡ Generate official print-ready practical files in seconds with automatic headers, watermarks, faculty tables and footers..

</div>

---

# 🎥 Demo

<div align="center">
  <video src="https://github.com/user-attachments/assets/1e964672-7c13-4dc2-8dcd-706832215e1e" width="280" controls></video>
</div>

> ⚡ Upload → Select Department → Process → Download

---

# 💡 Why I Built LabDoc AI

Every engineering student knows the last-minute rush before getting a practical file printed.

The write-up is complete, but before it can be printed, there's still one frustrating task left—manually formatting the document.

Adding official headers, watermarks, faculty tables, footers, and making sure everything is perfectly aligned can easily take several minutes. It's repetitive, time-consuming, and creates unnecessary panic just before practical checking.

After facing this process again and again, I decided to automate it instead of repeating the same manual work every time.

**LabDoc AI** is built specifically for **TCET students**, allowing them to upload their practical file, choose the required formatting options, and generate an official print-ready document in just a few seconds.

>**The goal was simple: spend less time formatting documents and more time focusing on practical work.**

---

## 🌟 Key Features

LabDoc AI has evolved from a simple formatting utility into a complete **document automation platform** built specifically for TCET students.


### 🏫 1. Supports 11 Departments at TCET

LabDoc AI now supports **all 11 engineering departments** at TCET.

Simply choose your department and the processing engine automatically applies the correct official formatting resources.

Supported Departments:

- 💻 Computer Engineering (COMP)
- 🌐 Information Technology (IT)
- 🧠 AI & Data Science (AIDS)
- 🤖 AI & Machine Learning (AIML)
- 🛡️ Cyber Security
- 📡 Internet of Things (IoT)
- 📡 Electronics & Telecommunication (E&TC)
- ⚡ Computer Science & Engineering (E&CS)
- ⚙️ Mechanical Engineering
- 🔧 Mechatronics (Additive Manufacturing)
- 🏗️ Civil Engineering

---

### 📂 2. Supports DOCX & PDF

Upload either a DOCX or PDF practical file.

The processing pipeline automatically selects the appropriate engine and generates a print-ready document while preserving the original content.

---

### 🪄 3. Official Formatting

Automatically applies official department headers, faculty tables, watermarks and custom footers without requiring any manual formatting.

---

### 📱 4. Mobile-First Experience

Designed to work seamlessly on mobile devices, allowing students to prepare practical files directly from their phones whenever required.

---


# 🔥 Core Engine Features

### 📏 Smart Header Injection Engine

Parses the DOCX structure, removes outdated headers, and inserts the latest official TCET department header while preserving the document layout.

**Highlights**

* Automatic legacy header replacement
* Department-wise dynamic header selection
* Automatic margin adjustment to prevent content shifting
* Preserves original document formatting

---

### 👨‍🏫 Smart Faculty Table Generator

Automatically inserts the official TCET faculty evaluation table into the document without affecting existing content.

**Highlights**

- Automatic faculty table insertion
- Proper alignment and spacing
- Preserves the original document layout

---

### ✒️ Intelligent Footer & Pagination Engine

Automatically adds a footer containing Name, Class, Roll Number and Page Number while maintaining proper document spacing.

**Highlights**

* Dynamic page numbering
* Automatic margin adjustment
* Layout-safe footer injection

---

### 💧 Smart Watermark Processing

Applies the official TCET watermark while preserving document readability and print quality.

**Highlights**

* Intelligent RGB threshold detection
* 45% translucent watermark rendering
* Maintains crisp document text
* Print-friendly output

---

### 📄 Cloud PDF Processing Pipeline

Processes DOCX and PDF files using a Dockerized LibreOffice runtime for reliable document conversion.

**Highlights**

* Reliable DOCX → PDF conversion
* Dockerized headless LibreOffice
* Supports DOCX and PDF workflows

---

## ⚡ Average Processing Time

| Operation | Average Time |
|-----------|-------------:|
| DOCX → DOCX Formatting | **3–5 sec** |
| PDF → PDF Processing | **5–10 sec** |
| DOCX → PDF Conversion | **15–20 sec** |

> Processing time may vary depending on document size and system load.

---

## 📊 Early Impact (Version 1)

| Metric | Result |
|--------|-------:|
| 👥 Unique Users | **164+** |
| 📄 Page Views | **365+** |
| 📢 LinkedIn Impressions | **2,300+** |
| 🏫 Departments Supported (V2) | **11** |

---

## 🚀 From Version 1 to Version 2

LabDoc AI started as a small automation tool built for a single department.

After receiving feedback from early users, the platform was completely re-engineered into Version 2, expanding support to all 11 engineering departments at TCET while introducing automatic faculty tables, intelligent footer generation, improved document processing, mobile-first workflows and a scalable backend architecture.

The project evolved from solving a small classroom problem into a scalable campus-wide document automation platform.

---

# ⚙️ Advanced System Architecture

```mermaid
flowchart TD

    A[📤 User Uploads DOCX / PDF]
    A --> B[📱 Next.js Frontend]

    B -->|Multipart Request + Selected Options| C[⚡ FastAPI Backend]

    C --> D{📄 File Type?}

    %% ---------------- DOCX PIPELINE ----------------

    D -->|DOCX| E[🧠 python-docx Processing Engine]

    E --> F[📏 Header Injection Engine]

    F --> G[(🏫 Department Assets)]

    G --> H[👨‍🏫 Faculty Table Generator]

    H --> I[✒️ Footer & Pagination Engine]

    I --> J[📐 Margin Geometry Optimizer]

    J --> K[🐳 LibreOffice Headless]

    K --> L[📄 PDF Generation]

    %% ---------------- PDF PIPELINE ----------------

    D -->|PDF| M[📄 PyMuPDF Processing Engine]

    %% ---------------- COMMON PIPELINE ----------------

    L --> N[💧 Watermark Engine]

    M --> N

    N --> O[✅ Final Print-Ready Document]

    O --> P[⬇️ Download Response]
```

---

# 🛠️ Technology Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,fastapi,python,docker,git,github,vscode" />
</p>

| Layer | Technologies |
|--------|--------------|
| **Frontend** | Next.js, React, Tailwind CSS, Shadcn UI, Lucide Icons |
| **Backend** | FastAPI, Uvicorn, Python 3.10+ |
| **Document Processing** | python-docx, PyMuPDF (fitz), Pillow (PIL) |
| **Document Conversion** | LibreOffice Headless |
| **Deployment** | Vercel, Docker, Render |

---

## 🧩 Engineering Challenges

Building LabDoc AI required solving more than document formatting.

Some of the engineering challenges included:

- Scaling from 1 department to 11 departments
- Deploying Dockerized LibreOffice on Render's free tier
- Optimizing memory usage during document conversion
- Supporting both DOCX and PDF processing pipelines
- Maintaining layout accuracy while injecting headers, faculty tables and footers

---

# 👨‍💻 Developed By

**Shivam Vishwakarma**

🎓 Computer Engineering Student @ TCET

💻 Full Stack Developer

⚡ Passionate about building real-world software that solves practical problems through automation.

---

# 🌐 Connect With Me

💼 **LinkedIn**  
[Shivam Vishwakarma](https://www.linkedin.com/in/shivam-vishwakarma-932166371/)

🌍 **Live Website**  
[lab-doc-ai.vercel.app](https://lab-doc-ai.vercel.app)

---

<div align="center">

### ⭐ If you found this project interesting, consider giving it a Star!

Your support motivates me to keep building practical software that solves real-world problems.

</div>