# Use Gradle for Building and Testing
Gradle can leverage your Build Scan data to:
- speed up build and test feedback cycle times, 
- make troubleshooting more efficient, 
- more easily observe and analyze performance trends and failures like flaky tests.

Initialize Gradle project - adds Gradle's build scripts, wrapper files and generate build.gradle file
### `gradle init --type basic --dsl groovy --project-name grdl`
## Create a build Scan 
### `./gradlew clean build --scan`

