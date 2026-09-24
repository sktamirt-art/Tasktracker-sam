# TaskFlow Android

This is a native Android Java project designed for the requested TaskFlow app.

## Included
- admin / admin login
- dashboard
- Kanban board: NEW, OPEN, IN PROGRESS, BLOCKED, CLOSED
- task list
- search
- status/priority filtering
- sorting
- Low / Medium / High / Critical priority
- Urgent / Important flags
- start/end date and time
- short-term and long-term goals
- task-to-goal linking
- local SQLite storage
- backup/restore through Android document picker
- light/dark theme
- deadline notification scheduling
- no cloud account required

## Build
This environment cannot compile the APK because the Android SDK/build tools are not installed.

On an Android build environment or GitHub Actions:
1. Install Android SDK + JDK 17/21.
2. Use Gradle 8.x.
3. Set compileSdk to an installed SDK (35+ recommended).
4. Run `./gradlew assembleDebug`.
5. The APK will be under `app/build/outputs/apk/debug/`.

For a GitHub Actions build, the workflow template is included in `.github/workflows/build-apk.yml`.

Login: admin / admin
