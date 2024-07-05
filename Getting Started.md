# Building Android Apps and Features - Getting Started

## Requirements
- Given: Requirements for app functionality, design, etc. from a team or teams within the organization
- Goal: Develop a new app or enhance an existing app to meet the requirements
- Notes:
  - Ask any necessary or qualifying questions surrounding the requirements. For example:
    - Does the app or feature need to support an offline mode?
    - Will the app now or in the future need to implement localization or globalization?
    - Do the designs meet ADA requirements and WCAG standards?
    - Etc.

## Tools

### Tools for Android App Development
- Tools here refers to anything needed to build the app or feature, from the IDE to the programming language(s) to dependencies (libraries) for required functionality
- Based on the requirements, what tools are needed to build the app or feature?
- Commonly used tools for Android app development:
  - IDE: Android Studio
  - Programming Language: Java or Kotlin &rarr; **Kotlin**
  - UI: XML or Compose &rarr; **Compose**
  - What does the app contain or what does the app need to be able to do? A lot of functionality requires dependencies or libraries that need to be added to the project
    - API requests/responses, working with JSON, and logging:
      - Retrofit or Ktor for making API requests/responses &rarr; Retrofit
      - Moshi or Gson for working with JSON &rarr; Moshi
      - OkHttp or Ktor for logging &rarr; OkHttp
    - Asynchronous programming &rarr; Coroutines
    - Business logic &rarr; ViewModel(s)
    - Database:
      - Realm or Room &rarr; Room
    - Dependency injection:
      - Dagger, Dagger-Hilt (aka Hilt), or Koin &rarr; Dagger-Hilt
    - Image loading:
      - Coil or Glide &rarr; Coil
    - Postman for API testing and visualization
    - Etc.

### Gathering the Tools
- Are you building an app from scratch or are you adding a feature to an existing app?
  - Building an app from scratch
    - Make sure you have the core tools installed, i.e., Android Studio, Java and the JVM, etc.
    - After creating a new project in Android Studio, install any dependencies or libraries needed for the app's functionality (more on this later)
  - Adding a feature to an existing app
    - Make sure you have the core tools installed, i.e., Android Studio, Java and the JVM, etc.
    - Use Git to clone the existing project
    - Check existing dependencies or libraries to see if they provide the necessary functionality to build the new feature; if not, then add the required dependencies or libraries
- Adding dependencies or libraries