## 📘 SchedetBot – Cybersecurity Awareness Chatbot

SchedetBot is a multi-tab **Windows Forms** application that serves as a cybersecurity learning assistant. It allows users to chat with an intelligent bot, test their knowledge through a quiz, manage tasks, and set reminders — all while promoting cybersecurity best practices.

---

### 🧠 Features

#### 🤖 Chatbot Assistant

* Responds to keywords like `phishing`, `password`, `VPN`, etc.
* Detects **greetings**, **farewells**, and **sentiments** (positive/negative).
* Offers **context-aware cybersecurity tips**.
* Logs recent activity (use `show activity log` in chat).
* Auto-switches tabs based on user commands (`quiz`, `task`, `remind`).

#### 🧪 Cybersecurity Quiz

* 10 multiple-choice questions on core cybersecurity topics.
* Real-time feedback on answers (correct/incorrect).
* Displays a summary of questions and correct answers.
* Tracks and displays quiz scores.

#### ✅ Task Manager

* Add, edit, and delete personal tasks.
* Fields for task name, description, time, and status.
* Task status options: Pending, In Progress, Completed.

#### ⏰ Reminder Setter

* Add reminders using plain English, e.g., “Drink water at 14:30”.
* Checks reminders every minute using a built-in timer.
* Alerts via popup when reminder time is reached.

---

### 🖥️ Technologies

* `C#` with `.NET Windows Forms`
* `System.Windows.Forms` for GUI
* `System.Media.SoundPlayer` for greeting audio
* `Regular Expressions` for parsing reminders and chatbot logic

---

### 🚀 Getting Started

1. **Clone or Download** the project:

   ```bash
   git clone https://github.com/yourusername/SchedetBot.git
   ```

2. **Open in Visual Studio**

   * Open the solution file `.sln`.
   * Make sure your startup project is set to `SchedetBot`.

3. **Add Greeting Audio (Optional)**

   * Place a `.wav` file named `Greetings.wav` in:

     ```
     SchedetBot\files\Greetings.wav
     ```
   * This will play when the app launches.

4. **Run the Application**

   * Hit `Start` or `F5` in Visual Studio.

---

### 🧠 Example Chat Commands

* `"hello"` → Friendly greeting from the bot.
* `"quiz"` → Switch to the Quiz tab.
* `"phishing"` → Tips on phishing detection.
* `"remind me to take a break at 15:00"` → Sets a reminder.
* `"show activity log"` → Lists recent interactions.

---

### 📁 Folder Structure

```
SchedetBot/
├── Form1.cs              # Main logic
├── Form1.Designer.cs     # UI components
├── Program.cs            # App entry point
├── files/
│   └── Greetings.wav     # (Optional) Welcome audio
├── README.md             # You're here!
```

---

### 🧑‍💻 Developer Info

**Project Title**: Cybersecurity Awareness Chatbot (SchedetBot)
**Author**: Kgothatso Masekwameng
**Course**: PROG6221pt1
**Tools Used**: Visual Studio 2022+, .NET Framework / .NET 6+, Windows Forms

---

### ✅ Future Enhancements

* Save tasks and reminders to file or database.
* Speech-to-text chatbot input.
* Animated chat UI with avatars.
* More question sets for quizzes.

