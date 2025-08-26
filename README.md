# QRReaderApp – React Native

**QRReaderApp** is a fast and user-friendly mobile application built with **React Native** that allows users to scan and generate QR codes. It provides a seamless experience for reading QR codes, copying or sharing scanned data, and managing scan history.

---

## Table of Contents

* [Features](#features)
* [Demo](#demo)
* [Tech Stack](#tech-stack)
* [Installation](#installation)
* [Usage](#usage)
* [Folder Structure](#folder-structure)
* [Contributing](#contributing)
* [License](#license)

---

## Features

* Scan QR codes using the device camera.
* Generate QR codes from custom text or URLs.
* Save scan history locally for future reference.
* Copy or share scanned content directly.
* Simple, responsive, and intuitive user interface.
* Dark mode support.

---

## Demo

![QRReaderApp Demo](link-to-screenshots-or-gif)

---

## Tech Stack

* **Framework:** React Native
* **QR Scanning:** `react-native-camera` or `react-native-qrcode-scanner`
* **State Management:** Redux / Context API
* **Navigation:** React Navigation
* **QR Generation:** `react-native-qrcode-svg`
* **Storage:** AsyncStorage for storing scan history
* **Styling:** Styled Components / React Native Paper / Tailwind CSS

---

## Installation

1. **Clone the repository**

```bash
git clone <your_github_repo_url>
cd <folder_name>
```

2. **Install dependencies**

```bash
npm install
```

3. **Run the app**

```bash
# expo
npx expo start
```

---

## Usage

* Open the app and allow camera permissions.
* Scan a QR code by pointing the camera at it.
* View the scanned content and choose to copy, share, or save it.
* Generate QR codes from text, URLs, or other content using the "Generate" screen.
* Access your scan history anytime from the history section.

---

## Folder Structure

```
qrreaderapp/
├── android/
├── ios/
├── src/
│   ├── assets/
│   ├── components/
│   ├── screens/
│   ├── navigation/
│   ├── redux/ or context/
│   ├── utils/
│   └── App.js
├── .env
├── package.json
└── README.md
```

### 👨‍💻 Developer

Prince Bhatt

📧 Email: princebhatt316@gmail.com

🌐 Portfolio: [Prince Bhatt](https://princebhatt03.github.io/Portfolio)

💼 GitHub: [princebhatt03](https://github.com/princebhatt03)

💬 LinkedIn: [Prince Bhatt](https://www.linkedin.com/in/prince-bhatt-0958a725a/)

📄 License

This project is created and owned by Prince Bhatt

✨Thank you for connecting...
