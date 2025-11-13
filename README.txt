Knight Event Alarm - Android project skeleton
--------------------------------------------
What's included:
- Minimal Android Studio project files (app module).
- Kotlin code implementing:
  * Event Room database
  * Add event screen (hour/minute)
  * Alarm scheduling for daily repeating events
  * Silent notifications (no sound)
  * Prepopulate function with your provided times (call Prepopulate.addDefaults(context) from MainActivity)

How to build:
1. Open Android Studio (Arctic Fox or newer).
2. File -> Open -> select the KnightEventAlarm folder.
3. Let Gradle sync. Add Android Gradle Plugin / Gradle wrapper if prompted.
4. Build > Make Project. Then Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Install the generated APK on your Android device.

Notes:
- The project is a skeleton; you may need to add Gradle wrapper files and adjust versions if Android Studio prompts.
- I couldn't build the APK here. This package contains full source you can open and build locally.
- To get the app to pre-add your times at first run, call Prepopulate.addDefaults(this) from MainActivity.onCreate().
