# 🔐 WalletNFC - Android Wallet App

A secure Android wallet powered by Firebase, Jetpack Compose, and NFC Tap-to-Pay using Host Card Emulation (HCE).

## 🚀 Features
- 🔐 Firebase Authentication (Email/Password)
- 🧬 Biometric login via fingerprint or face unlock
- 💳 Add, encrypt, and manage credit cards locally
- 📡 Simulated NFC Tap-to-Pay (Host Card Emulation)
- 🧾 Transaction history (mocked)
- ☁️ Firebase backend ready

## 🛠 Stack
- Kotlin + Jetpack Compose
- Firebase Auth
- Android Keystore + AES/GCM encryption
- Jetpack Navigation
- NFC HCE APIs

## 📦 Setup
1. Clone this repo
2. Add your `google-services.json` from Firebase
3. Open in Android Studio and sync Gradle
4. Run on device with NFC

## 🧠 Security
- Card data encrypted using AES via Android Keystore
- BiometricPrompt locks access to cards
- No sensitive info stored in cloud (yet)

## 🧑‍💻 Author
Built by enchirid10n 💻🧠 using Jake the AI Dev 🥷

## 🛡 License
MIT
