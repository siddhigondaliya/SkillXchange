📱 SkillXchange Flutter Application

SkillXchange is a Flutter-based mobile application that allows users to learn, teach, and connect by exchanging skills. This project demonstrates the integration of a public REST API, JSON parsing, and dynamic UI rendering using Flutter.

---

🚀 Features

- 🔗 Fetch data from a public REST API
- 📦 Parse JSON data into Dart models
- 📋 Display users using ListView
- 💬 Navigate to a simple Chat Screen
- 🎨 Clean and responsive UI
- ⚡ Fast and lightweight Flutter app

---

🌐 API Used

This app uses the following public API:

https://jsonplaceholder.typicode.com/users

---

🛠️ Tech Stack

- Flutter
- Dart
- HTTP Package
- REST API Integration

---

📂 Project Structure

lib/
 └── main.dart

(All code is implemented in a single file for simplicity.)

---

📦 Dependencies

Add this in your "pubspec.yaml":

dependencies:
  flutter:
    sdk: flutter
  http: ^0.13.6

---

▶️ How to Run the Project

1. Clone the repository:

git clone https://github.com/your-username/skillexchange.git

2. Navigate to project folder:

cd skillexchange

3. Get dependencies:

flutter pub get

4. Run the app:

flutter run

---

📖 How It Works

1. App sends a GET request to the API
2. Receives JSON response
3. Converts JSON into Dart objects
4. Displays data in a ListView
5. On button click → navigates to chat screen

---

🎯 Learning Outcomes

- Understanding REST API integration in Flutter
- Working with asynchronous programming
- JSON parsing in Dart
- Navigation between screens
- Building UI with ListView

---

🔮 Future Enhancements

- 👤 Add user profile images
- 🔍 Search & filter skills
- 🔐 Firebase Authentication
- 💬 Real-time chat using Firebase
- 📊 GridView UI option

---

👨‍💻 Author

Developed as a Flutter learning project.

---

📄 License

This project is for educational purposes only.