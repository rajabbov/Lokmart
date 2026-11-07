# Lokmart

An e-commerce client built the way a production app is wired: Hilt for dependency injection, Retrofit for the API, DataStore for tokens and Navigation for the screen graph.

## Features

- Onboarding carousel with a page indicator
- Sign-in flow backed by a repository and ViewModel
- Hilt modules split by concern (`NetworkModule`, `ApiModule`, `DataModule`, `RepositoryModule`)
- Token and user session persisted with DataStore Preferences
- `SingleLiveEvent` for one-shot UI events
- Retrofit with a Gson converter and an OkHttp logging interceptor

## Tech stack

- **Language:** Kotlin
- **UI:** XML layouts with View binding
- **SDK:** min 24, target 35
- **Package:** `com.example.lokmart`
- **Libraries:** Hilt (dependency injection), Retrofit, OkHttp, Glide, Navigation component, DataStore, Gson, ViewPager indicator

<sub>23 source files · 469 lines of code · 4 layouts</sub>

## Getting started

```bash
git clone https://github.com/rajabbov/Lokmart.git
```

Open the folder in Android Studio, let Gradle sync, and run the `app` configuration on a device or emulator.

### Configuration

Point `NetworkModule` at your own backend URL before running.

## License

MIT
