AI-Powered Coaching Center Management System 

Project Overview

EduAI Suite is a modern, data-driven management and pedagogical platform designed to overcome operational inefficiencies in traditional coaching centers. Beyond standard database ledger features, EduAI Suite integrates Artificial Intelligence to deliver automated performance diagnostics, adaptive exam generation, targeted resource recommendations, and 24/7 AI-driven student assistance.

Key Challenges & Solutions

Manual Administrative Overheads: Replaces error-prone manual attendance and fee scheduling with automated digital loggers and notifications.

Lack of Personalization: Identifies individual learning paces and specific subject weak areas instead of delivering uniform, non-actionable feedback.

Legacy Limitations: Overcomes the absence of intelligent analytics by integrating generative AI models for personalized learning enablement.

Features

Role-Based Authentication: Secure multi-user access portals tailored for Administrators, Teachers, Students, and Parents.

AI Student Analytics Dashboard: Visual analytical charts showcasing academic growth curves, attendance rates, and AI-predicted exam outcomes.

24/7 AI Study Assistant: Embedded conversational interface powered by the Google Gemini API to resolve student queries and concept doubts instantaneously.

Smart Exam & Quiz Generator: Enables faculty to automatically compile practice papers tailored to custom topics and difficulty levels.

Attendance & Fee Tracking: Digital logger for student daily presence paired with automated fee reminder notifications.

Automated Weakness Detection: Smart recommendation engine suggesting targeted practice modules or video lectures based on low exam scores.

Technology Stack

Domain

Technology

Justification & Purpose

Frontend

React.js (Vite) + Tailwind CSS

Fast single-page rendering, highly responsive UI components.

Backend

Node.js + Express.js

Asynchronous, lightweight API architecture for real-time data handling.

Database

MongoDB (Mongoose ODM)

Flexible document-oriented NoSQL database for user profiles, logs, and AI contexts.

AI Engine

Google Gemini API (Generative AI SDK)

NLP for query resolution, automated question generation, and analytics extraction.

Deployment

Vercel (Frontend) & Render (Backend)

High-reliability continuous deployment and serverless scalability.

Team Information

Institution: Northern University of Business and Technology (NUBT), Khulna

Department: Computer Science & Engineering

Course Code & Title: CSE4104: AI-Based Software Development Project

Section & Team: Section 7C | Team T07

Course Instructor: Md. Riaz Mahmud, Assistant Professor


Team Leader

Fakir Reyad Hossain
11230321428


Team Member 02

Abdullah Sami
11230321451


Team Member 03

Tamima Zahan Bohni
11230321425

Team Member 04

Arshia Jaman
11230321432

Quick Start & Installation

Prerequisites

Node.js (v18 or higher)

MongoDB (Local instance or MongoDB Atlas URI)

Google Gemini API Key

1. Clone the Repository

git clone https://github.com/YourUsername/CSE4104-7C-T07_CoachingManagement.git
cd CSE4104-7C-T07_CoachingManagement


2. Backend Setup

cd server
npm install


Create a .env file in the server directory:

PORT=5000
MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key
JWT_SECRET=your_jwt_secret


Start the backend server:

npm run dev


3. Frontend Setup

cd ../client
npm install


Create a .env file in the client directory:

VITE_API_BASE_URL=http://localhost:5000/api


Start the frontend server:

npm run dev
