# Roommate Management App

## Overview

The Roommate Management App is an Android mobile application built with React Native and Expo. It enables users to create and manage groups of roommates, providing essential tools for coordination, such as calendar scheduling, task management, and expense tracking.

## Features

- **Group Management:** Users can form and manage groups of roommates.

- **Calendar Scheduling:** Plan and share events within the group.

- **Task Management:** Assign and track household chores.

- **Emergency Notifications:** Send urgent alerts to all roommates.

- **Chat:** Real-time messaging for seamless communication.

- Expense Tracking: Split and manage shared expenses among roommates.

## Tech Stack

- **Frontend:** React Native (Expo), React-Redux
- **Backend:** Firebase (Authentication, Firestore, Storage)
- **State Management:** Redux
- **Testing:** Jest, React Native Testing Library

## Installation

1. Clone the repository:
   ```sh
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```sh
   cd roommate-management-app
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Run the app on an Android device:
   ```sh
   npx expo run:android
   ```

## Development Workflow

- Follow Agile methodologies for iterative development.
- Use Redux for state management across components.
- Utilize Firebase for authentication and real-time data storage.
- Debug and test using React Native Testing Library and Jest.

## Troubleshooting

- Ensure all dependencies are installed correctly by running:
  ```sh
  npx expo doctor
  ```
- If Firebase services are not working, check Firebase project settings and API keys.
- Resolve dependency conflicts by updating or reinstalling node modules:
  ```sh
  rm -rf node_modules package-lock.json
  npm install
  ```

## Contributors

- Ethan Tobey
- Sreya Srinidhi
- Shourya Poddar
- Jiana Kambo

