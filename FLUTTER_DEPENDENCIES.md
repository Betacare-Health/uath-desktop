# Flutter dependencies (uath-desktop)

NFC desktop bridge - USB reader companion for staff EMR.

**Dart SDK constraint:** `^3.12.2` (resolved lock: `>=3.12.2 <4.0.0`)
**Flutter SDK (lock):** `>=3.32.3`

Docker builds use `ghcr.io/cirruslabs/flutter:stable`.

## Direct dependencies

Packages declared in `pubspec.yaml` `dependencies`.

| Package | Version | Purpose |
| --- | --- | --- |
| `flutter` | >=3.32.3 | Flutter SDK - UI framework and runtime |
| `cupertino_icons` | 1.0.9 | iOS-style icon font |
| `shelf` | 1.4.2 | HTTP server for the desktop bridge local API |
| `shelf_web_socket` | 3.0.0 | WebSocket support on Shelf server |
| `web_socket_channel` | 3.0.3 | WebSocket client/server channel abstraction |
| `flutter_pcsc` | 0.0.4 | USB PC/SC smart card reader access |
| `ndef` | 0.4.0 | Parse and encode NFC NDEF payloads from patient cards |
| `shadcn_flutter` | 0.0.53 | Local UI component library |

## Dependency overrides

Local or pinned replacements.

| Package | Version | Purpose |
| --- | --- | --- |
| `flutter_pcsc_macos` | 0.0.3 | macOS PC/SC plugin (local override) |
| `flutter_pcsc_windows` | 0.0.3 | Windows PC/SC plugin (local override) |

## Dev dependencies

Build, lint, and test tooling only (not shipped in release builds).

| Package | Version | Purpose |
| --- | --- | --- |
| `flutter_test` | 0.0.0 | Flutter SDK test framework (dev only) |
| `flutter_lints` | 6.0.0 | Recommended lint rules for Dart/Flutter (dev only) |

## Indirect dependencies

Transitive packages from `pubspec.lock`.

| Package | Version | Purpose |
| --- | --- | --- |
| `animation_kit` | 0.0.2 | Animation helpers (transitive via shadcn_flutter) |
| `args` | 2.7.0 | Command-line argument parsing for build tools |
| `async` | 2.13.1 | Async utilities (Future/Stream helpers) |
| `boolean_selector` | 2.1.2 | Boolean expression parsing for tests |
| `characters` | 1.4.1 | Unicode grapheme cluster string operations |
| `clock` | 1.1.2 | Injectable clock abstraction for tests |
| `collection` | 1.19.1 | Extra collection types and utilities |
| `convert` | 3.1.2 | Encoders/decoders (base64, hex, etc.) |
| `country_flags` | 4.1.2 | Country flag widgets (transitive via shadcn_flutter) |
| `cross_file` | 0.3.5+4 | Cross-platform file representation for file_picker |
| `crypto` | 3.0.7 | Cryptographic hashing (transitive via secure storage) |
| `data_widget` | 0.0.3 | Data-driven widget helpers (transitive via shadcn_flutter) |
| `email_validator` | 3.0.0 | Email validation (transitive via shadcn_flutter) |
| `expressions` | 0.2.5+3 | Expression parsing (transitive via shadcn_flutter) |
| `fake_async` | 1.3.3 | Fake async clock for tests |
| `ffi` | 1.2.1 | Foreign function interface for native plugins |
| `fixnum` | 1.1.1 | Fixed-width integers for serialization |
| `flutter_localizations` | 0.0.0 | Flutter localization delegates (transitive) |
| `flutter_pcsc_linux` | 0.0.3 | Linux PC/SC plugin (transitive) |
| `flutter_pcsc_platform_interface` | 0.0.2 | Shared PC/SC plugin interface |
| `gap` | 3.0.1 | Fixed spacing widgets (transitive via shadcn_flutter) |
| `http` | 1.6.0 | Low-level HTTP client (transitive via dio/shelf) |
| `http_parser` | 4.1.2 | HTTP header and body parsing |
| `intl` | 0.20.2 | Date, number, and message formatting |
| `jovial_misc` | 0.10.0 | Misc utilities for jovial_svg |
| `jovial_svg` | 1.1.30 | SVG rendering support library |
| `leak_tracker` | 11.0.2 | Memory leak detection for Flutter tests |
| `leak_tracker_flutter_testing` | 3.0.10 | Flutter test integration for leak tracker |
| `leak_tracker_testing` | 3.0.2 | Leak tracker test utilities |
| `lints` | 6.1.0 | Core lint rule definitions (transitive via flutter_lints) |
| `matcher` | 0.12.19 | Test assertion matchers |
| `material_color_utilities` | 0.13.0 | Material 3 color algorithms |
| `meta` | 1.18.0 | Annotations (@immutable, @required, etc.) |
| `path` | 1.9.1 | Path manipulation utilities |
| `petitparser` | 7.0.2 | Parser combinator library (XML/SVG parsing) |
| `phonecodes` | 0.0.4 | Phone country codes (transitive via shadcn_flutter) |
| `plugin_platform_interface` | 2.1.8 | Base class for federated plugins |
| `quiver` | 3.2.2 | Utility collections (transitive via shelf_web_socket) |
| `rxdart` | 0.28.0 | Reactive extensions for Dart streams |
| `skeletonizer` | 2.1.3 | Loading skeleton placeholders (transitive via shadcn_flutter) |
| `sky_engine` | 0.0.0 | Flutter/Dart sky engine bindings |
| `source_span` | 1.10.2 | Source location tracking for parsers |
| `stack_trace` | 1.12.1 | Stack trace formatting |
| `stream_channel` | 2.1.4 | Stream wrappers for tests and WebSockets |
| `string_scanner` | 1.4.1 | String scanning for parsers |
| `term_glyph` | 1.2.2 | Terminal glyph helpers for tests |
| `test_api` | 0.7.11 | Core test API definitions |
| `typed_data` | 1.4.0 | Typed byte buffer views |
| `uuid` | 4.6.0 | UUID generation (transitive) |
| `vector_math` | 2.2.0 | 2D/3D math for charts and graphics |
| `vm_service` | 15.2.0 | Dart VM service protocol client |
| `web` | 1.1.1 | Web platform interop (dart:html successor) |
| `web_socket` | 1.0.1 | WebSocket API for web platform |
| `xml` | 7.0.1 | XML parsing and generation |

Source of truth: [`pubspec.yaml`](pubspec.yaml) and [`pubspec.lock`](pubspec.lock). Regenerate this list after major dependency upgrades.
