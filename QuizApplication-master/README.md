# Quiz Application

**Created by: Kashish Pandey**

A comprehensive Android quiz application featuring multiple science categories with interactive questions and real-time scoring. Built as part of the Udacity-Google Android Basics Nanodegree program.

## Features

- **Multi-Category Quizzes**: Physics, Chemistry, and Biology with 10 questions each
- **Diverse Question Types**: Multiple choice, checkbox (multiple answers), and text input questions
- **Interactive UI**: Material Design with CardView navigation and floating action buttons
- **Real-time Scoring**: Automatic score calculation with performance feedback
- **Social Sharing**: Share your quiz results with friends
- **Smooth Animations**: FAB menu with rotation animations
- **User-friendly Interface**: Clean, intuitive design with colorful category cards

## Technical Specifications

- **Platform**: Android (API 15+)
- **Language**: Java
- **Build System**: Gradle
- **Target SDK**: Android 27
- **Architecture**: Activity-based navigation
- **UI Framework**: Android Support Library with Material Design components

## Dependencies

- Android Support Library v27.1.1
- ConstraintLayout 1.1.2
- CardView Support Library
- Material Design Components
- JUnit for testing

## Project Structure

```
app/src/main/
├── java/com/example/android/quizapplication/
│   ├── MainActivity.java          # Main entry point
│   ├── PlayActivity.java          # Category selection
│   ├── PhysicsActivity.java       # Physics quiz
│   ├── ChemistryActivity.java     # Chemistry quiz
│   ├── BiologyActivity.java       # Biology quiz
│   └── HowTo.java                 # Instructions
├── res/
│   ├── layout/                    # UI layouts
│   ├── drawable/                  # Images and icons
│   ├── anim/                      # Animation files
│   └── values/                    # Strings, colors, styles
└── AndroidManifest.xml
```

## How to Use

1. **Launch the App**: Start from the main menu
2. **Select "Play"**: Choose your quiz category
3. **Pick a Subject**: Physics, Chemistry, or Biology
4. **Answer Questions**: Mix of multiple choice, checkboxes, and text input
5. **Submit & Score**: Use the floating action button to submit
6. **Share Results**: Share your performance with friends

## Quiz Categories

### Physics (10 Questions)
- Covers fundamental physics concepts
- Topics include optics, mechanics, and modern physics
- Mix of theoretical and practical questions

### Chemistry (10 Questions)
- Chemical processes and reactions
- Periodic table and molecular concepts
- Laboratory and industrial applications

### Biology (10 Questions)
- Life sciences and biological processes
- Anatomy, physiology, and ecology
- Cellular and molecular biology

## Scoring System

- **Excellent Performance**: "Well done! You are awesome!"
- **Good Performance**: "You can do better! Try again?"
- **Needs Improvement**: "Brush up your knowledge, maybe?"

## Installation

1. Clone the repository
2. Open in Android Studio
3. Sync Gradle files
4. Run on device or emulator (API 15+)

```bash
git clone <repository-url>
cd QuizApplication-master
```

## Building the App

```bash
./gradlew assembleDebug
```

## Testing

```bash
./gradlew test
./gradlew connectedAndroidTest
```

Some of the app screenshots:

![Alt text](https://i.imgur.com/MU7Rzjnl.png)        ![Alt text](https://i.imgur.com/3mnR0Rjl.png)
![Alt text](https://i.imgur.com/2wBbiTHl.png)
![Alt text](https://i.imgur.com/UnQNxvGl.png)
![Alt text](https://i.imgur.com/eckFUtxl.png)
![Alt text](https://i.imgur.com/ybJiUXil.png)

## Contributing

This project was created as part of the Udacity Android Basics Nanodegree. Feel free to fork and enhance the application with additional features or quiz categories.

## License

This project is part of the Udacity-Google Android Basics Nanodegree program.
