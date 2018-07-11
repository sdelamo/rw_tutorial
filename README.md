Gradle project which given two folders `starter` and `finished` with two Android Studio applications within them, generates two zip files
as described in the Raywenderlich.com Android Team Guide [Finalizing Projects](https://www.raywenderlich.com/tutorial-team/android-team-guide).


If you run `./gradlew zip` it generates two zip files which do not include `.iml` files, `local.properties` file, and `.idea`, `.git`, `.gradle` or `build` directories.
