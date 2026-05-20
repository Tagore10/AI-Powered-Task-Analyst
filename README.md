# SmartEval AI

## AI Powered Assignment Evaluation & Academic Integrity Platform

---

# 📌 Overview

SmartEval AI is a cloud-integrated academic evaluation platform developed to automate and modernize the traditional assignment evaluation process using Artificial Intelligence, OCR technology, and AWS cloud services.

The main goal of this project is to reduce the manual workload of faculty members and provide a scalable system capable of handling assignment uploads, student submissions, AI-based evaluation, plagiarism analysis, and intelligent feedback generation.

Traditional academic evaluation systems often consume a large amount of time and effort. Faculty members manually verify assignments, compare answers, provide feedback, and calculate scores, which becomes inefficient when handling large numbers of submissions. Existing systems also struggle to process scanned PDFs, handwritten documents, and duplicate content detection.

SmartEval AI addresses these challenges by integrating:

* Cloud Computing
* Artificial Intelligence
* OCR Processing
* Database Management
* Academic Integrity Analysis

The platform allows faculty members to upload assignments and students to submit their solutions in PDF format. Uploaded files are processed using AWS Textract for text extraction and analyzed using Google Gemini AI to generate intelligent evaluation reports.

The project is designed with a production-level cloud architecture using AWS RDS MySQL for centralized database management and AWS S3 for secure cloud-based file storage.

---

# 🚀 Key Features

## 🔐 Authentication & Role Management

* Secure Faculty Registration
* Secure Student Registration
* Login Authentication System
* Role-Based Access Control
* Session Handling
* User Profile Management

---

## 📚 Assignment Management

Faculty members can:

* Create assignments
* Upload assignment PDFs
* Set assignment deadlines
* Add assignment descriptions
* Set difficulty levels
* Manage student submissions

---

## 📝 Student Submission System

Students can:

* View assignments
* Upload assignment PDFs
* Submit scanned documents
* Track submission status
* View AI-generated feedback
* Access evaluation reports

---

## ☁️ Cloud Storage Integration

The platform uses AWS S3 for:

* Assignment PDF storage
* Student submission storage
* Report management
* Scalable cloud-based file handling

All uploaded files are securely stored in cloud infrastructure instead of local storage.

---

## 📄 OCR Text Extraction

AWS Textract is integrated to extract:

* Printed text
* Scanned text
* Tables
* Paragraphs
* Document content from PDFs

This enables the platform to process scanned assignments and convert them into machine-readable content for AI analysis.

---

## 🤖 AI Powered Evaluation

The project integrates Google Gemini AI for intelligent assignment evaluation.

The AI engine analyzes:

* Assignment relevance
* Answer quality
* Technical correctness
* Completeness
* Missing concepts

The system automatically generates:

* Marks
* Suggestions
* Strengths
* Weaknesses
* Missing points
* Detailed feedback

---

## 🛡️ Plagiarism & Integrity Analysis

SmartEval AI includes an advanced integrity analysis system capable of:

* Text similarity analysis
* Cosine similarity detection
* Duplicate content analysis
* Similarity scoring
* Integrity scoring
* AI-based plagiarism analysis

Future versions also include:

* Duplicate image detection
* Screenshot similarity analysis
* AI integrity reports

---

## 📊 Dashboard System

### Faculty Dashboard

Faculty can:

* View assignments
* Track submissions
* Analyze plagiarism reports
* View AI evaluation results
* Access integrity analysis

### Student Dashboard

Students can:

* View assignments
* Submit solutions
* View marks
* Access feedback
* Analyze integrity reports

---

# 🏗️ Project Architecture

The project follows a cloud-integrated AI architecture:

Frontend
↓
Flask Backend APIs
↓
AWS RDS MySQL
↓
AWS S3 Storage
↓
AWS Textract OCR
↓
Gemini AI Evaluation
↓
Evaluation Reports & Dashboards

This architecture provides:

* Scalability
* Security
* Cloud storage
* AI processing
* Centralized management

---

# ⚙️ Complete Workflow

## Step 1 — Faculty Uploads Assignment

Faculty members log in and upload assignment PDFs through the dashboard interface.

The faculty can provide:

* Assignment title
* Description
* Deadline
* Difficulty level

The uploaded assignment file is stored securely inside AWS S3 bucket.

Assignment metadata is stored in AWS RDS MySQL database.

---

## Step 2 — Student Uploads Submission

Students log in and upload their assignment solutions in PDF or scanned format.

The submission is:

* Uploaded through frontend
* Processed by Flask backend
* Stored securely in AWS S3

Submission details are stored in the database.

---

## Step 3 — OCR Processing

AWS Textract processes:

* Assignment PDFs
* Student submissions

Textract extracts:

* Text
* Tables
* Paragraphs
* Structured content

The extracted data becomes the input for AI evaluation.

---

## Step 4 — Plagiarism & Similarity Analysis

The system performs:

* Text similarity analysis
* Cosine similarity calculations
* Duplicate content comparison
* Integrity analysis

This helps identify:

* copied answers
* suspicious submissions
* duplicated content

---

## Step 5 — AI Evaluation

Gemini AI receives:

* Assignment content
* Student submission content

The AI evaluates:

* Correctness
* Quality
* Completeness
* Technical understanding

The system generates:

* Marks
* Feedback
* Suggestions
* Missing points
* Strengths
* Weaknesses

---

## Step 6 — Result Storage

All evaluation results are stored in AWS RDS MySQL.

This includes:

* scores
* feedback
* integrity reports
* plagiarism analysis

---

## Step 7 — Dashboard Visualization

Faculty and students can access detailed evaluation reports through interactive dashboards.

The dashboards display:

* assignment information
* submission status
* evaluation scores
* plagiarism percentage
* integrity score
* AI feedback

---

# 🧠 AI & NLP Components

The project integrates multiple AI and NLP workflows:

* OCR extraction
* Text similarity detection
* AI evaluation
* Integrity scoring
* Semantic comparison
* AI feedback generation

---

# 🗄️ Database Design

The system uses AWS RDS MySQL with a relational schema.

## Main Tables

### users

Stores:

* faculty accounts
* student accounts
* authentication details

---

### assignments

Stores:

* assignment metadata
* S3 file references
* deadlines
* faculty assignment data

---

### submissions

Stores:

* student submissions
* submission tracking
* S3 references
* status information

---

### evaluation_results

Stores:

* AI-generated scores
* feedback
* plagiarism reports
* integrity analysis
* evaluation details

---

# ☁️ AWS Services Used

## AWS S3

Used for:

* cloud file storage
* assignment PDFs
* submission PDFs
* report management

---

## AWS Textract

Used for:

* OCR processing
* scanned PDF extraction
* text extraction

---

## AWS RDS MySQL

Used for:

* centralized cloud database management
* scalable relational storage

---

# 💻 Technology Stack

## Frontend

* HTML5
* CSS3
* JavaScript

---

## Backend

* Python
* Flask

---

## Database

* AWS RDS MySQL

---

## Cloud Services

* AWS S3
* AWS Textract

---

## AI Integration

* Google Gemini API

---

## Libraries & Tools

* boto3
* pymysql
* sklearn
* Pillow
* imagehash
* REST APIs
* VS Code
* MySQL Workbench

---

# 🔒 Security Features

* Secure authentication system
* Password hashing
* Cloud-based secure storage
* Role-based authorization
* Database constraints
* API-based communication

---

# 📈 Future Enhancements

The future scope of SmartEval AI includes:

* Advanced plagiarism engine
* Duplicate image detection
* Screenshot integrity analysis
* Handwriting recognition
* JWT authentication
* Real-time notifications
* Mobile application
* Admin dashboard
* Multi-language support
* AI-powered analytics
* Blockchain certificate verification

---

# 👨‍💻 Team Contributions

The project was developed collaboratively with contributions in:

* Backend API Development
* AWS Cloud Integration
* Frontend Development
* Database Architecture
* AI Workflow Integration
* OCR Processing
* Documentation & Testing

---

# 🎯 Project Outcome

SmartEval AI successfully demonstrates how Artificial Intelligence and Cloud Computing can transform academic workflows by:

* automating evaluation,
* improving scalability,
* reducing manual effort,
* and enhancing academic integrity.

The project creates a foundation for intelligent educational systems capable of supporting modern digital learning environments.

---

# 📌 Conclusion

SmartEval AI is not just a traditional full stack application. It combines:

* AI-powered evaluation,
* OCR processing,
* cloud infrastructure,
* plagiarism analysis,
* and intelligent automation

to build a modern academic evaluation ecosystem.

The platform showcases the integration of cloud computing, AI services, and scalable backend architecture to solve real-world educational challenges efficiently and intelligently.
