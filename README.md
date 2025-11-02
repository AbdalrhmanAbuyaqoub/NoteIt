
# NoteIt
A simple note-taking mobile application built with Flutter.

### Authentication
- **User Registration** - Create a new account with email and password
- **User Login** - Secure login to access your notes
- **Email Verification** - Verify your email address for account security
- **Password Reset** - Reset your password via email
- **Logout** - Securely logout from your account

### Notes Management
- **Create Notes** - Create new notes with ease
- **Update Notes** - Edit and update existing notes in real-time
- **Delete Notes** - Remove notes you no longer need
- **Share Notes** - Share your notes with others using the share functionality
- **Cloud Sync** - All notes are automatically saved and synced to the cloud
- **Real-time Updates** - Changes are reflected immediately across devices

### User Experience
- **Material Design** - Clean and intuitive user interface
- **Responsive UI** - Works seamlessly on different screen sizes

## Tech Stack

### Framework & Language
- **Flutter** - Cross-platform mobile development framework
- **Dart** - Programming language

### Backend & Cloud Services
- **Firebase Authentication** - User authentication and management
- **Cloud Firestore** - NoSQL cloud database for storing notes

### State Management & Architecture
- **BLoC Pattern** - Business Logic Component for state management
- **flutter_bloc** - Flutter widgets for BLoC pattern implementation
- **Equatable** - Simplifies equality comparisons in Dart

### Additional Libraries
- **share_plus** - Cross-platform plugin for sharing content
- **path_provider** - Access to commonly used locations on the filesystem
- **flutter_launcher_icons** - Custom app launcher icons

## Project Structure

```
lib/
├── constants/       # App constants and routes
├── enums/          # Enumerations
├── extensions/     # Dart extensions
├── l10n/           # Localization files
├── services/       # Business logic and services
│   ├── auth/       # Authentication services
│   └── cloud/      # Cloud storage services
├── utilities/      # Utility functions and helpers
└── views/          # UI screens and widgets
```
