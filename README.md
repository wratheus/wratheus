# Aleksandr Pavlenko

Flutter Developer.

## Open-source contributions

### Flutter SDK

- **AGP Built-in Kotlin compatibility**
  - Reported [flutter/flutter#192167](https://github.com/flutter/flutter/issues/192167), where Flutter's Gradle plugin rejected projects using AGP Built-in Kotlin by enforcing an independently configurable Kotlin Gradle Plugin version.
  - Submitted [flutter/flutter#192206](https://github.com/flutter/flutter/pull/192206), which skips KGP minimum-version validation when Kotlin is provided by AGP.
  - Maintainer-approved; awaiting CI and merge.

- **Android Impeller rendering**
  - Reported [flutter/flutter#162521](https://github.com/flutter/flutter/issues/162521): rendering glitches involving scroll views, navigation, and modal sheets on Android Impeller.
  - Provided a minimal reproduction, videos, timeline traces, and device data. The issue was closed as fixed in a later Flutter release.

### Flutter ecosystem

- **Yandex MapKit Android build regression**
  - Helped diagnose missing Maven artifacts with the `-flutter` suffix after MapKit 4.30 in [yandex/yandex_maps_mapkit#41](https://github.com/yandex/yandex_maps_mapkit/issues/41) and [#40](https://github.com/yandex/yandex_maps_mapkit/issues/40).
  - The maintainers fixed the issue in MapKit SDK 4.38.1.

## Projects

- [tracksu](https://github.com/wratheus/tracksu) — Flutter app for visualizing osu! API data, built for the osu! community.
- [flutter_simple_ble](https://github.com/wratheus/flutter_simple_ble) — Flutter BLE plugin for Android and iOS. Feedback and contributions are welcome.
- [flutter_tetris](https://github.com/wratheus/flutter_tetris) — Flutter implementation of classic Tetris with keyboard and sensor controls.
- [flutter_minesweeper](https://github.com/wratheus/flutter_minesweeper) — Flutter implementation of classic Minesweeper.
- [dart_rest_client_example](https://github.com/wratheus/dart_rest_client_example) — A practical Dart REST client guide with a working example.
