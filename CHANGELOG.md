## [0.1.14] - Change route param name

void ANY(String route, Function fn) -> Change to:
void ANY(String url, Function fn)

## [0.1.13] - Change file name

Change: lib/main.dart -> lib/serral.dart

## [0.1.12] - Update Readme

## [0.1.11] - Fix Serral initCtx

## [0.1.10] - Add Chinese README.md

## [0.1.9] - Change description

## [0.1.7] - Add mixin SerralCtx

- Look README.md

## [0.1.6] - Add queryPaser

```dart
Map<String, dynamic> data = ctx.queryPaser('name=dog&age=10');
print(data);
```

## [0.1.5] - Add API: addCorsHeaders

open cros:

```dart
app.before(app.addCorsHeaders);
```

## [0.1.4] - Add api app.sendJson

## [0.1.3] - Fix parse body data

- fix parse body data
- change API: serral.use -> serral.ANY

## [0.1.2] - Update README

## [0.1.1] - Update README

## [0.1.0] - Update Github URL

## [0.0.7] - Use Likt Koa API

## [0.0.5] - Add middleware

## [0.0.1] - TODO: Add release date.

- TODO: Describe initial release.
