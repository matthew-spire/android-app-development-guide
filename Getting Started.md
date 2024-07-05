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
- Based on the requirements, what tools are needed to build the app or feature?
  - Tools here refers to anything needed to build the app or feature, from the IDE to the programming language(s) to dependencies (libraries) for required functionality
- Tools:
  - IDE: Android Studio
  - Programming Language: Java or Kotlin &rarr; **Kotlin**
  - UI: XML or Compose &rarr; **Compose**
  - What does the app contain or what does the app need to be able to do? A lot of functionality requires dependencies or libraries
    - API requests/responses, working with JSON, and logging:
      - Retrofit or Ktor for making API requests/responses &rarr; Retrofit
      - Moshi or Gson for working with JSON &rarr; Moshi
      - OkHttp or Ktor for logging &rarr; OkHttp
    - Asynchronous programming &rarr; Coroutines
    - Business logic &rarr; ViewModel(s)
    - Image loading
      - Coil or Glide &rarr; Coil