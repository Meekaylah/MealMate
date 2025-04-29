# MealMate

MealMate is an Android application designed to simplify meal planning, recipe discovery, and grocery shopping. With personalized recipe recommendations, grocery list management, and easy access to saved recipes, MealMate helps users stay organized and inspired in the kitchen.


## Features

### 1. **Personalized Recipe Discovery**
   - Discover recipes tailored to your preferences.
   - Save your favorite recipes for quick access.

### 2. **Grocery List Management**
   - Build weekly grocery lists based on your planned meals.
   - Stay organized while shopping with a clear and concise list.

### 3. **Recipe Storage**
   - Save your favorite recipes and access them anytime.
   - View detailed instructions and ingredient lists for each recipe.

### 4. **Interactive Onboarding**
   - A guided onboarding experience introduces users to the app's features.

### 5. **Dark Mode Support**
   - Enjoy a visually pleasing experience with support for dark mode animations and themes.


## Tech Stack

- **Programming Language**: Java
- **Frameworks & Libraries**:
  - AndroidX (AppCompat, ConstraintLayout, CardView, etc.)
  - Firebase (Authentication, Firestore, Storage)
  - Google Material Design
- **Build System**: Gradle
- **Minimum SDK**: API 21 (Android 5.0)
- **Target SDK**: API 34 (Android 14)


## Project Structure
```
MealMate/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/mealmate/
│   │   │   │   ├── MainActivity.java        # Main entry point of the app
│   │   │   │   ├── Recipe.java              # Recipe model class
│   │   │   ├── res/
│   │   │   │   ├── drawable/                # Vector and image assets
│   │   │   │   ├── values/                  # Strings, styles, and themes
│   │   │   │   ├── animator-night/          # Dark mode animations
│   │   │   │   ├── xml/                     # Backup and data extraction rules
├── gradle/                                  # Gradle configuration files
├── settings.gradle.kts                      # Project settings
└── build.gradle.kts                         # App-level Gradle configuration

```


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/MealMate.git
   cd MealMate


## Key Files

- **[MainActivity.java](app/src/main/java/com/example/mealmate/MainActivity.java)**: The main activity that handles navigation and user interactions.
- **[Recipe.java](app/src/main/java/com/example/mealmate/Recipe.java)**: A model class representing a recipe with title, ingredients, and instructions.
- **[styles.xml](app/src/main/res/values/styles.xml)**: Defines the app's visual styles.
- **[backup_rules.xml](app/src/main/res/xml/backup_rules.xml)**: Configures data backup rules for Android's auto-backup feature.


## Dependencies

The app uses the following libraries and tools:

- **Firebase**: Authentication, Firestore, and Storage.
- **AndroidX**: Core libraries for modern Android development.
- **Material Design**: For UI components and animations.
- **jBCrypt**: For secure password hashing.

For a full list of dependencies, see the [libs.versions.toml](gradle/libs.versions.toml) file.


## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


## Contact

Deeloped by **Michaela** 🍂 at [michaelausangaa@gmail.com].
