
## 1. [Env Setup](#env-setup)
## 2. [Vim](#vim)
## 3. [Gradle](#gradle) 
## 4. [Git](#git)
## 5. [Intelij Idea](#intelij-idea)

# Env Setup
------------------------------------------------

# Vim

| Command name | Short cut |
| --------------- | --------------- |
| Search | / |
| Insert new line in edit mode before | O |
| Insert new line in edit mode after | o |
| Cursor to start of document | gg |
| go to line <NUMBER>  | <NUMBER> gg |
| Cursor to the end of document | G |
| Move to bottom visible line (LOW)  | L |

# Gradle

Installation on macOs: 
```
  brew install gradle
```
Configure gradle in new project: 
```
  gradle init
```
After gradle init Gradle structure looks like this:
```
├── build.gradle  <- 1
├── gradle 
│   └── wrapper
│       ├── gradle-wrapper.jar. <- 2
│       └── gradle-wrapper.properties. <- 3 
├── gradlew. <- 4
├── gradlew.bat. <- 5 
└── settings.gradle. <- 6
```

1. Gradle build script for configuring the current project
2. Gradle Wrapper executable JAR
3. Gradle Wrapper configuration properties
4. Gradle Wrapper script for Unix-based systems
5. Gradle Wrapper script for Windows
6. Gradle settings script for configuring the Gradle build

# Git
------------------------------------------------

# Intelij Idea
------------------------------------------------

