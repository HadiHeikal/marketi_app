# Marketi App

Welcome to the **Marketi App**, an e-commerce application built using Flutter. This project is in its initial stages of development and will follow the **MVVM (Model-View-ViewModel)** architectural pattern.

## Project Overview
Marketi App aims to provide a seamless shopping experience for users, featuring a modern and scalable architecture. The app will include features such as product browsing, cart management, and secure checkout.

## Current Status
- **Version**: Initial version
- **Development Stage**: Starting development

## Architecture
This project follows the **MVVM (Model-View-ViewModel)** architecture to ensure:
- **Separation of Concerns**: Clear distinction between UI, business logic, and data handling.
- **Scalability**: Easy to extend and maintain as the app grows.
- **Testability**: Simplified unit testing for business logic and UI components.

### Layers
1. **Model**: Represents the data and business logic of the app.
2. **View**: Handles the UI and user interactions.
3. **ViewModel**: Acts as a bridge between the Model and View, managing the app's state and exposing data to the View.

## Getting Started
### Prerequisites
- Flutter SDK installed
- Android Studio or Visual Studio Code
- A connected device or emulator

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/HadiHeikal/marketi_app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd marketi_app
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

## Folder Structure
```
lib/
├── main.dart          # Entry point of the app
├── models/            # Data models
├── views/             # UI components
├── viewmodels/        # State management and business logic
└── services/          # API and data handling
```

## Roadmap
- [ ] Implement basic UI components
- [ ] Set up MVVM architecture
- [ ] Integrate product listing API
- [ ] Add cart functionality
- [ ] Implement user authentication

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.



