# ChatRoom App (Android / Java)

A simple Android chat-style interface built using **Java** and **Android Studio**, designed to demonstrate basic UI interaction, event handling, and Android activity lifecycle concepts.

This project focuses on handling button click events, updating UI components dynamically, and logging user interactions for debugging purposes.

---

## 📱 Features

- Simple chat-style user interface
- Button click event handling
- Dynamic text updates using `TextView`
- Logging user interactions with Android Logcat
- Clean and beginner-friendly Android architecture

---

## 🧠 Core Concepts Demonstrated

- Android Activity lifecycle (`onCreate`)
- View binding using `findViewById`
- Event handling with `onClick`
- UI updates at runtime
- Debug logging using `Log.d`

---

## 🧩 Code Overview

The main logic is implemented in `MainActivity.java`.

```java
public void handleButton(View view){
    TextView text = findViewById(R.id.textView);
    text.setText("Button was passed...");
    Log.d(MsTag,"Button was passed...");
}
```

## ▶️ How It Works

- When the user presses the button:
  - The text on the screen is updated
  - A debug message is printed to Logcat

### App Flow

1. The app launches and loads `activity_main.xml`
2. A button is displayed on the screen
3. When the button is clicked:
   - The `handleButton()` method is triggered
   - The `TextView` text changes
   - A log message is recorded in Logcat

---

## 🛠️ Tech Stack

- **Language:** Java  
- **Platform:** Android  
- **IDE:** Android Studio  
- **UI:** XML Layouts  
- **Minimum SDK:** Compatible with standard Android APIs  

---

## 🎯 Learning Outcomes

- Understanding basic Android application structure
- Handling user interactions in Android
- Updating UI components dynamically at runtime
- Using Logcat for debugging and logging
- Writing clean and readable Java code for Android development

---

## 👤 Author

**Yuyao Tu**

This project was developed as part of an Android programming course to practice UI interaction and event-driven development.

---

## 📄 License

This project is intended for **educational purposes only**.
