# 🧠 Android Quiz App

An interactive Android Quiz Application built using **Kotlin** and **XML** that allows users to test their knowledge on various topics.  
The app features a clean UI, question navigation, score calculation, and result display.

---

## 📱 Features

- 🎯 Multiple-choice questions  
- 🔄 Next and Previous navigation  
- 🧾 Result summary with total score  
- 🕹️ Restart quiz option  
- 🧠 Randomized questions and answers  
- 🌙 Dark Mode Support (Optional)  
- 💾 Save user scores locally using SharedPreferences (Optional)  

---

## 🏗️ Tech Stack

| Component | Technology |
|------------|-------------|
| **Language** | Kotlin |
| **UI Design** | XML Layouts |
| **IDE** | Android Studio |
| **Architecture** | MVVM (recommended) |
| **Storage (Optional)** | SharedPreferences / Room |

---
Android-Quiz-App/
```
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/ishanwalia/quizapp/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   ├── QuestionModel.kt
│   │   │   │   ├── QuizActivity.kt
│   │   │   │   ├── ResultActivity.kt
│   │   │   └── res/
│   │   │       ├── layout/
│   │   │       │   ├── activity_main.xml
│   │   │       │   ├── activity_quiz.xml
│   │   │       │   ├── activity_result.xml
│   │   │       └── values/
│   │   │           ├── strings.xml
│   │   │           ├── colors.xml
│   │   │           ├── themes.xml
│   │   └── AndroidManifest.xml
│   └── build.gradle
│
└── README.md
```
---

## 🚀 How to Run the App

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ishanwalia7579/Android-Quiz-App.git



2.Open in Android Studio


3.Sync Gradle and wait for dependencies to download


4.Connect your device or start an emulator


5.Click ▶ Run



6.🧩 Example Code
```
data class QuestionModel(
    val id: Int,
    val question: String,
    val options: List<String>,
    val correctAnswerIndex: Int
)
```

7.🎨 Screens (Add Previews)
Home ScreenQuiz ScreenResult Screen🏠🧠🏁
(You can place screenshots in a /screenshots/ folder and reference them here.)

#💡 Future Enhancements


1.⏱️ Add timer per question


2.📚 Add category selection


3.☁️ Integrate Firebase for storing high scores


4.🔊 Add sound effects and animations



# 👨‍💻 Developer
Ishan Walia
📍 Lovely Professional University
🔗 LinkedIn
💻 GitHub

# 📜 License
This project is open-source under the MIT License.
Feel free to use and modify it for your own learning or projects.

# ✅ Pro Tip:
If you add screenshots, use this path:
![Home Screen](screenshots/home.png)
![Quiz Screen](screenshots/quiz.png)
![Result Screen](screenshots/result.png)


