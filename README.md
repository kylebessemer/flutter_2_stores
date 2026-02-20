# Flutter 2 Stores

A Flutter demo project showcasing how to use multiple Provider stores (ChangeNotifiers) in a single application, along with an infinite scrolling list example.

## Features

- **Multiple Provider Stores** -- Uses `MultiProvider` with two independent `ChangeNotifier` stores (`AppData1` and `AppData2`), each managing its own counter state.
- **Infinite Scrolling List** -- Demonstrates a `ListView.builder` that dynamically loads more items as the user scrolls to the bottom.

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (>=3.2.4)
- Dart SDK (>=3.2.4)

### Installation

```bash
git clone https://github.com/kylebessemer/flutter_2_stores.git
cd flutter_2_stores
flutter pub get
```

### Run

```bash
flutter run
```

## Project Structure

```
lib/
  main.dart             # App entry point, MultiProvider setup, ChangeNotifier stores
  counter.dart          # CounterPage UI with two independent counters
  infinite_loading.dart # Infinite scrolling list demo
```

## Dependencies

- [provider](https://pub.dev/packages/provider) -- State management

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
