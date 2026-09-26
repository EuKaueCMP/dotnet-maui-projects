# dotnet-maui-projects

Collection of cross-platform mobile applications developed in C# with .NET MAUI and XAML.

## Description

dotnet-maui-projects contains mobile application projects exploring cross-platform client development with .NET MAUI (.NET Multi-platform App UI). The repository focuses on mobile UI layout composition with XAML, multi-page screen navigation, splash screens, styling dictionaries, and platform bootstrapping for Android, iOS, Windows, and macOS.

## Technologies

- **Language:** C#
- **Framework:** .NET MAUI (.NET 8 / modern .NET)
- **Markup:** XAML (Extensible Application Markup Language)
- **Target Platforms:** Android, iOS, Windows, macOS (MacCatalyst), Tizen
- **IDE:** Visual Studio 2022 with .NET MAUI workload

## Project Structure

```text
dotnet-maui-projects/
├── LoginCadastroMobile/
│   ├── LoginCadastroMobile.sln
│   └── LoginCadastroMobile/
│       ├── MauiProgram.cs              # MAUI builder and DI configuration
│       ├── App.xaml / App.xaml.cs      # Application lifecycle and root window
│       ├── Splash.xaml                 # Mobile splash screen
│       ├── MainPage.xaml               # Login page layout and authentication triggers
│       ├── Cadastro.xaml               # User registration form
│       ├── Platforms/                  # Platform-specific native entry points (Android, iOS, etc.)
│       └── Resources/Styles/           # XAML resource dictionaries (Colors.xaml, Styles.xaml)
└── MobileApp1/                         # Starter mobile exploration and layout testing
```

## Features

- **Cross-Platform Architecture:** Single codebase targeting multiple operating systems through the unified .NET MAUI platform model.
- **XAML UI Design:** Declarative layout definition utilizing `StackLayout`, `Grid`, `Entry`, `Button`, and custom styles.
- **Mobile Navigation Flow:** Screen transitions between initial splash screen (`Splash.xaml`), authentication login (`MainPage.xaml`), and account registration (`Cadastro.xaml`).
- **Resource Theming:** Centralized styling defined in `Colors.xaml` and `Styles.xaml` for consistent mobile visual appearance.

## Setup & Execution

### Prerequisites
- [Visual Studio 2022](https://visualstudio.microsoft.com/) (version 17.8 or higher) with **.NET Multi-platform App UI development** workload
- Android SDK and emulator (or physical Android/iOS device)

### Running an Application
1. Clone the repository:
```bash
git clone https://github.com/EuKaueCMP/dotnet-maui-projects.git
```

2. Open `LoginCadastroMobile/LoginCadastroMobile.sln` in Visual Studio, select the target emulator/device, and press `F5` to build and deploy.

## Developer

**Kauê Sérgio Campos**  
GitHub: [@EuKaueCMP](https://github.com/EuKaueCMP)
