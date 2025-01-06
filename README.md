### NOTE: Not the same default branch as the parent repo.<br>
The reason for this is that I want to retain the link to the parent repo while also keeping this somewhat separate. The default branch is based off of the initial branch of the parent repo.

---
# Fork of [Philipp Lackner](https://www.youtube.com/@PhilippLackner)'s CMP-Bookpedia Compose Project. [Video Link]("https://youtu.be/WT9-4DXUqsM?feature=shared")<br>
The aim of this project is to follow through his tutorial. Also; this readme is more for myself to track what I've learned/implemented and what I plan to do with this project.
- Jetpack Compose
- Animations
- Navigation transitions
- Compose Multiplatform
- Room database
- Koin
- Ktor
- Coil

## Platforms tested on:<br>
- Android (API 33)
<br><br>
---
---
###### (From Parent Repo)<br>
This is a Kotlin Multiplatform project targeting Android, iOS, Desktop.

* `/composeApp` is for code that will be shared across your Compose Multiplatform applications.
  It contains several subfolders:
  - `commonMain` is for code that’s common for all targets.
  - Other folders are for Kotlin code that will be compiled for only the platform indicated in the folder name.
    For example, if you want to use Apple’s CoreCrypto for the iOS part of your Kotlin app,
    `iosMain` would be the right folder for such calls.

* `/iosApp` contains iOS applications. Even if you’re sharing your UI with Compose Multiplatform, 
  you need this entry point for your iOS app. This is also where you should add SwiftUI code for your project.


Learn more about [Kotlin Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html)…