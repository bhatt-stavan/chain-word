# 📜 Chain Word Game - README

## 🎮 About the Game

The **Chain Word Game** is a fast-paced, real-time multiplayer word association game where players submit words starting with the last letter of the previous word. The game continues until one player remains.

## 🚀 Features

- 🏆 **Multiplayer gameplay** powered by Supabase Realtime.
- ⏳ **Turn-based mechanics** with a countdown timer.
- 📜 **Word validation** to ensure valid gameplay.
- 📊 **Leaderboard & history tracking** for performance comparison.
- 📱 **Cross-platform support** (Mobile & Web via React Native Web).
- 🔒 **Secure authentication** with Supabase Auth.
- 🌍 **D********eployed on AWS (EC2 for backend, S********3 & CloudFront for web hosting).**

## 🏗️ Tech Stack

### **Frontend**

- **React Native Web (Expo)** → Unified mobile & web app.
- **MobX** → State management.
- **React Navigation** → Cross-platform routing.
- **Tailwind CSS** → UI styling.

### **Backend**

- **Supabase (Postgres, Realtime, Edge Functions)** → Database & Realtime API.
- **AWS EC2** → Hosting backend APIs.
- **AWS S3 + CloudFront** → Web deployment & optimization.

## 📂 Project Structure

```
/chain-word-game
├── /apps
│   ├── /mobile  # React Native Web (Expo) app
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

### **Web App (AWS S3 & CloudFront)**

- **AWS S3** for static hosting.
- **CloudFront CDN** for performance & lower latency.
- **Automatic CI/CD deployment pipeline**.
- **Live on**: [chainword.devstavan.in](https://chainword.devstavan.in)

### **Mobile App**

- **Expo EAS Build** for Android & iOS.
- OTA (Over-the-Air) updates for instant fixes.

### **Backend (AWS EC2 + Supabase)**

- **Supabase Postgres** for scalable data storage.
- **Supabase Realtime** for instant updates.
- **AWS EC2** for backend API hosting.

## 🎉 Future Enhancements

- 🎙️ **Voice input for word submission**
- 🤖 **AI-powered challenges** for solo play
- 🏆 **Private game rooms & social features**

## 🤝 Contribution

Pull requests are welcome! Please follow our **contribution guidelines**.

## 📜 License

This project is licensed under the **MIT License**.

---

### 🚀 Ready to Play?

Get started now and test your word association skills! 📝🔥

