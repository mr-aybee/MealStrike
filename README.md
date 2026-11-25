# MealStrike

A Xamarin.Forms mobile meal-ordering application with a shared .NET Standard 2.0 project and an Android host.

## Application areas

- Meal browsing and product details
- Cart and checkout screens
- Order history and details

## Architecture

| Component | Responsibility |
| --- | --- |
| `MealApp/MealApp/` | Shared application, views, controls and data access |
| `MealApp/MealApp.Android/` | Android host |

## Build from source

Open `MealApp.sln` in a Xamarin-compatible Visual Studio environment with Android tooling. Restore packages and review backend configuration before running.

## Status

Legacy Xamarin implementation. Build compatibility and backend availability are unverified. Use test data only; checkout UI does not establish live payment support.
