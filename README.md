# The NOTES App 

A modern, production-ready Notes application built for Android using **Jetpack Compose** and **Room Database**. This project demonstrates full local data persistence and clean architecture principles as part of an Android development internship.

## ✨ Features

### Task 1: Core Functionality
- [x] Clean, modern UI built entirely with Jetpack Compose
- [x] Material 3 design system with custom purple theme
- [x] Create, view, and delete notes seamlessly
- [x] Responsive layout with proper padding and spacing

### Task 2: Data Persistence & Architecture
- [x] **Room Database** integration for persistent local storage
- [x] Full **CRUD operations** (Create, Read, Update, Delete)
- [x] MVVM Architecture with ViewModel and Repository pattern
- [x] Automatic UI updates when database changes
- [x] Offline-first functionality (works without internet)

### Visual Enhancements
- [x] Pastel-colored sticky note cards with shadows
- [x] Professional empty state with iconography
- [x] Smooth animations and transitions
- [x] Edit dialog with pre-filled content

## 🛠️ Tech Stack

- **Language:** Kotlin
- **UI Toolkit:** Jetpack Compose (Material 3)
- **Database:** Room (SQLite abstraction)
- **Architecture:** MVVM (Model-View-ViewModel)
- **Async:** Kotlin Coroutines & Flow
- **Dependency Injection:** Manual (ViewModelFactory)

## 📁 Project Structure

app/src/main/java/com/example/thenotesapp/
── MainActivity.kt # UI Layer (Composables)
├── NoteEntity.kt # Data Layer (Database Schema)
├── NoteDao.kt # Data Access Object
├── NoteDatabase.kt # Room Database Instance
├── NoteRepository.kt # Repository Pattern
└── NotesViewModel.kt # ViewModel Layer


## 🚀 How to Run

1. Clone this repository
2. Open in **Android Studio** (latest version recommended)
3. Sync Gradle files
4. Run on an emulator or physical device (API 24+)

## 🎯 Learning Outcomes

This project demonstrates mastery of:
- Android local data persistence with Room
- Reactive programming with Kotlin Flow
- Clean architecture separation of concerns
- Modern Android UI development with Compose
- Production-level code organization

---
*Built as part of Android Development Internship - Task 1 & 2*
