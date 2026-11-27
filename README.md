# myapp

My first Flutter app: the standard counter starter (Material 3, deep-purple seed colour), kept for learning the basics
of widgets and state. Pressing the **+** button increments a counter with `setState`.

## Run it

Needs the [Flutter SDK](https://docs.flutter.dev/get-started/install) (Dart 3.5 or later).

```bash
flutter pub get
flutter run            # pick a device, or:
flutter run -d chrome  # the web target
flutter test           # the widget test in test/widget_test.dart
```

The project has Android and web targets, and an `.idx/dev.nix` for Project IDX.

## Layout

| Path | What it is |
|------|------------|
| `lib/main.dart` | The whole app: `MyApp`, `MyHomePage` and the counter state |
| `test/widget_test.dart` | Taps the button and checks the counter |
| `android/`, `web/` | Platform folders |
| `.github/workflows/` | GitHub's stock Dart workflow (it runs `dart` rather than `flutter`, so it doesn't build this app as is) |
