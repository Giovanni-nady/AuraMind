# AuraMind

A Headspace-inspired meditation app built with **React Native**, **Expo**, and **RevenueCat**. AuraMind helps users practice mindfulness, relaxation, and focus through guided meditations and breathing exercises.

## Features

- 🧘 Guided Meditation Sessions
- 🌿 Mindfulness Exercises
- 🎵 Relaxing Sounds & Music
- 🔔 Daily Reminders & Streaks
- 💳 In-App Subscriptions (Powered by RevenueCat)
- 🌙 Light & Dark Theme Support
- 🌍 Multi-language Support

## Tech Stack

- **React Native** - Cross-platform mobile development
- **Expo** - Simplified app development workflow
- **Nativewind** - For Styling
- **RevenueCat** - Subscription management and payments
- **React Navigation** - Smooth navigation experience
- **ExpoSecureStore** - Persistent storage for user data

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/AuraMind.git
   cd AuraMind
   ```

2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```sh
   expo start
   ```

## Configuration

To enable subscriptions, create a RevenueCat project and add your API keys to the `.env` file:

```env
REVENUECAT_PUBLIC_KEY=your_public_key
REVENUECAT_SECRET_KEY=your_secret_key
```

## Folder Structure

```
AuraMind/
│── src/
│   ├── components/    # Reusable UI components
│   ├── screens/       # App screens
│   ├── navigation/    # Navigation setup
│   ├── context/       # Global state management
│   ├── hooks/         # Custom hooks
│   ├── utils/         # Utility functions
│   ├── assets/        # Images and sounds
│── App.tsx           # Main entry file
│── package.json      # Project dependencies
│── .env.example      # Environment variables
```

## Contributing

Pull requests are welcome! Feel free to open an issue for feature requests or bug reports.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
