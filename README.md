# 🏥 CareChannel — Personal Healthcare & Appointment Notes Android App

A native Android mobile application developed using **Kotlin** and **SQLite** to help users record, organize, update, and track personal healthcare notes, doctor channeling details, and medical reminders.

---

## ✨ Key Features

* **Create Healthcare Notes (`AddNoteActivity`):** Quickly add new doctor channeling notes, symptoms, prescriptions, or appointment details.
* **View & Manage Records (`MainActivity` & `NotesAdapter`):** Clean RecyclerView-based interface displaying all saved health records in an organized list.
* **Edit & Delete Entries (`UpdateNoteActivity`):** Update existing medical notes or remove outdated records seamlessly.
* **Offline Local Storage (`NoteDataBaseHelper`):** Persistent local data storage powered by Android SQLite, ensuring fast access without an internet connection.

---

## 🛠️ Tech Stack

* **Language:** Kotlin
* **Platform:** Android SDK
* **Database:** SQLite (`SQLiteOpenHelper`)
* **UI Components:** XML Layouts, RecyclerView, Material Components
* **Build System:** Gradle (Kotlin DSL)

---

## 📂 Project Structure

```text
CareChannel-main/
├── app/
│   └── src/
│       └── main/
│           ├── java/com/example/myapplication/
│           │   ├── MainActivity.kt         # Main dashboard displaying saved health notes
│           │   ├── AddNoteActivity.kt      # Screen for creating new records
│           │   ├── UpdateNoteActivity.kt   # Screen for editing existing records
│           │   ├── Note.kt                 # Data model class
│           │   ├── NoteDataBaseHelper.kt   # SQLite database CRUD operations
│           │   └── NotesAdapter.kt         # RecyclerView adapter for note items
│           ├── res/                        # XML layouts, drawables, fonts, and themes
│           └── AndroidManifest.xml         # App configuration & activity declarations
└── build.gradle.kts                        # Project build configuration
