# Hackathob-Collaborative-Platform
SUBMIISION- NOT FULL APP BUT RELEVENT ONLY FOR HACKATHON >



# Collaborative Coding Platform

A **real-time collaborative coding platform** where multiple users can write and edit code together with live WebSocket synchronization. Includes a **Monaco Editor**, animated UI, and room-based collaboration.

## 🚀 Features

- **Live Code Collaboration:** Users can create/join rooms to code in real-time.
- **WebSocket Integration:** Ensures real-time updates between users.
- **Monaco Editor:** A feature-rich code editor (same as VS Code).
- **Room-based System:** Users can only join valid room IDs.
- **Theater-Style Animation:** Engaging UI with smooth transitions.
- **Minimize/Maximize Code Windows:** Users can resize their editor panels.

## 📜 Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technology Stack](#technology-stack)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)


## 📂 Project Structure
```plaintext
📦 collaborative-coding
 ┣ 📂 app
 ┃ ┣ 📜 page.tsx      # Main landing page
 ┃ ┣ 📜 session.tsx   # Handles real-time collaboration
 ┣ 📂 components/ui
 ┃ ┣ 📜 button.tsx    # Custom buttons
 ┃ ┣ 📜 input.tsx     # Input fields
 ┣ 📂 server
 ┃ ┣ 📜 index.ts      # WebSocket Server (Node.js + Socket.io)
 ┣ 📜 package.json    # Project dependencies
 ┣ 📜 README.md       # Project documentation
 ┣ 📜 tsconfig.json   # TypeScript config
```

## 💻 Technology Stack
- **Frontend:** Next.js, React, TypeScript, Tailwind CSS
- **Editor:** Monaco Editor
- **Backend:** Node.js, Express, Socket.io
- **Deployment:** Vercel / Netlify

## 🔄 How It Works
1. **User creates a room.** A unique room ID is generated.
2. **Other users join using the room ID.**
3. **Code syncs in real-time** between all users using WebSockets.
4. **Users can minimize/maximize their editor windows.**
5. **Host can close the room** when the session ends.

## 🤝 Contributing
1. **Fork the repo**
2. **Create a new branch:** `git checkout -b feature-branch`
3. **Commit changes:** `git commit -m "Add new feature"`
4. **Push to GitHub:** `git push origin feature-branch`
5. **Create a Pull Request**



#####STILL NEED TO FIX MINOR ISSUES AND OPTIMISATION. SOME OPERATIONS WORK ON LOCAL END AND NOT YET ON WEBSITE. REMAIN PAITENT TILL FINAL ROUND.
THIS CODE DOESNT INLCUDE FULL HOSTING AS THAT IS WITH THE DEVLOPERS RIGHTS TO USE AND PRIVATE.

LINK TO THE WEBSITE-----  https://v0-coding-session-website.vercel.app/


---

💡 *Built with ❤️ by GURVIR SINGH , ABHIJEET KUMAR SINGH and CHANDAN KARTIK.
