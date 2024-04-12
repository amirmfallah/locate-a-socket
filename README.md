# Locate a Socket

## Project info

- View [Software Requirement Document](docs/SRS.pdf)
- View [Software Design Document](docs/SDD.pdf)
- This project is a app that shows a map with Electric Charging Stations and their information. The app supports station markers clustering.
- The app runs on Android, iOS and Web.
- The app is built using Flutter 3.3 and Dart.
- The app is built using the MVVM architecture.
- The app is built using the BLoC pattern.

## Demo

## How to run the app

- **Clone the project.**

```shell
git clone https://github.com/extrawest/evc_google_maps_demo.git
```

- **Open the project.**

```shell
cd your_name_here
```

- **Get packages.**

```shell
flutter pub get
```

- **Configure firebase project with flutterfire.**

```shell
flutterfire configure
```

- **Run the app with your api key for the map as additional run argument.**

```
    flutter run --dart-define MAP_API_KEY="{YOUR_API_KEY_HERE}"
```

At this point you should be able to run the app on your device or emulator.

## Firebase hosting

1. In order to deploy this app to Firebase hosting, follow these commands

- **Login to firebase.**

```shell
firebase login
```

- **Initialize firebase.**

```shell
firebase init
```

- **Choose account, then choose Hosting as an option.**
- **Select Firebase project**
- **Select public directory for your hosting**
  build/web (default)
- **Configure as a single-page app**
- **Build the project if you haven't yet**

```shell
flutter build web
```

- **Deploy to firebase.**

```shell
firebase deploy
```
