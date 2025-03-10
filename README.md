# Dart Rational

[![Build Status](https://github.com/a14n/dart-rational/actions/workflows/dart.yml/badge.svg)](https://github.com/a14n/dart-rational/actions/workflows/dart.yml)

This project enable to make computations on rational numbers.

## Usage
To use this library in your code :
* add a dependency in your `pubspec.yaml` :

```yaml
dependencies:
  rational:
```

### Rational numbers

* add import in your `dart` code :

```dart
import 'package:rational/rational.dart';
```

* Start computing using `Rational.parse('1.23')`,
`Rational(BigInt.from(12), BigInt.from(7))` or `Rational.fromInt(12, 7)`.

## Example

```dart
import 'package:rational/rational.dart';

void main() {
  var r = Rational.parse('0.1') + Rational.fromInt(1, 4) ;
  print(r); // 0.35
}
```

## License
Apache 2.0
