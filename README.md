# Android dependencies and repositories

### Links to the repositories
🏞️ [Image loader](https://coil-kt.github.io/coil/compose/)


### Some dependencies that I use
#### Navigation
``` kotlin
implementation("androidx.navigation:navigation-compose:2.6.0")
implementation("androidx.lifecycle:lifecycle-viewmodel-compose:2.6.1")
```
#### Room database
``` kotlin
implementation("androidx.room:room-runtime:2.6.1")
implementation("androidx.room:room-ktx:2.6.1")
annotationProcessor("androidx.room:room-compiler:2.6.1")
```
You need to add these dependencies into project gradle file
``` kotlin
id("com.google.devtools.ksp") version "1.8.10-1.0.9" apply false
```
and these to module gradle file
``` kotlin
id("com.google.devtools.ksp")
```
