# Chain Word Game

## 🎮 About the Game
The **Chain Word Game** is a fast-paced, real-time multiplayer word association game. Players must submit words that start with the last letter of the previous word within a limited time. The game continues until only one player remains.

## 🚀 Features
- 🔥 **Real-time multiplayer gameplay** using Supabase Realtime.
- ⏳ **Turn-based mechanics** with a countdown timer.
- ❌ **Word validation** to prevent repeated words.
- 🏆 **Leaderboards & history tracking** for competition.
- 📱 **Mobile-first design** built with React Native (Expo).
- 🔒 **Secure authentication** with Supabase Auth.
- 🌍 **Web support** deployed via AWS S3 & CDN for high performance.
- 🌐 **Live on**: [chainword.devstavan.in](https://chainword.devstavan.in)

## 🏗️ Tech Stack
- **Frontend**: React Native (Expo), MobX for state management.
- **Backend**: Supabase (Postgres, Realtime, Edge Functions) & AWS EC2.
- **Authentication**: Supabase Auth (JWT-based login).
- **Deployment**:
  - **Mobile**: Expo EAS for mobile.
  - **Web**: AWS S3 & CDN for fast distribution.
  - **Backend**: Deployed on AWS EC2 for better performance and control.

## 📂 Project Structure
```
/chain-word-game
├── /apps
│   ├── /mobile  # React Native Expo app
│   ├── /web  # Web version hosted on AWS S3 & CDN
│   ├── /backend  # Backend hosted on AWS EC2
├── /packages
│   ├── /shared  # Common utilities for validation, API calls
│   ├── /config  # Shared environment configurations
│   ├── /ui  # Reusable UI components
```

## 🎯 How to Play
1. **Join a game room** with other players.
2. A **random word** is generated as the starting word.
3. **Players take turns** submitting words based on the last letter.
4. **Each player has 5 seconds** to respond, or they lose a life.
5. The **last player standing wins**!

## 🛠️ Setup & Installation
### Prerequisites
- Install **Node.js** and **Yarn**
- Setup **Expo CLI**
- Sign up for **Supabase** and get project keys
- AWS account with **S3, CloudFront, and EC2** access

### Installation
```sh
git clone https://github.com/your-repo/chain-word-game.git
cd chain-word-game
yarn install
```

### Running the App
```sh
yarn start
```

## 🌍 Deployment
### **Web App (AWS S3 & CDN)**
- **AWS S3** for static hosting.
- **CloudFront CDN** for optimized performance and lower latency.
- **Automatic deployments** using CI/CD pipelines.
- **Live on**: [chainword.devstavan.in](https://chainword.devstavan.in)

### **Mobile App**
- **Expo EAS Build** for Android & iOS.
- OTA (Over-the-Air) updates for instant fixes.

### **Backend (AWS EC2)**
- **Backend services deployed on AWS EC2** for full control over API logic.
- **Supabase Postgres** for scalable data storage.
- **Supabase Realtime** for instant updates.

## 🎉 Future Enhancements
- 🎙️ **Voice input for word submission**
- 🤖 **AI-powered challenges** for solo play
- 🏆 **Private game rooms & social features**

## 🤝 Contributing
Pull requests are welcome! Please follow our **contribution guidelines**.

## 📜 License
This project is licensed under the **MIT License**.

---
### 🚀 Ready to Play?
Get started now and test your word association skills! 📝🔥
