📱 TaskSync - Real-Time To-Do App
A cross-platform task management app built with React Native, Expo, and Convex

https://via.placeholder.com/800x500?text=TaskSync+Screenshots

✨ Features
📝 Tasks Management
✅ Add, edit, and delete tasks

✔️ Mark tasks as complete/incomplete

📊 Real-time progress tracking

⚡ Instant sync across all devices

⚙️ Settings & Customization
🌙 Dark/Light mode toggle

📈 Task statistics dashboard

🔔 Notification preferences

🗑️ Danger zone (clear all tasks)

🔄 Real-Time Sync
Powered by Convex backend

Instant updates across all connected devices

Offline-first design

🛠️ Technologies Used
React Native (Cross-platform mobile development)

Expo (Rapid development & testing)

Convex (Real-time database)

React Navigation (Tab and stack navigation)

NativeWind (Tailwind CSS for React Native)

🚀 Getting Started
Prerequisites
Node.js (v18+)

Expo CLI (npm install -g expo-cli)

Convex account (free tier available)

Installation
Clone the repository

bash
git clone https://github.com/yourusername/tasksync.git
cd tasksync
Install dependencies

bash
npm install
Set up environment variables
Create a .env file in the root directory:

text
CONVEX_DEPLOYMENT=your_convex_deployment
EXPO_PUBLIC_CONVEX_URL=your_convex_url
Start the development server

bash
npx expo start
Run Convex in a separate terminal

bash
npx convex dev
📱 Running the App
iOS Simulator: Press i in the Expo terminal

Android Emulator: Press a in the Expo terminal

Physical Device: Scan QR code with Expo Go app

🧑‍💻 Project Structure
text
tasksync/
├── app/                  # Main app components
│   ├── (tabs)/           # Tab navigation screens
│   ├── convex/           # Convex functions
│   ├── components/       # Reusable components
│   └── hooks/            # Theme and config
├── assets/               # Images and fonts and styles
└── .env                  # Environment variables
🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request.

Happy task managing! ✨