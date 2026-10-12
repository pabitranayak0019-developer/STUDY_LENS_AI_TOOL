# study-lens-ai-tool
# 📚 STUDY LENS AI TOOL

> An AI-powered educational companion that transforms study materials, notes, handwritten text, and document images into structured summaries, Q&A, and interactive study tools.

---

## 📌 Project Overview
**STUDY LENS AI TOOL** is designed to simplify the learning process for students and educators. By leveraging Optical Character Recognition (OCR) and Large Language Models (LLMs), the tool automatically processes educational documents, extracts text, and generates actionable study materials such as summaries, doubt-solving answers, and revision quizzes.

---

## ⚙️ How It Works (Workflow)

```mermaid
graph TD
    A[User Uploads Image / PDF] --> B[Pre-processing & OCR Extraction]
    B --> C[Text Structuring & AI Prompt Generation]
    C --> D[AI Processing - Gemini API / OpenAI API]
    D --> E[Feature Generation - Summaries, Q&A, Quizzes]
    E --> F[Interactive UI Output & Download Options]

[ User Uploads Image/PDF ]
           │
           ▼
[ Pre-processing & OCR Extraction (Tesseract / Vision API) ]
           │
           ▼
[ Text Structuring & AI Prompt Generation ]
           │
           ▼
[ AI Processing (Google Gemini API / OpenAI API) ]
           │
           ▼
[ Feature Generation (Summaries, Q&A, Quizzes) ]
           │
           ▼
[ Interactive UI Output & Download Options ]




# 📚 Study Lens AI Tool

> An intelligent, client-side web application designed to supercharge learning, document analysis, and study workflows using modern AI capabilities.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38BDF8?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

---

## 🌟 Features

- **Interactive AI Assistant:** Direct client-side integration with advanced generative AI models for answering study questions and summarizing complex topics.
- **Smart Study Tools:** Tools tailored for creating notes, structuring revision material, and breaking down tough concepts.
- **Responsive & Modern UI:** Built with a clean, distraction-free interface optimized for desktop and mobile screens.
- **Zero-Backend Architecture:** Lightweight and fast static deployment with direct API connectivity.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 / Tailwind CSS, Modern JavaScript (ES6+)
- **AI Integration:** RESTful APIs / Google Gemini API client integration
- **Storage:** Browser `localStorage` for session history and user preferences

---

## 📂 Project Structure

```text
STUDY_LENS_AI_TOOL/
├── index.html        # Main entry point & application layout
├── assets/           # Stylesheets, images, and custom CSS
│   ├── css/
│   └── js/           # Application logic, API handlers, and UI controllers
└── README.md         # Project documentation
