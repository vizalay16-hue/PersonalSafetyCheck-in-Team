# 🛡️ Personal Safety Check-In App (SafetyU)

## 1. Project Overview

Personal Safety Check-In App (SafetyU) is a mobile application designed to improve personal safety, especially for people who travel or go places alone.

The application allows users to check in, share their location, and notify trusted contacts when they need assistance or fail to respond to a safety check.

## 2. Project Objectives

- Improve personal safety for people traveling alone.
- Allow users to check in and share their current location.
- Provide an emergency notification system.
- Notify trusted contacts when an emergency occurs.
- Help users access emergency assistance more efficiently.

## 3. Main Features

- **Safety Check-In:** Users can create and manage safety check-ins.
- **Location Sharing:** Share location information during check-ins and emergencies.
- **Emergency Escalation:** Escalate alerts from primary to secondary contacts and emergency status.
- **Trusted Contacts:** Manage primary and secondary emergency contacts.
- **Emergency Notifications:** Send emergency alerts and messages.
- **Police Station Support:** Assign a police station to handle an emergency.
- **Chat and Directions:** Support communication and location directions.

## 4. Technologies Used

### Frontend
- Flutter
- Dart

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Other Technologies
- Firebase
- Git and GitHub

## 5. Project Structure

```text
PersonalSafetyCheck-in-Team/
│
├── Frontend_SafetyU/
│   └── safetyU_app/
│
├── backend_SafetyU/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── services/
│   │   └── server.js
│   ├── package.json
│   └── package-lock.json
│
└── .gitignore
```

## 6. Installation Instructions

### Prerequisites

Install the following tools:

- [Node.js](https://nodejs.org/)
- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)
- Visual Studio Code

### Backend Setup

1. Clone the repository:

```bash
git clone https://github.com/vizalay16-hue/PersonalSafetyCheck-in-Team.git
```

2. Navigate to the backend:

```bash
cd PersonalSafetyCheck-in-Team/backend_SafetyU
```

3. Install dependencies:

```bash
npm install
```

4. Configure your environment variables in `src/config/.env`.

5. Start the backend server:

```bash
node src/server.js
```

### Frontend Setup

1. Open another terminal.
2. Navigate to the Flutter application:

```bash
cd Frontend_SafetyU/safetyU_app
```

3. Install Flutter dependencies:

```bash
flutter pub get
```

4. Run the application:

```bash
flutter run
```

## 7. How to Run the Project

1. Start the MongoDB database and configure the required backend services.
2. Start the Node.js backend server.
3. Connect a mobile device or Android emulator.
4. Run the Flutter application.
5. Register or log in and explore the safety check-in features.

## 8. Project Purpose

SafetyU aims to make traveling alone safer by providing an accessible way to check in, share location information, and contact trusted people during emergencies.

---

**Project Name:** Personal Safety Check-In App (SafetyU)  
**Repository:** [GitHub - PersonalSafetyCheck-in-Team](https://github.com/vizalay16-hue/PersonalSafetyCheck-in-Team)