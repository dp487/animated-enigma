# SimpleMeditation

A modern **React Native meditation app** built with Expo. This app helps users practice mindfulness through guided meditation sessions with a clean, calming interface.

## ✨ Features

- File-based navigation using Expo Router
- Tab-based interface for easy navigation
- Meditation section with guided sessions
- Clean, minimalist design focused on user experience
- Built with TypeScript for type safety
- Styled using Tailwind CSS

## 🛠️ Tech Stack

- **Framework**: React Native + Expo
- **Navigation**: Expo Router (file-based routing)
- **Language**: TypeScript
- **Styling**: Tailwind CSS (via NativeWind or similar setup)
- **Platform**: iOS, Android, and Web

## 📁 Project Structure

```
animated-enigma/
├── app/                    # Expo Router screens
│   ├── (tabs)/
│   ├── (modal)/
│   ├── meditate/
│   ├── _layout.tsx
│   └── index.tsx
├── components/             # Reusable UI components
├── constants/              # App constants and theme
├── context/                # React Context providers
├── assets/                 # Images, fonts, icons
├── App.js                  # Entry point
├── app.json                # Expo configuration
├── tailwind.config.js      # Tailwind configuration
└── package.json
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- Expo CLI (`npm install -g expo-cli`)
- iOS Simulator / Android Emulator (or Expo Go app)

### Installation

```bash
# Clone the repository
git clone https://github.com/dp487/animated-enigma.git
cd animated-enigma

# Install dependencies
npm install
# or
yarn install

# Start the development server
npx expo start
```

Then scan the QR code with **Expo Go** or run on a simulator.

## 📱 Running on Devices

- **iOS**: `npx expo run:ios`
- **Android**: `npx expo run:android`
- **Web**: `npx expo start --web`

## 📄 License

MIT
