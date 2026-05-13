# Curly ➰

Curly is a universal mobile application built with **Expo** and **React Native**, designed for subscription management. It features a modern tech stack including **NativeWind v5** for styling and **Expo Router** for file-based navigation.

## 🚀 Tech Stack

- **Framework:** [Expo](https://expo.dev/) (SDK 54)
- **Library:** [React Native](https://reactnative.dev/) (0.81.5)
- **Routing:** [Expo Router](https://docs.expo.dev/router/introduction/)
- **Styling:** [NativeWind v5](https://www.nativewind.dev/) (Tailwind CSS for React Native)
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **State/Animations:** React Native Reanimated

## 📁 Project Structure

```text
Curly/
├── app/                  # Expo Router directory (File-based routing)
│   ├── (auth)/           # Authentication routes (Sign-in, Sign-up)
│   ├── (tabs)/           # Main application tabs (Insights, Settings, Subscriptions)
│   ├── subscriptions/    # Dynamic subscription routes
│   ├── _layout.tsx       # Root layout
│   └── onboarding.tsx    # Onboarding screen
├── assets/               # Images, fonts, and static assets
├── constants/            # Theme, data, and icon constants
├── components/           # Reusable UI components (TODO: Add components here)
├── global.css            # Global Tailwind CSS styles
├── app.json              # Expo configuration
├── package.json          # Dependencies and scripts
└── tsconfig.json         # TypeScript configuration
```

## 📋 Requirements

- [Node.js](https://nodejs.org/) (LTS)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Expo Go](https://expo.dev/go) (for physical device testing) or an Emulator (Android Studio / Xcode)

## 🛠️ Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Curly
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm start
   ```

## 📜 Available Scripts

- `npm start`: Starts the Expo development server.
- `npm run android`: Opens the app in an Android emulator.
- `npm run ios`: Opens the app in an iOS simulator.
- `npm run web`: Opens the app in a web browser.
- `npm run lint`: Runs ESLint to check for code quality.
- `npm run reset-project`: Resets the project to a blank state (use with caution).

## 🔐 Environment Variables

Currently, no environment variables are explicitly defined in the project root.
- TODO: Add any API keys or configuration variables here as they are implemented.

## 🧪 Testing

Testing infrastructure is not yet fully implemented.
- TODO: Setup Jest and React Testing Library for unit and component tests.
- Run linting with:
  ```bash
  npm run lint
  ```

## 📄 License

- TODO: Specify the license (e.g., MIT, Apache 2.0).
