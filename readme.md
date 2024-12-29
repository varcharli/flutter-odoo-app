# Flutter Odoo App

This project is a Flutter application that connects to an Odoo server. It allows users to interact with the Odoo ERP system through a mobile interface.

## Features

- User authentication
- View and manage Odoo records
- Real-time data synchronization
- Push notifications

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Odoo server: [Install Odoo](https://www.odoo.com/documentation/14.0/setup/install.html)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/flutter-odoo-app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd flutter-odoo-app
    ```
3. Install dependencies:
    ```sh
    flutter pub get
    ```

### Running the App

1. Connect your device or start an emulator.
2. Run the app:
    ```sh
    flutter run
    ```

## Configuration

Update the Odoo server configuration in the `lib/config.dart` file:
```dart
// ...existing code...
const String odooServerUrl = 'https://your-odoo-server.com';
// ...existing code...
```

## Screenshots

Here are some screenshots of the app:

![Screenshot 1](./screen/screenshot1.png)
![Screenshot 2](./screen/screenshot2.png)
![Screenshot 3](./screen/screenshot3.png)
![Screenshot 4](./screen/screenshot4.png)
![Screenshot 5](./screen/screenshot5.png)
![Screenshot 6](./screen/screenshot6.png)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
