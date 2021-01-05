# Quick Setup for IntellIJ
1. Fix Kotlin Compiler in IntellIJ
- Open the IntelliJ preferences
- Go to Build, Execution, Deployment > Compiler > Kotlin Compiler BUT Other Settings > Kotlin compiler
- Change the Target JVM version to 11, ref: [StackOverflow](https://stackoverflow.com/questions/48988778/cannot-inline-bytecode-built-with-jvm-target-1-8-into-bytecode-that-is-being-bui)
2. Link Gradle Project to get code insight for Kotlin
- Open build.gradle.kts
- Click on "Link Gradle project" prompt at top right.
- Click load gradle project prompt at bottom right.