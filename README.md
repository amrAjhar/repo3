# RandomEmojiApp

A Flutter-based mobile application offering random emoji display, task management, and comprehensive user profiles with Firebase integration for secure data storage and authentication.

## Key Features

- Random emoji generator with a large emoji set
- Task management: create and view tasks stored locally
- User authentication: email/password, Google, and GitHub sign-in
- Profile management: view and update personal data in Cloud Firestore
- Navigation drawer for seamless section access
- Local persistence via Shared Preferences

## Technologies

- **Flutter & Dart** (Frontend)
- **Firebase** (Authentication, Cloud Firestore)
- **Google Sign-In** & **Flutter Web Auth 2** (OAuth)
- **Shared Preferences** (Local storage)
- **Calendar Date Picker 2**

## Screens

1. **Login Screen**: Email/password, Google, and GitHub authentication
2. **Register Screen**: New user sign-up and Firestore profile creation
3. **Random Emoji Screen**: Display a random emoji and greeting
4. **Add Task Screen**: Create and save tasks locally
5. **Task List Screen**: View list of saved tasks with summary
6. **Profile Screen**: View and update user data synced with Firestore
7. **Saved Data Screen**: Display locally stored credentials
8. **About Us Screen**: Project overview and team credits

## Data Structure

### Task Example (Local Storage)

```json
[
  "Buy groceries",
  "Read a book",
  "Walk the dog"
]
```

### User Example (Firestore)

```json
{
  "name": "John",
  "surname": "Doe",
  "email": "john.doe@example.com",
  "adress": "123 Main St",
  "living-city": "Anytown",
  "birth-date": "1990-01-01",
  "birth-place": "Country",
  "password": "••••••••"
}
```

## Authentication

- Firebase Authentication for secure login and registration
- Session management handled by Firebase SDK
- OAuth support for Google and GitHub providers

## Configuration

- Multi-platform Firebase setup (Android, iOS, Web)
- Add `google-services.json` (Android) and `GoogleService-Info.plist` (iOS)
- Update `FirebaseOptions` in `main.dart` for web
- `.gitignore` configured to exclude build artifacts and IDE files

## Team Contributions

### Enes Elhovete (030722060)

- Core app architecture, random emoji feature, and theming
- Navigation drawer and shared preferences integration

### Amr Acar (030722108)

- Task management screens and local storage
- UI design and responsive layouts

### Mohamad Alhamoud (030721079)

- Authentication flows and Firestore integration
- Profile screen implementation and data synchronization

## Architecture

- MVVM-inspired modular structure
- Separation of services: AuthService, FirestoreService
- State management with Provider and Shared Preferences
- Reusable widgets and theming via Material Design

## Development

Built with:

- Flutter SDK (3.7.0)
- Dart
- Firebase CLI & Tools
- Android Studio / VS Code

## Project Link

[https://github.com/amrAjhar/repo3](https://github.com/amrAjhar/repo3)

