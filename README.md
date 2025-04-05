# 💬 ChataKai – A Smart Chat App Powered by DeepSeek R1 via Kai AI

**ChataKai** is a sleek and intelligent chat application built using **Flutter**, offering a seamless real-time messaging experience enhanced by AI. At its core, ChataKai leverages **Firebase** for backend services and integrates **Kai AI**, which utilizes **Llama-3.3-70b-versatile by Meta** to deliver conversational intelligence directly within chats.

The app allows users to authenticate securely using email/password or Google Sign-In, manage their profiles, and chat in real-time with both humans and an AI assistant. With rich markdown support, users can also send styled messages, while advanced media handling lets them upload, crop, and cache profile pictures effortlessly.

Built with flexibility in mind, ChataKai uses environment variables (`.env`) for secure API key management and handles permissions cleanly using the `permission_handler` package.

---

## 🚀 Key Features

- 🔐 **Authentication** – Secure sign-in with email/password or Google.
- ☁️ **Realtime Messaging** – Powered by Firebase Cloud Firestore.
- 🤖 **AI Chat Assistant** – Smart replies via Kai AI backed by DeepSeek R1.
- 🖼️ **Profile Picture Upload** – Image picker, cropper, and caching.
- 🧾 **Markdown Support** – Rich text formatting in messages.
- 📲 **Permissions Handling** – Manages runtime permissions with ease.
- 💾 **Local Storage** – Session persistence with Shared Preferences.

---

## 🛠️ Tech Stack

- **Flutter** – Cross-platform mobile development
- **Firebase** – Authentication, Firestore, Storage
- **Kai AI + DeepSeek R1** – AI assistant integration
- **Google Sign-In** – Social login support
- **Image Picker** – Media customization
- **Shared Preferences** – Local data storage
- **Cached Network Image** – Optimized image loading
- **Flutter Markdown & SVG** – Rich UI support

---

## 📦 Dependencies

```yaml
firebase_core: ^3.12.1
firebase_auth: ^5.5.1
cloud_firestore: ^5.6.5
firebase_storage: ^12.4.5
google_sign_in: ^6.3.0
cached_network_image: ^3.4.1
image_picker: ^1.1.2
image_cropper: ^9.1.0
permission_handler: ^11.4.0
flutter_svg: ^2.0.17
flutter_markdown: ^0.6.0
shared_preferences: ^2.2.0
flutter_dotenv: ^5.2.1

