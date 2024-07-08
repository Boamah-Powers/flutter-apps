# Expense Tracker

## Description

Expense Tracker is a mobile application built using Flutter, designed to help users manage their expenses effectively. This app allows users to add, view, and categorize their expenses, providing a seamless and intuitive experience. With Firebase integration, Expense Tracker ensures that all data is securely stored and easily accessible across multiple devices. Additionally, the app features a dynamic chart implemented using the fl_chart package from pub.dev, giving users a visual representation of their spending habits.

## Installation Instructions

To run the Expense Tracker app on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Boamah-Powers/flutter-apps.git
   cd flutter-apps/expense_tracker
   ```

2. **Install Dependencies**:
   Make sure you have Flutter installed on your machine. You can follow the instructions [here](https://flutter.dev/docs/get-started/install) if you haven't installed Flutter yet. Once Flutter is installed, run the following command to install the necessary dependencies:
   ```bash
   flutter pub get
   ```

3. **Set Up Firebase**:
   - Go to the [Firebase Console](https://console.firebase.google.com/).
   - Create a new project or select an existing project.
   - Add an Android/iOS app to your Firebase project.
   - Download the `google-services.json` (for Android) or `GoogleService-Info.plist` (for iOS) file and place it in the appropriate directory of your Flutter project.
   - Follow the Firebase setup instructions for Flutter [here](https://firebase.flutter.dev/docs/overview).

4. **Run the App**:
   Connect your device or start an emulator, then run:
   ```bash
   flutter run
   ```

5. **Enjoy Using Expense Tracker**:
   Your Expense Tracker app should now be up and running!

## Usage

The Expense Tracker app allows users to add and manage their expenses effortlessly. Here’s a step-by-step guide on how to use the app:

### Adding an Expense

1. **Open the App**:
   Launch the Expense Tracker app on your device.

2. **Navigate to Add Expense Screen**:
   Tap on the button to add a new expense, which will take you to the Add Expense screen.

3. **Fill in Expense Details**:
   - **Amount**: Enter the amount spent.
   - **Category**: Select a category for your expense from the list. If the desired category does not exist, you can create a new one.
   - **Date**: The current date is pre-filled, but you can select a different date if needed.

4. **Save the Expense**:
   After filling in all the necessary details, tap the save button to record your expense. The app uses a unique ID for each expense to ensure data integrity.

5. **View Expenses**:
   Return to the main screen to see the list of all recorded expenses. You can view detailed information for each expense by tapping on it.

### Visualizing Expenses

- **Charts**:
  The app features a dynamic chart that visually represents your spending habits. Navigate to the chart section to see a graphical breakdown of your expenses by category and date.

### Firebase Integration

All your expenses are securely stored in Firebase, ensuring that your data is safe and can be accessed from multiple devices. The app automatically syncs your data with Firebase, providing a seamless experience.

## Features

Expense Tracker offers a comprehensive set of features to help users manage their expenses efficiently:

- **Add Expenses**: Easily add new expenses by specifying the amount, category, and date. Categories can be selected from an existing list or created on the fly.
  
- **Expense List**: View a detailed list of all recorded expenses on the main screen. Each expense entry displays the amount, category, and date, providing a quick overview of your spending.

- **Charts and Graphs**: Visualize your expenses with dynamic charts powered by the fl_chart package. The charts give you a clear understanding of your spending patterns over time, helping you make informed financial decisions.

- **Firebase Integration**: Securely store your expense data in Firebase. The app automatically syncs data with Firebase, ensuring that your information is always up-to-date and accessible from any device.

- **Intuitive UI**: Enjoy a clean and user-friendly interface designed with ease of use in mind. The app's layout and navigation make managing your expenses a hassle-free experience.

- **Cross-Platform Support**: Built with Flutter, Expense Tracker runs smoothly on both Android and iOS devices, providing a consistent experience across platforms.

- **Real-Time Updates**: Experience real-time updates and feedback while adding or viewing expenses, thanks to the app's efficient use of Flutter Bloc for state management.

## Technologies Used

Expense Tracker is built using a variety of technologies and packages to provide a robust and efficient application. The following are the key technologies and dependencies used in this project:

### Framework
- **Flutter**: The primary framework used for developing the app, providing a rich set of pre-designed widgets and tools for building natively compiled applications for mobile, web, and desktop from a single codebase.

### State Management
- **Bloc**: A predictable state management library that helps implement the Business Logic Component (BLoC) design pattern.
- **flutter_bloc**: Integrates the Bloc library with Flutter, making it easier to use Bloc for state management.

### UI and Visualization
- **cupertino_icons**: Provides the iOS-style icons.
- **font_awesome_flutter**: Offers a wide range of icons from the Font Awesome library.
- **fl_chart**: A powerful Flutter library for creating beautiful and customizable charts.
- **flutter_colorpicker**: A color picker library for Flutter.
- **intl**: Provides internationalization and localization facilities, including date formatting.

### Data Management
- **firebase_core**: A Flutter plugin for Firebase Core, enabling the app to connect to Firebase services.
- **firebase_auth**: Provides Firebase Authentication services for secure user authentication.
- **cloud_firestore**: A Firestore database plugin for Flutter, used to store and sync expense data in real-time.
- **equatable**: Simplifies equality comparisons in Dart objects.
- **uuid**: Generates unique IDs for various objects in the app.

### Custom Packages
- **expense_repository**: A custom package within the project that handles data management and interactions with Firebase, including authentication and Firestore operations.

### Development Tools
- **flutter_test**: Provides testing utilities for Flutter apps.
- **flutter_lints**: A set of recommended lints for Flutter projects to help maintain a high code quality.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

## Contributors

We welcome contributions to the Expense Tracker app! If you have any ideas, suggestions, or bug fixes, feel free to create a pull request or open an issue.

### Main Contributor

- **[Kwaaku Boamah-Powers]** - *Developer and Maintainer* 
