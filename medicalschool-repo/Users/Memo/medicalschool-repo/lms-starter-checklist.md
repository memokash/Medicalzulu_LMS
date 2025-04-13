# 🚀 LMS Project Kickoff Checklist

**Date:** April 09, 2025

Welcome to the Medical School Quizzes LMS build! Here's your foundational checklist and task layout for a clean start to the project.

---

## 🧠 Project Overview

This LMS is designed to deliver:
- Structured medical education content
- Quizzes with CEU tracking
- Course eBooks (SCORM/EPUB/HTML)
- Real-time analytics and user progression
- Firebase-based storage, hosting, and authentication

---

## 📁 Folder & Codebase Setup

- [ ] Initialize Git repo
- [ ] Create `/src` folder with subdirectories:


- [ ] Install React + Tailwind CSS
- [ ] Set up React Router
- [ ] Set global font (Space Mono)
- [ ] Apply Edmate HTML template structure

---

## 🔐 Firebase Setup

- [ ] Create Firebase project
- [ ] Enable Email/Password Auth
- [ ] Create Firestore database
- [ ] Set rules for `users`, `courses`, `comments`
- [ ] Add Firebase SDK to `/firebase/config.ts`

---

## ✨ Core Pages to Build

- [ ] `Home.tsx`
- [ ] `AllCourses.tsx`
- [ ] `CourseDetails.tsx`
- [ ] `Login.tsx` / `Signup.tsx`
- [ ] `Dashboard.tsx`
- [ ] `AdminDashboard.tsx`
- [ ] `UserProfile.tsx`

---

## 🧱 Component Breakdown

- [ ] `Navbar.tsx` (mobile toggle)
- [ ] `Footer.tsx`
- [ ] `CourseCard.tsx`
- [ ] `CourseDetail.tsx`
- [ ] `CommentThread.tsx`
- [ ] `ProgressBar.tsx`
- [ ] `QuizViewer.tsx`

---

## 🔍 Initial Features to Implement

- [ ] Firebase Auth (Login/Signup)
- [ ] Course page rendering from Firestore
- [ ] Comment threads per course
- [ ] Quiz viewer with answer tracking
- [ ] User dashboard (notes, progress, CEUs)
- [ ] Admin course creation (title, image, content links)

---

## 🧪 First Tests & QA

- [ ] Test login/signup flows
- [ ] Verify Firestore writes/reads
- [ ] Basic mobile responsiveness
- [ ] Check quiz scoring + display
- [ ] Progress saving per user

---

Let's build something unforgettable.
