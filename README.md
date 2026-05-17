# Copy-Text: ATS Resume Template Utility

A lightweight, minimal web utility designed to host and provide one-click clipboard access to an ATS-friendly resume generation prompt.

This tool was specifically created as an accessible resource for the YouTube tutorial:
**[Create an ATS Friendly Resume: Step by Step Malayalam Guide](https://youtu.be/OiVPtLSdygE)** by **ANANDHU**.

## 📌 Context & Purpose

When building a high-scoring Applicant Tracking System (ATS) friendly resume, relying on AI models (like Groq, ChatGPT, or Claude) can drastically speed up the formatting and keyword optimization process. 

This repository serves a single, functional purpose: hosting the exact prompt template referenced in the video, removing the friction of manual copying from YouTube descriptions or disorganized text files. 

## 🚀 How to Use

1. **Visit the Live Site**: Go to the GitHub Pages link provided in the video description.
2. **Copy the Formula**: Click the **"Copy Text"** button to automatically copy the entire prompt and template to your clipboard.
3. **Generate Your Resume**: 
    - Paste the copied text into your preferred AI Chatbot (Groq is recommended in the tutorial).
    - Fill in your specific details (Name, Skills, Experience, Education).
    - Use the **XYZ Formula** (Accomplished [X] as measured by [Y], by doing [Z]) for your bullet points.
4. **Format**: Once the AI generates your markdown text, copy the output into Google Docs, adjust the typography (Arial, Calibri, or Times New Roman), and export as a single-column PDF.

## 🛠 Technical Details

* **Tech Stack**: Pure HTML, CSS, and Vanilla JavaScript.
* **Architecture**: A single `index.html` file utilizing the `navigator.clipboard.writeText()` API.
* **Hosting**: Deployed seamlessly via GitHub Pages.

## ⚠️ Note for Technical Recruiters

*If you are viewing this repository from my GitHub profile:* Please note that this is not a showcase of complex software engineering or architecture. It is a strictly functional, rapid-deployment utility built to solve a specific workflow problem for my YouTube audience and freelance resume-building clients. 

For technical projects involving RAG-based architectures, AI integrations, and database management, please refer to the other pinned repositories on my profile.
