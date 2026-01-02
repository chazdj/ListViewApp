# Fruit List Android App

## Overview
An Android application that displays a scrollable list of fruits. Each fruit item includes a title, subtitle, and image. Tapping an item navigates to a detail screen showing more information about the selected fruit.

## Features

- 📋 ListView of fruits with custom titles, subtitles, and images  
- ✅ Clickable list items that open a second activity with full fruit details  
- 🔄 Explicit intents used for navigation between activities  
- 📦 Serializable data model to pass objects between screens  
- 🔙 ActionBar back arrow for smooth return navigation  
- 🔔 Snackbar confirmation on return to the main screen  
- ♿ Accessibility support with content descriptions for images

## Tech Stack
- Java  
- Android SDK  
- Android Studio  
- Material Components (Snackbar)

## Project Structure

<pre>
app/
├── java/com/example/listviewapp/
│   ├── MainActivity.java
│   ├── DetailActivity.java
│   ├── ItemAdapter.java
│   └── Item.java
├── res/layout/
│   ├── activity_main.xml
│   ├── activity_detail.xml
│   └── list_item.xml
├── res/values/
│   ├── strings.xml
│   └── themes.xml
└── drawable/
    └── fruit images (e.g., apple.png, mango.png, etc.)
</pre>

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/chazdj/ListViewApp.git
2. Open the project in Android Studio
3. Build and run the app on an emulator or physical Android device

## What I Learned
- Implementing a ListView with custom adapters in Android
- Handling item clicks and navigation between activities
- Passing complex objects between screens using serialization
- Enhancing UI with images, accessibility, and Material design components
  
## Demo Video

🎥 [Click to view demo video](assets/ListViewApp.mp4)

## Author
Created by **Chastidy Joanem**  
GitHub: [@chazdj](https://github.com/chazdj)
