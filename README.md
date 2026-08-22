# 🚀 Mars Photos App

A beginner-friendly Android application built using **Kotlin**, **Jetpack Compose**, and **Retrofit** to explore API communication and JSON data handling.

## 📖 Overview

This project demonstrates how an Android application can fetch data from a remote API and display meaningful information to the user.

The app initially used Retrofit with a **Scalars Converter** to retrieve API responses as raw JSON strings. This helped in understanding how network communication works and how APIs return data.

As the project progressed, **Kotlin Serialization** was integrated to deserialize JSON responses into Kotlin data objects. This provided a more structured, readable, and type-safe way of handling API data.

Currently, the application:

- Connects to the Mars Photos API.
- Fetches photo data from the internet.
- Converts JSON responses into Kotlin objects using Kotlin Serialization.
- Displays the total number of Mars images retrieved from the API.
- Uses Retrofit and Coroutines for asynchronous network operations.
- Updates the UI using Jetpack Compose state management.

## 🛠 Technologies Used

- Kotlin
- Jetpack Compose
- Retrofit
- Kotlin Serialization
- Kotlin Coroutines
- Android Studio

## 🎯 Learning Outcomes

Through this project, I learned:

- How to perform network requests in Android applications.
- How Retrofit communicates with REST APIs.
- The difference between handling raw JSON strings and deserializing JSON into Kotlin objects.
- How Kotlin Serialization simplifies JSON parsing.
- How API data flows from the network layer to the UI.
- Basic state management in Jetpack Compose.
- Working with asynchronous operations using Coroutines.

## 🔄 Project Evolution

### Phase 1: API Connectivity
- Configured Retrofit for network communication.
- Retrieved API responses as raw JSON strings using `ScalarsConverterFactory`.

### Phase 2: Understanding API Responses
- Explored the structure of JSON data returned by the API.
- Displayed the raw response for verification and debugging.

### Phase 3: JSON Deserialization
- Added Kotlin Serialization dependencies.
- Created data models matching the API response structure.
- Replaced scalar response handling with automatic JSON deserialization.

### Phase 4: Data Display
- Parsed API responses into Kotlin objects.
- Retrieved and displayed the total number of Mars images returned by the API.

---

Built as part of my Android development learning journey with Kotlin, Jetpack Compose, and modern Android networking practices.
