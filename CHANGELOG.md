## 1.1.0

- Removed hard coded `shared_preferences` version.
- Hide public constructors for `ThemePreferences`.
- `AdaptiveTheme.of()` now returns instance of `AdaptiveThemeManager` instead of `AdaptiveThemeState` to set restrictions for accessing state directly.

## 1.0.0

- add option to get previous theme mode on app startup

## 0.1.1

- add option to silently update theme without notifying. Useful when chaining multiple changes.

## 0.1.0

- Supports theme modes: light, dart, system default.
- Persists theme modes across app restarts.
- Allows to toggle theme mode between light and dark.
- Allows to set default theme.
- Allows to reset to default theme.
