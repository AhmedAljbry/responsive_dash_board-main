# Responsive Flutter Dashboard

A Flutter dashboard interface focused on layouts for desktop and tablet screen sizes. The repository includes reusable UI components and custom font assets.

## Requirements

- Flutter with Dart 3.2.3 or newer.
- The Montserrat font files configured by the project under `assets/fonts/`.

## Run locally

```sh
flutter pub get
flutter run -d chrome
```

Use `flutter devices` to select another supported device. Check the project with:

```sh
flutter analyze
flutter test
```

The current widget test is a generated counter example rather than a dashboard test. Treat it as placeholder coverage and replace it with widget tests for the responsive dashboard before relying on CI test results. Flutter SDK was unavailable in the audit environment, so a build and analyzer run have not been verified here.

## Design reference

The project README originally referenced this community Figma file: [Admin Dashboard design](https://www.figma.com/design/MaVFj6GIkC4oUYj6DYx4E8/Admin-Dashboard--Community-?node-id=0-1&p=f). Confirm that the reference and included implementation still match before presenting it as a current design spec.

## Scope

This repository demonstrates a dashboard UI. It does not document a connected production API, authentication flow, or deployed service. Do not describe those capabilities as implemented without verifying them in the source and a running build.
