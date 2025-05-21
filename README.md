# ChatwootSDK

Android SDK for Chatwoot

## Development Setup

Before building or publishing, please run:

```bash
./gradlew wrapper --gradle-version 8.0
```

This will generate the required Gradle wrapper JAR file in the gradle/wrapper directory.

## Usage in other projects

Add the JitPack repository to your build file:

```kotlin
allprojects {
    repositories {
        ...
        maven(url = "https://jitpack.io")
    }
}
```

Add the dependency:

```kotlin
dependencies {
    implementation("com.github.muhsin-k:chatwoot-sdk:v1.0.4")
}
```