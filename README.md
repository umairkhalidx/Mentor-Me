# MentorMe App  

### 📌 Description  
**MentorMe** is an **Android mentorship platform** built with **Kotlin**, designed to connect students and mentors worldwide. The app offers a **real-time, interactive ecosystem** with secure authentication, dynamic chat systems (text/voice/video), session booking, push notifications, and offline support—all backed by **Firebase Realtime Database, Storage, and Agora API** for seamless communication.  

### 🔥 Key Features  
✔ **Auth & Profiles**  
- Secure signup/login/logout with Firebase Auth.  
- Customizable profiles (DP, cover photo, bio edits).  
- Auto-navigation: Splash → Home (if logged in) or Signup → Profile (new users).  

✔ **Mentor Discovery**  
- Browse mentors on the homepage.  
- **Search & filter** mentors by expertise/availability.  
- Add mentors to **favorites** for quick access.  
- Leave **reviews/ratings** based on sessions.  

✔ **Real-Time Chat & Calls**  
- **1-on-1 & group chats** with text, images, files, and voice notes.  
- **Audio/video calls** via Agora API.  
- **Message editing/deleting** (within 5 mins).  
- **Screenshot detection** with notifications.  
- Online/offline status indicators.  

✔ **Sessions & Notifications**  
- Book/cancel mentorship sessions.  
- **Push notifications** (new messages, session updates, screenshots).  
- Notification history screen.  

✔ **Offline Support**  
- Cached images (**Picasso** library).  
- Send queued messages when back online.  
- View old chats/bookings without internet.  

---

## 📱 Sample UI Screens  
<p align="center">
  <img src="User Interface/Splashscreen.png" alt="Splash Screen" width="30%" />
  <img src="User Interface/login.png" alt="Login Screen" width="30%" />
  <img src="User Interface/Signup.png" alt="Signup Screen " width="30%" />
</p>
<p align="center">
  <img src="User Interface/home.png" alt="Home Screen" width="30%" />
  <img src="User Interface/search.png" alt="Search Screen" width="30%" />
  <img src="User Interface/Search%20Results.png" alt="Search Results Screen" width="30%" />
</p>
<p align="center">
  <img src="User Interface/Mentor%20Profile.png" alt="Mentor Profile Screen" width="30%" />
  <img src="User Interface/Book%20Mentor.png" alt="Book Mentor Screen" width="30%" />
  <img src="User Interface/Mentor%20Review.png" alt="Mentor Review Screen" width="30%" />
</p>
<p align="center">
  <img src="User Interface/Profile.png" alt="Profile Screen" width="30%" />
  <img src="User Interface/Profile%20Edit.png" alt="Edit Profile Screen" width="30%" />
  <img src="User Interface/Booked%20Sessions.png" alt="Booked Sessions Screen" width="30%" />
</p>
<p align="center">
  <img src="User Interface/Chats.png" alt="Chats Screen" width="30%" />
  <img src="User Interface/Chat%20Screen.png" alt="Chat Screen" width="30%" />
  <img src="User Interface/Voice%20Call.png" alt="Voice Call Screen" width="30%" />
</p>

---

### ⚙️ Installation  
1. **Download the APK** from the [Releases](https://github.com/your-repo/mentorme/releases) section.  
2. Install on an Android device.  
3. **Sign up** or log in to start exploring mentors!  

### 🛠️ Tech Stack  
- **Frontend**: Kotlin, XML (Android Studio)  
- **Backend**: Firebase (Auth, Realtime DB, Storage, Cloud Messaging)  
- **APIs**: Agora (calls), Picasso (image caching)  
- **Testing**: Espresso 
