 # FocusLearn • E-Learning Platform
<img width="1920" height="1080" alt="Screenshot 2025-11-20 174321" src="https://github.com/user-attachments/assets/df4c3f3e-6381-480e-adb3-bb73d7503c85" />

 
 

**FocusLearn** is a single-page, interactive e-learning platform where users can enroll in courses, track their progress, and generate certificates upon completion. It features Firebase Authentication, Firestore integration, a lecture player, reminders, and a responsive modern interface with dark/light mode.

---

## 🚀 Features

1. **User Authentication**
   - Firebase Email/Password Signup & Login
   - User info displayed in dashboard
   - Persistent login state

2. **Course Management**
   - 3 Sample courses: Python, JavaScript, HTML
   - Embedded lecture videos (YouTube)
   - Track lesson completion with Previous / Mark as Read / Next
   - Dashboard shows overall progress

3. **Firestore Integration**
   - Store user enrollments and lecture progress
   - Persist progress across sessions

4. **Certificate Generation**
   - PDF certificate upon course completion
   - Preview and download options
   - Fully dynamic with user name, course, and completion date

5. **UI & UX**
   - FocusLearn design system
   - Responsive for desktop, tablet, mobile
   - Light blue/violet color theme
   - Dark mode toggle
   - Smooth animations and scroll transitions

6. **Extra**
   - Study reminders with date & time
   - User menu with logout and dashboard access

---

## 🗂 Project Structure

focuslearn/
├─ index.html
├─ README.md
├─ src/
│ ├─ css/
│ │ └─ styles.css
│ ├─ js/
│ │ └─ app.js
│ └─ assets/
│ ├─ logo.png
│ └─ banner.png
└─ .gitignore


- `index.html` – main SPA structure
- `styles.css` – all styling, light & dark mode
- `app.js` – core JS: auth, Firebase, courses, lectures, PDF certificate
- `assets/` – images, icons, banners

---

## ⚡ Prerequisites

- Node.js (optional for local dev server)
- Firebase Project with:
  - **Authentication** enabled
  - **Firestore Database** enabled
- Modern browser (Chrome, Edge, Firefox)

---

## 🔧 Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/focuslearn.git
cd focuslearn


Configure Firebase:

Create a Firebase project

Enable Email/Password Authentication

Enable Firestore Database

Copy your Firebase config and replace it in app.js:

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};


Open index.html in your browser:

You can also serve via Live Server in VS Code for live reload:

npx live-server

📄 How to Use

Click Sign Up or Login to access your dashboard.

Explore courses under the Courses section.

Enroll in a course to start lectures.

Use Previous / Mark as Read / Next buttons to track progress.

Complete all lessons to unlock the certificate.

Download or preview your PDF certificate.

Add reminders to schedule your study sessions.

💻 Technologies Used

HTML5, CSS3, JavaScript (ES6)

Firebase Authentication & Firestore

HTML2Canvas + jsPDF (certificate generation)

Responsive design (Flexbox & Grid)

Dark/Light mode toggle with CSS variables

📌 Future Improvements

Add more courses and categories dynamically

Integrate quiz & assessments per course

Add social sharing for certificates

Push notifications for reminders

Mobile app version using React Native
 
<img width="1920" height="1080" alt="Screenshot 2025-11-20 174409" src="https://github.com/user-attachments/assets/f6a875d8-ea20-4465-8324-65e1868dbec4" />
<img width="1920" height="1080" alt="Screenshot 2025-11-20 174421" src="https://github.com/user-attachments/assets/05198087-1580-4172-97dc-c1c82bc4cbe7" />
<img width="1920" height="1080" alt="Screenshot 2025-11-20 174432" src="https://github.com/user-attachments/assets/ffb151bf-d599-4c68-966b-77765ea36447" />
<img width="1920" height="1080" alt="Screenshot 2025-11-20 174438" src="https://github.com/user-attachments/assets/1c68ddd9-0705-45cb-b1ee-54a4e17977fe" />
