# 📱 Curator YT - Subscription Management App

A modern React Native application built with Expo for managing and tracking your digital subscriptions across multiple platforms. Keep track of your Netflix, Spotify, YouTube Premium, and dozens of other service subscriptions in one beautifully designed app.

![App Preview](public/preview.png)

## ✨ Features

- **🔐 Authentication System**
  - User registration and login
  - Forgot password functionality
  - OTP verification
  - Secure session management

- **📊 Dashboard & Analytics**
  - Visual insights into subscription spending
  - Monthly/yearly spending analysis
  - Subscription usage statistics
  - Cost optimization recommendations

- **💳 Subscription Management**
  - Add/edit/remove subscriptions
  - Track renewal dates and payments
  - Support for 25+ popular services (Netflix, Spotify, YouTube, Disney+, etc.)
  - Custom service support

- **🔔 Smart Notifications**
  - Renewal reminders
  - Payment due alerts
  - Cost optimization suggestions
  - Usage insights

- **💰 Billing & Payments**
  - Payment method management
  - Billing history tracking
  - Subscription cost analysis
  - Export financial reports

- **⚙️ Profile & Settings**
  - Personal information management
  - Security settings
  - Notification preferences
  - Dark/light theme support

## 🛠 Tech Stack

- **Framework**: [Expo](https://expo.dev/) ~55.0.17
- **Language**: TypeScript ~5.9.2
- **Navigation**: [Expo Router](https://docs.expo.dev/router/introduction/) ~55.0.13
- **Styling**: [NativeWind](https://www.nativewind.dev/) 5.0.0 (Tailwind CSS for React Native)
- **UI Components**: Custom components with Expo Vector Icons
- **Animations**: React Native Reanimated 4.2.1
- **Package Manager**: pnpm

## 🚀 Quick Start

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later)
- [pnpm](https://pnpm.io/) package manager
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- iOS Simulator (Mac) or Android Studio (for emulator)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/noor-mohammad/curator-yt.git
   cd curator-yt
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Start the development server**
   ```bash
   pnpm dev
   # or
   pnpm start
   ```

4. **Run on your preferred platform**
   ```bash
   # iOS Simulator
   pnpm ios

   # Android Emulator
   pnpm android

   # Web Browser
   pnpm web
   ```

### Development Setup

The app will automatically open in:
- [Expo Go](https://expo.dev/go) (scan QR code with your phone)
- [iOS Simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Android Emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [Web Browser](http://localhost:8081)

## 📁 Project Structure

```
curator-yt/
├── src/
│   ├── app/                    # App router pages
│   │   ├── (auth)/            # Authentication screens
│   │   ├── (tabs)/            # Main app tabs
│   │   ├── details/           # Detail screens
│   │   ├── notification/      # Notification screens
│   │   └── settings/          # Settings screens
│   ├── components/            # Reusable UI components
│   │   └── constants/         # Theme and configuration
│   └── services/              # Data services and API calls
├── assets/                    # Static assets (images, icons)
├── public/                    # Public assets
└── [config files]            # Expo, TypeScript, Tailwind configs
```

## 🔧 Available Scripts

- `pnpm dev` - Start development server
- `pnpm start` - Start Expo development server
- `pnpm android` - Run on Android emulator
- `pnpm ios` - Run on iOS simulator
- `pnpm web` - Run in web browser
- `pnpm lint` - Run ESLint for code linting

## 📱 Supported Platforms

- **iOS** (iPhone & iPad)
- **Android** (Phone & Tablet)
- **Web** (Progressive Web App)

## 🔒 Security Notice

_(⚠️ **Crucial**: Ensure your downloaded service account JSON file is explicitly ignored in your root `.gitignore` to prevent hardcoded structural credentials from leaking strictly into source control)._

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## ☕ Support

If you found this project helpful, please consider supporting the development!

<a href="https://www.buymeacoffee.com/reactbd" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

_Made with ❤️ by Noor Mohammad._

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
