# Android dependencies and repositories

## Links to the repositories and some interesting stuff
🏞️ [Image loader](https://coil-kt.github.io/coil/compose/) <br>
🛜 [HTTP Requests](https://ktor.io/) <br>
🪙 [Koin](https://insert-koin.io/) <br>
🧙 [KMP Wizard](https://kmp.jetbrains.com/) <br>
🗡️ [Dagger - Hilt](https://dagger.dev/hilt/)
## Some dependencies that I use
### Kapt
``` kotlin
kotlin(kapt)
```
### Navigation
``` kotlin
implementation("androidx.navigation:navigation-compose:2.6.0")
```
### ViewModel
``` kotlin
implementation("androidx.lifecycle:lifecycle-viewmodel-compose:2.6.1")
```
### Room database
``` kotlin
// project
id("com.google.devtools.ksp") version "1.8.10-1.0.9" apply false

// app
implementation "androidx.room:room-runtime:2.5.2"
kapt "androidx.room:room-compiler:2.5.2"
implementation "androidx.room:room-ktx:2.5.2"
```
### DaggerHilt
``` kotlin
// project
id ("com.google.dagger.hilt.android") version '2.44' apply false

// app
implementation("com.google.dagger:hilt-android:2.45")
kapt("com.google.dagger:hilt-compiler:2.45")
implementation("androidx.hilt:hilt-navigation-compose:1.0.0")
```
### Splash API
``` kotlin
implementation("androidx.core:core-splashscreen:1.0.1")
```
### Retrofit
``` kotlin
implementation("com.squareup.retrofit2:retrofit:2.9.0")
implementation("com.squareup.retrofit2:converter-gson:2.9.0")
```

### Coil
``` kotlin
implementation("io.coil-kt:coil-compose:2.4.0")
```

### Paging 3
``` kotlin
implementation("androidx.paging:paging-runtime:3.1.1")
implementation("androidx.paging:paging-compose:3.2.0-rc01")
```


