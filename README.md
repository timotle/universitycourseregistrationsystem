# 🎓 University Course Registration System

## 🌐 Live App

You can try the project here:

https://uwcourseregistrationsystem.vercel.app/

## 📁 Project Documentation

You can view our milestones, product workbook, and other project documentation here:

https://drive.google.com/drive/folders/1wLqfzgl5gKaewQ-XQvSlbI8jXvkFMb11?usp=sharing

## 📌 Project Overview

This project is an advisor-student communication channel for course registration support. Students can submit registration help requests, and those requests reach an advisor queue where advisors can review student needs, check registration risks, and decide the next best action.

The prototype is designed from the advisor perspective because advisors are the key stakeholder for this workflow. The main goal is to help advisors quickly understand which students need help, why they are at risk, and what schedule or communication step should happen next.

## ✨ Features

- 🧑‍🎓 View students who need registration help from an advisor queue
- 📨 Track student requests related to full-time status, course seats, degree progress, and registration timing
- 📚 Preview course options with seats, requirements, meeting times, and advisor notes
- 🧠 Build recommended schedule plans and backup scenarios
- ⚠️ Surface warnings for full-time enrollment, financial aid, waitlists, and course conflicts
- ✅ Record advisor actions like messaging a student, requesting an override, saving notes, or flagging follow-up
- 📋 Keep next steps organized so advisors know what still needs to happen

## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript

## ⚙️ How It Works

🧑‍💼 **Step 1: Advisor reviews the queue**

The advisor starts by looking at students who need registration support. Each student card shows the main risk, current credits, and registration timing.

📚 **Step 2: Advisor checks the student's plan**

The advisor can review the student's course needs, current schedule, recommended plan, backup plans, and system warnings.

💬 **Step 3: Advisor takes action**

After reviewing the situation, the advisor can send the schedule to the student, request an override, message the student, save advising notes, or flag the case for follow-up.

## 💻 Local Setup

This is a single-page prototype, so there are no packages to install.

1. Clone the repository:

```bash
git clone https://github.com/timotle/universitycourseregistrationsystem.git
cd universitycourseregistrationsystem
```

2. Open `index.html` in your browser.

## 🚧 What Still Needs Development

- 🔐 Add real login roles for students and advisors
- 🗃️ Connect submitted student requests to a real database
- 🔔 Add notifications when advisors respond to students
- 🔄 Integrate real course seat, prerequisite, and degree audit data
- 🌐 Improve accessibility and mobile support for real advising use
