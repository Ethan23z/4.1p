Task Management Application

An Android native task management app using Kotlin + Room, which supports task creation, viewing, editing, and deletion. The data persistence uses the Room persistence library.

Function

Task list: Sort by due date and display all tasks.

Create a new task: Enter the title, description, and due date, and save to the local database.

Edit task: Modify the details of an existing task.

Delete task: Delete tasks that are no longer needed individually or in batches.

View details: Click on the list item to view the complete task information.

Technology stack

Language: Kotlin

Database: Room Persistence Library (SQLite)

UI: ConstraintLayout + ViewBinding

Minimum SDK: API 24

Compile SDK: API 34

Kotlin JVM Target: 1.8

2. Open the project directory with Android Studio.

3. Synchronize Gradle.

4. Run to the Pixel 5 simulator or real device (Java 17).

## Build and Run

- **Debug**: `Run > app`

- **Release**: After configuring the signature in `build.gradle`, execute `./gradlew assembleRelease`.

## Notes

- Room will export the schema by default. If not, set `exportSchema = false` in `@Database`.

- Some APIs are marked as `@RequiresApi` (use carefully).

## Contribute

1. Add an issue or submit a PR.

2. Keep the code name clear and the comments complete.
