# UIRouter for KCM - Maven Repository

This repository serves as a Maven repository for [UIRouter for KCM](https://github.com/istsest/UIRouter-for-KCM), a type-safe routing library for Kotlin Compose Multiplatform.

## Usage

Add this repository to your `settings.gradle.kts`:

```kotlin
dependencyResolutionManagement {
    repositories {
        google()
        mavenCentral()
        maven {
            url = uri("https://istsest.github.io/uirouter-kcm-maven")
        }
    }
}
```

Then add the dependency:

```kotlin
dependencies {
    implementation("io.github.istsest:uirouter-for-kcm:VERSION")
}
```

## Platform Support

- ✅ Android
- ✅ iOS (arm64, x64, Simulator arm64)
- ✅ Kotlin Multiplatform

## License

This repository serves as a distribution mechanism. See the main project for license information.

---

**Note**: This repository is automatically generated. Do not edit manually.
