# vama-mobile

## Run the application

### Dependencies
Install [nix](https://nixos.org/download/) package manager and enable [flakes](https://wiki.nixos.org/wiki/Flakes)

### Run the environment
```sh
nix develop
```
This command will:
- Install all dependencies required for the Flutter development for Android
- Setup the environment shell, with required environment variables
- Run the Android Emulator

### Run the application
```sh
flutter run
```

### Build the application
```sh
flutter build apk
```