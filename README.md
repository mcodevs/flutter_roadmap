# Flutter Roadmap

<a href="https://github.com/Solido/awesome-flutter">
   <img alt="Awesome Flutter" src="https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square" />
</a>

A curated, highly-subjective roadmap and resource list for learning Flutter and Dart.

- **Visual roadmap**: ![Flutter Roadmap](images/FlutterRoadmap.png)
- **Text version**: [`FlutterRoadmap.md`](FlutterRoadmap.md)
- **Other formats**: [`images/FlutterRoadmap.svg`](images/FlutterRoadmap.svg)

## Contents

- [Dev environment](#dev-environment)
- [Language (Dart)](#language-dart)
- [Basic widgets & UI](#basic-widgets--ui)
- [Design patterns](#design-patterns)
- [Design principles](#design-principles)
- [State management & DI](#state-management--di)
- [Networking](#networking)
- [Persistence](#persistence)
- [Databases & cloud data](#databases--cloud-data)
- [Architecture](#architecture)
- [Testing](#testing)
- [Other languages / mobile foundations](#other-languages--mobile-foundations)
- [Dart tooling & advanced topics](#dart-tooling--advanced-topics)
- [Package managers](#package-managers)
- [Profiling](#profiling)
- [Flutter internals](#flutter-internals)
- [Security](#security)
- [Continuous integration](#continuous-integration)
- [Analytics](#analytics)
- [Store / publishing](#store--publishing)
- [Contribution](#contribution)
- [License](#license)

## Dev environment

- [Android Studio keyboard shortcuts](https://developer.android.com/studio/intro/keyboard-shortcuts) — Speed up development in Android Studio.
- VS Code keyboard shortcuts — [Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf), [macOS](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf).
- [Flutter CLI](https://docs.flutter.dev/reference/flutter-cli) — Reference for `flutter` commands.
- [Dart CLI](https://dart.dev/tools/dart-tool) — Reference for `dart` commands (including `dart fix`).
- [DartPad](https://dartpad.dev/) — Online editor/sandbox for Dart & Flutter.
- [DartPad documentation](https://dart.dev/tools/dartpad) — Official docs for DartPad on `dart.dev`.
- [Zapp!](https://zapp.run) — Online sandbox for Dart & Flutter with pub.dev package support.
- [Learn Git Branching](https://learngitbranching.js.org) — Interactive Git tutorial.

## Language (Dart)

- [Dart language tour](https://dart.dev/guides/language/language-tour) — A brief tour of the Dart language.
- [Effective Dart](https://dart.dev/guides/language/effective-dart) — Guidelines for writing better Dart code.
- [Analysis options](https://dart.dev/guides/language/analysis-options) — How to configure static analysis.
- [Sound problems](https://dart.dev/guides/language/sound-problems) — How to fix common sound null safety issues.
- [Dart linter rules](https://dart.dev/tools/linter-rules) — All available Dart lints.
- [Dart Code Metrics (DCM)](https://dcm.dev/) — Additional lint rules, metrics, and code quality tooling.

## Basic widgets & UI

- [Widget of the Week](https://youtube.com/playlist?list=PLjxrf2q8roU23XGwz3Km7sQZFTdB996iG) — Short videos introducing core widgets.
- [Package of the Week](https://youtube.com/playlist?list=PLjxrf2q8roU1quF6ny8oFHJ2gBdrYN_AK) — Useful packages from pub.dev and how to use them.
- [All Flutter Widgets](https://youtube.com/playlist?list=PL82uaKJraAILRBFE1XhCyfvu-Fclc6vv1&si=m5CL8oFoPPu7_LED) — Playlist by **Flutter Mapp** covering (almost) every widget.
- [Introduction to widgets](https://flutter.dev/docs/development/ui/widgets-intro) — Official guide to Flutter widgets.
- [Material Design](https://material.io) — Material system and guidelines.
- [Apple design resources](https://developer.apple.com/design/) — Apple UI design guidance and resources.

## Design patterns

- [Design Patterns (Wikipedia)](https://en.wikipedia.org/wiki/Design_Patterns) — Overview and terminology.
- [“Gang of Four” book](https://en.wikipedia.org/wiki/Design_Patterns) — Classic patterns reference.
- [Flutter Design Patterns](https://flutterdesignpatterns.com) — Patterns applied to Flutter.
- [Refactoring Guru](https://refactoring.guru/design-patterns) — Great pattern explanations and examples.

## Design principles

- [KISS](https://en.wikipedia.org/wiki/KISS_principle) — Keep it simple.
- [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) — Don’t repeat yourself.
- [SOLID](https://en.wikipedia.org/wiki/SOLID) — Principles for maintainable OOP design.
- [Clean Coders](https://cleancoders.com) — Practical software craftsmanship lessons.

## State management & DI

- [provider](https://pub.dev/packages/provider) — Simple state management built on top of InheritedWidget.
- [get_it](https://pub.dev/packages/get_it) — Service locator for dependency injection.
- [injectable](https://pub.dev/packages/injectable) — Code generation for DI (works well with get_it).

## Networking

- [REST (Wikipedia)](https://en.wikipedia.org/wiki/Representational_state_transfer) — API fundamentals.
- [retrofit](https://pub.dev/packages/retrofit) — Retrofit-style HTTP client generator for Dart.
- [json_serializable](https://pub.dev/packages/json_serializable) — JSON model code generation.

## Persistence

- [shared_preferences](https://pub.dev/packages/shared_preferences) — Lightweight key/value storage.
- [flutter_secure_storage](https://pub.dev/packages/flutter_secure_storage) — Encrypted storage for secrets.

## Databases & cloud data

- [isar](https://pub.dev/packages/isar) — Fast local database for Flutter.
- [sqflite](https://pub.dev/packages/sqflite) — SQLite plugin for Flutter.
- [firebase_storage](https://pub.dev/packages/firebase_storage) — Upload/download files to Firebase Storage.
- [cloud_firestore](https://pub.dev/packages/cloud_firestore) — Cloud Firestore database client.
- [icloud_storage](https://pub.dev/packages/icloud_storage) — iCloud storage integration.

## Architecture

- [Flutter Samples](https://fluttersamples.com) — Collection of real-world Flutter examples.
- [async_redux](https://pub.dev/packages/async_redux) — Redux-style state management.
- [flutter_mobx](https://pub.dev/packages/flutter_mobx) — MobX bindings for Flutter.
- [flutter_bloc](https://pub.dev/packages/flutter_bloc) — BLoC implementation and tooling.

## Testing

- [Test-driven development (TDD)](https://en.wikipedia.org/wiki/Test-driven_development) — Basics and motivation.
- [Behavior-driven development (BDD)](https://en.wikipedia.org/wiki/Behavior-driven_development) — Behavior-focused testing style.
- [Test-Driven Development: By Example (Kent Beck)](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530) — Classic TDD book.

## Other languages / mobile foundations

- [Developing Android Apps with Kotlin (Udacity)](https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012) — Solid Android fundamentals.
- [CS193p (Stanford)](https://cs193p.sites.stanford.edu) — iOS development course (SwiftUI-era).

## Dart tooling & advanced topics

- [freezed](https://pub.dev/packages/freezed) — Immutable models + unions/sealed classes via codegen.
- [F# for Fun and Profit](https://fsharpforfunandprofit.com) — Great FP concepts that translate well to Dart.

## Package managers

- [Developing packages & plugins](https://flutter.dev/docs/development/packages-and-plugins/developing-packages) — Official guide to building Flutter packages.
- [CocoaPods](https://cocoapods.org) — Dependency manager for Swift/Obj‑C projects.
- [Gradle](https://docs.gradle.org/current/userguide/userguide.html) — Build automation and dependency management for Android.

## Profiling

- [Flutter UI performance](https://flutter.dev/docs/perf/rendering/ui-performance) — Official performance guidance.
- [Flutter performance video](https://youtu.be/vVg9It7cOfY) — Practical tips and pitfalls.

## Flutter internals

- [Flutter internals talk](https://youtu.be/UUfXWzp0-DU) — Under the hood overview.
- [Dart VM internals talk](https://youtu.be/dkyY9WCGMi0) — Runtime/VM fundamentals.
- [CMU lecture: Flutter](http://www.cs.cmu.edu/~bam/uicourse/830spring20/05-830-2020-03-23-Lecture-10-Flutter.mp4) — Academic-level deep dive.
- [Dart VM](https://mrale.ph/dartvm/) — Excellent write-up on the Dart VM.
- [Flutter under the hood](https://surf.dev/flutter-under-the-hood/) — Engine/framework overview.
- [Architectural overview](https://docs.flutter.dev/resources/architectural-overview) — Official architecture docs.
- [Flutter architecture guide](https://surf.dev/flutter-architecture-guide/) — Practical architecture notes.

## Security

- [OWASP MASVS](https://owasp.org/www-project-mobile-app-security/) — Mobile Application Security Verification Standard.
- [freerasp](https://pub.dev/packages/freerasp) — Mobile RASP for Flutter apps.

## Continuous integration

- [fastlane](https://fastlane.tools) — Automate releases and common mobile workflows.
- [Danger](https://danger.systems) — Automate code review chores in CI.
- [SonarQube](https://www.sonarqube.org) — Code quality and security analysis.
- [Codemagic](https://codemagic.io/) — Flutter-focused CI/CD.
- [Travis CI](https://travis-ci.org) — Hosted CI service.

## Analytics

- [Firebase Analytics](https://firebase.google.com/docs/analytics) — Analytics for mobile apps.
- [App Center Analytics](https://docs.microsoft.com/en-us/appcenter/analytics/) — Analytics via Microsoft App Center.
- [Mixpanel (Flutter)](https://developer.mixpanel.com/docs/flutter) — Product analytics SDK for Flutter.
- [Smartlook (Flutter)](https://docs.smartlook.com/docs/sdk/flutter) — Session recording/UX analytics for Flutter.
- [datadog_flutter_plugin](https://pub.dev/packages/datadog_flutter_plugin) — Datadog logs/traces/rum for Flutter.

## Store / publishing

- [App Store review guidelines](https://developer.apple.com/app-store/review/guidelines/) — Apple submission requirements.
- [Google Play developer policy](https://play.google.com/about/developer-content-policy/) — Play Store rules and policies.
- [Android launch checklist](https://developer.android.com/distribute/best-practices/launch/launch-checklist) — Pre-release checklist.

## Contribution

PRs and suggestions are welcome!

- **Add a link**: keep it in the most relevant section and include a short, one-line description.
- **Update the roadmap**: consider updating both the image (`images/`) and the text version (`FlutterRoadmap.md`).

## License

MIT — see [`LICENSE`](LICENSE).
