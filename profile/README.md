# TalkNest: Real-Time Chat Application

## Introduction
This project is a full-fledged real-time chat application that enables users to communicate through text messages, video calls, and audio calls. It utilizes Node.js, Express, Firebase, React, Socket.io, and WebRTC to provide a seamless and interactive communication platform.

## Features
- **User Authentication:** Secure login and registration functionality, including Google Sign-In integration.
- **Real-Time Messaging:** Instant text messaging capabilities using Firebase Firestore and Socket.io for live updates.
- **Video and Audio Calls:** WebRTC-based real-time video and audio calls, supported by peer-to-peer connections.
- **User Profile Management:** Users can create and update their profiles.
- **User Search:** Functionality to search for other users within the platform.
- **Chat Context Management:** Utilizes React context for efficient state management across the chat application.

## Setup and Installation
1. **Clone the Repository:** `git clone [https://github.com/TalkNest]`
2. **Install Dependencies:** Navigate to the project directory and run `npm install` to install the required dependencies.
3. **Firebase Configuration:** Set up Firebase in the Firebase Console and update the `.env` file with your project's configuration details.
4. **Start the Server:** Run `node server.js` to start the backend server.
5. **Launch the Application:** Run `npm start` in the client directory to launch the React application.

## Technologies Used
- Backend: Node.js, Express, Firebase Firestore, Firebase Auth, Socket.io
- Frontend: React, Context API, simple-peer, socket.io-client
- Others: WebRTC, Firebase Admin SDK

## Contribution Guidelines
Contributors are welcome to enhance the functionalities of the chat application. Please follow the guidelines below:
- **Fork the Repository:** Fork the project to your GitHub account.
- **Create a Feature Branch:** Work on new features or bug fixes in a separate branch.
- **Commit Changes:** Use meaningful commit messages that clearly describe the changes made.
- **Open a Pull Request:** Submit a pull request from your feature branch to the main project for review.

## License
This project is licensed under the [MIT License](LICENSE.md). Feel free to use, modify, and distribute the code as you see fit.

## Contact
For any questions or suggestions, please reach out to [yuqi.guo17@gmail.com](mailto:yuqi.guo17@gmail.com) or open an issue in the GitHub repository.
