skill_xchange1
SkillXchange – Flutter Skill Exchange Application

📱 Project Overview

SkillXchange is a mobile application developed using Flutter that enables users to exchange skills without monetary transactions. The platform connects individuals who want to teach a skill with those who want to learn a skill, encouraging collaborative learning and community engagement.

The application allows users to create profiles, list their offered skills, specify skills they want to learn, and find matching users for skill exchange.

🎯 Objective

The main objective of this project is to create a peer-to-peer learning platform that enables users to share knowledge and develop new skills without paying for expensive courses.

✨ Key Features

👤 User Authentication

User registration and login

Secure authentication using Firebase

🧑‍💻 User Profile

Add personal information

List skills offered

List skills wanted

🔍 Skill Matching

Match users based on complementary skills

Display users who can teach the required skill

💬 Chat System

Real-time messaging between matched users

Request and accept skill exchange

⭐ Rating System

Users can rate each other after completing a session

Helps build trust within the community

🛠️ Technologies Used

Technology Purpose

Flutter Mobile app development Dart Programming language Firebase Authentication User login & signup Cloud Firestore Database for storing user data Firebase Storage Storing profile images REST API Fetching skill suggestions

📂 Project Structure

lib/ │ ├── main.dart │ ├── models/ │ └── user_model.dart │ ├── services/ │ ├── auth_service.dart │ ├── firestore_service.dart │ └── api_service.dart │ ├── screens/ │ ├── login_screen.dart │ ├── register_screen.dart │ ├── home_screen.dart │ ├── profile_screen.dart │ └── chat_screen.dart │ └── widgets/ └── skill_card.dart

🗄️ Database Structure (Firestore)

Users Collection

users └── userId ├── name ├── email ├── skills_offered [ ] ├── skills_wanted [ ] ├── rating └── location

Chats Collection

chats └── chatId ├── participants ├── messages │ ├── sender │ ├── text │ └── timestamp

🔄 Application Workflow

User registers or logs into the application.

User creates a profile and adds skills they offer and want to learn.

The application searches for users with complementary skills.

Matched users can communicate using the in-app chat feature.

After a session, users can rate each other.

🚀 Installation Guide

Clone the Repository
git clone https://github.com/siddhigondaliya/SkillXchange

Navigate to Project Folder
cd skillxchange

Install Dependencies
flutter pub get

Run the Application
flutter run

📊 Future Enhancements

AI-based skill recommendation system

Location-based user matching

Video call integration for remote learning

Skill verification badges

Session scheduling system

🎓 Educational Value

This project helps students understand:

Flutter mobile app development

Firebase authentication and database

REST API integration

JSON data parsing

UI design using Material Design

👨‍💻 Author

Student Name: Gondaliya Siddhi

Course: Computer Science / Information Technology

Project Type: Academic / College Project
