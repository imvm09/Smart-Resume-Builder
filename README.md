# 🚀 Smart Resume Builder (AI ATS Optimizer)
**Lab Task:** 10.A — Mini Project 1: AI-Based Application Development  
**Tools Used:** Google Gemini, HTML5/CSS3/JavaScript, Canva, GitHub Pages  

---

## 🌐 Live Application Demo
👉 **[Click Here to Open Live Smart Resume Builder](https://imvm09.github.io/Smart-Resume-Builder/)**

---

## 🎯 1. Project Definition & Objective
* **Problem Statement:** Students and fresh graduates often get rejected by Applicant Tracking Systems (ATS) due to weak action verbs, poor formatting, and missing role-specific keywords.
* **Objective:** Build an AI-powered web application that converts raw candidate inputs into an ATS-friendly, single-page resume tailored to a target job role.
* **Expected Outcome:** A responsive browser-based tool capable of generating and exporting a clean PDF resume in under 10 seconds.

---

## ⚙️ 2. System Architecture & Development Process
The application operates on a 3-stage pipeline engineered using **Google Gemini** prompt templates:
1. **Input Layer:** Structured HTML form capturing Education, Skills, Internship Experience, Projects, Certifications, and Achievements.
2. **AI Prompt & Logic Engine:** Maps the selected job role (*Software Developer, Data Analyst, UI/UX Designer, Digital Marketer*) to industry keywords and upgrades passive descriptions into action-verb bullet points.
3. **ATS Output & Export Layer:** Renders a clean single-column layout with a `@media print` stylesheet for one-click PDF export.

---

## 🧪 3. Testing, Evaluation & Improvements

| Test ID | Scenario | Initial Output | Issue Found | Improvement Made |
| :--- | :--- | :--- | :--- | :--- |
| **TC-01** | Weak project text (*"Made a weather site"*) | Copied exact weak phrasing | Lacked recruiter action verbs | Added automated action-verb wrappers (*"Engineered"*, *"Leveraged"*) |
| **TC-02** | Exporting to PDF | Printed input form alongside resume | Unusable as a standalone document | Added `@media print` CSS rules to isolate the A4 resume card |
| **TC-03** | Empty optional sections | Displayed blank headings | Looked incomplete for freshers | Added dynamic section-hiding logic in JavaScript |

---

## 📊 4. Final Presentation
* **Canva Presentation:** [Paste your Canva Link Here after creating slides]
