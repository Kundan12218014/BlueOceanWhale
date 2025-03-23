
---

# BlueOceanWhale - Chat Application

## Overview

BlueOceanWhale is a modern chat application built with React, TypeScript, and Firebase. It provides users with a seamless and intuitive platform for real-time messaging, group chats, and more. This project serves as a starting point for developers looking to create their own chat applications or learn more about React and Firebase integration.

## Features

* **Real-time Messaging:** Send and receive messages instantly.
* **User Authentication:** Secure user signup and login with email/password, Google, and Facebook.
* **Private and Group Chats:** Create one-on-one conversations or group chats with multiple participants.
* **Profile Management:** Update display names and profile photos.
* **Dark/Light Theme:** Toggle between light and dark themes for optimal viewing experience.
* **Firebase Integration:** Utilizes Firebase for authentication, database, and storage.

## Technologies Used

* **React:** A JavaScript library for building user interfaces.
* **TypeScript:** A typed superset of JavaScript that enhances code quality and maintainability.
* **Vite:** A fast build tool and development server for modern web projects.
* **Tailwind CSS:** A utility-first CSS framework for rapid UI development.
* **Firebase:** A comprehensive platform for building web and mobile applications, providing authentication, database, storage, and more.
* **Lucide React:** Beautifully simple, pixel-perfect icons for React.
* **React Hot Toast:** A library for displaying elegant toast notifications.
* **React Router DOM:** A standard library for routing in React applications.

## Prerequisites

Before you begin, ensure you have the following installed:

* **Node.js:** Version 18 or higher. You can download it from [nodejs.org](https://nodejs.org/).
* **npm:** The Node.js package manager, which comes with Node.js.

## Installation

Follow these steps to get the project up and running on your local machine:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Kundan12218014/blueOceanWhale.git
    cd blueOceanWhale
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

## Configuration

1. **Firebase Project Setup:**

    * Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.
    * Enable Email/Password, Google, and Facebook authentication methods in the Authentication section.
    * Create a Firestore database in test mode.
    * Create a Storage bucket.
    * Obtain your Firebase configuration object from the Firebase Console.

2. **Environment Variables:**

    Create a `.env.local` file in the root of your project and add your Firebase configuration:

    ```env
    VITE_FIREBASE_API_KEY="YOUR_API_KEY"
    VITE_FIREBASE_AUTH_DOMAIN="YOUR_AUTH_DOMAIN"
    VITE_FIREBASE_PROJECT_ID="YOUR_PROJECT_ID"
    VITE_FIREBASE_STORAGE_BUCKET="YOUR_STORAGE_BUCKET"
    VITE_FIREBASE_MESSAGING_SENDER_ID="YOUR_MESSAGING_SENDER_ID"
    VITE_FIREBASE_APP_ID="YOUR_APP_ID"
    VITE_FIREBASE_MEASUREMENT_ID="YOUR_MEASUREMENT_ID"
    ```

    Replace the placeholder values with your actual Firebase configuration.

## Running the Application

1. **Start the development server:**

    ```bash
    npm run dev
    ```

    This command starts the Vite development server. You can view the application in your browser at the provided local server URL (usually `http://localhost:5173`).

## Building for Production

To build the application for production, run:

```bash
npm run build
```

This command creates an optimized build of your application in the `dist` directory.

## Firebase Deployment

1. **Install Firebase Tools:**

    If you haven't already, install the Firebase CLI globally:

    ```bash
    npm install -g firebase-tools
    ```

2. **Login to Firebase:**

    ```bash
    firebase login
    ```

3. **Initialize Firebase:**

    Run the following command and follow the prompts to initialize Firebase in your project:

    ```bash
    firebase init
    ```

4. **Deploy to Firebase Hosting:**

    ```bash
    firebase deploy --only hosting
    ```

## Firestore Indexes

To deploy Firestore indexes, run:

```bash
firebase deploy --only firestore:indexes
```

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

## License

This project is licensed under the [MIT License](LICENSE).

---
