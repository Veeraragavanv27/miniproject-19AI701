# 🎯 AI-Powered Multi-Input Quiz Generator

A smart web-based application that automatically generates quizzes from **multiple input formats** such as **PDF documents, audio files, text input, and web URLs**.  
The system uses **Natural Language Processing (NLP)** techniques to extract meaningful content and convert it into **interactive multiple-choice questions**, creating a **gamified learning environment**.

---

## 📌 Project Overview

The **AI-Powered Multi-Input Quiz Generator** is designed to simplify quiz creation for students, teachers, and self-learners. Instead of manually preparing questions, users can upload content or provide input in different formats, and the system automatically generates quizzes.

### Key Objectives
- Reduce manual effort in quiz preparation  
- Support multiple learning content formats  
- Improve engagement through gamified quizzes  
- Enable quick assessment and self-evaluation  

---

## 🚀 Features

### 🔄 Multi-Input Quiz Generation

#### 1️⃣ PDF-Based Quiz Generation
- Upload lecture notes, textbooks, or study materials in PDF format  
- Automatically extracts text using PDF parsing  
- Generates MCQs from important sentences  

#### 2️⃣ Audio-Based Quiz Generation
- Upload recorded lectures or explanations  
- Converts speech to text using speech recognition  
- Generates quiz questions from transcribed content  

#### 3️⃣ Text-Based Quiz Generation
- Directly paste any textual content  
- Useful for quick quiz creation  

#### 4️⃣ URL / Web-Based Quiz Generation
- Provide a webpage link  
- Extracts meaningful content using web scraping  
- Generates quizzes from online articles or blogs  

---

## 🎮 Gamified Quiz Environment
- Multiple-choice questions (MCQs)  
- Real-time score evaluation  
- Instant feedback after quiz submission  
- Interactive and learner-friendly interface  

---

## 🧠 How It Works

1. **Input Collection**  
   User provides input in the form of PDF, audio, text, or URL  

2. **Content Extraction**  
   - PDF → Text extraction  
   - Audio → Speech-to-text conversion  
   - URL → Web scraping  
   - Text → Direct processing  

3. **Text Processing (NLP)**  
   - Sentence segmentation  
   - Keyword identification  
   - Important sentence selection  

4. **Quiz Generation**  
   - Fill-in-the-blank question creation  
   - Multiple-choice option generation  
   - Correct answer storage  

5. **Evaluation & Results**  
   - User submits answers  
   - System calculates score  
   - Results displayed instantly  

---

## 🛠️ Technology Stack

### Backend
- Python  
- Flask  

### NLP & Processing
- SpeechRecognition  
- PyPDF2  
- BeautifulSoup  
- Natural Language Processing (NLP)  

### Frontend
- HTML5  
- CSS3  
- JavaScript  
- Bootstrap  

---

## 📊 Functional Modules

| Module | Description |
|------|-------------|
| Input Handler | Accepts PDF, audio, text, or URL |
| Text Extractor | Extracts content from input |
| NLP Processor | Processes and filters content |
| Quiz Generator | Generates MCQs |
| Quiz Evaluator | Calculates score |
| Result Manager | Displays performance |

---

## 🌐 Web Routes

| Route | Method | Description |
|------|--------|-------------|
| `/` | GET | Home page |
| `/create-quiz` | GET | Quiz creation page |
| `/api/generate` | POST | Generate quiz |
| `/api/quiz/<id>` | GET | Fetch quiz |
| `/api/submit` | POST | Submit answers |
| `/api/result/<id>` | GET | View results |

---

## 🧪 Testing

### ✔ Black Box Testing
- Verified quiz generation accuracy  
- Tested all input formats  
- Checked result correctness  

### ✔ White Box Testing
- Validated NLP processing logic  
- Verified quiz generation algorithms  
- Tested API workflows  

---

## 📈 Results & Discussion

The system successfully generates quizzes from all supported input formats with good accuracy.  
The gamified interface improves learner engagement and assessment efficiency.

---

## 🔮 Future Enhancements

- AI-based difficulty level adjustment  
- User authentication & profiles  
- Leaderboard and badges  
- Voice-based quiz answering  
- Mobile application support  

---

## 📄 Conclusion

The **AI-Powered Multi-Input Quiz Generator** demonstrates the effective use of NLP and web technologies to automate quiz creation.  
It reduces manual effort, supports diverse learning materials, and enhances the learning experience.

---

## ✍️ Author

**Veeraragavan V**  
Developed as a comprehensive **AI-powered quiz generation and learning assessment system**, designed to enhance interactive learning through automated quiz creation from multiple input formats.

⭐ If you find this project useful, please consider giving it a star!
