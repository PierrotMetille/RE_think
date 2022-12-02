# re_think

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

Problem : 
When execute command :   flutterfire configure --project=fir-setup-3319c or just flutterfure configure :
FirebaseCommandException: An error occured on the Firebase CLI when attempting to run a command.
COMMAND: firebase --version
ERROR: The FlutterFire CLI currently requires the official Firebase CLI to also be installed, see https://firebase.google.com/docs/cli#install_the_firebase_cli for how to install it.

try to make a segond CLI name firebase in the project folder for standalone problem
try to log, unlog
try to intall all depndance with npm install -g firebase-tools
CLI are activated
All the issue i have found are on this website and nothinks is fixing my probelm : https://www.appsloveworld.com/flutter/100/5/firebasecommandexception-an-error-occured-on-the-firebase-cli-when-attempting-to

I can run the project with flutter run, the project exist.
When i Flutter projects:list, the project is here
The project have a config (When make a init agane, say thats there already have one)
the firebase version is 11.16.1
Path to firebase.bat and flutter.bat are setup
