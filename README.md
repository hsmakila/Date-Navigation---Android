# Android Date Navigation Bar

DateNavigationBar is an Android library that provides a custom date navigation bar component. This component can be used in other projects to navigate through dates using a bottom navigation component.

## Project Structure

```
.gitignore
.gradle/
app/
    .gitignore
    app.iml
    build/
    build.gradle
    libs/
    proguard-rules.pro
    src/
        main/
            java/
                com/example/akila/datenavigationbar/
                    MainActivity.java
                    CustomView.java
            res/
                drawable/
                    ic_launcher_background.xml
                drawable-v24/
                    ic_launcher_foreground.xml
                layout/
                    activity_main.xml
                    custom_view.xml
                mipmap-anydpi-v26/
                    ic_launcher.xml
                    ic_launcher_round.xml
                values/
                    attrs.xml
                    colors.xml
                    strings.xml
                    styles.xml
            AndroidManifest.xml
        androidTest/
            java/
                com/example/akila/datenavigationbar/
                    ExampleInstrumentedTest.java
        test/
            java/
                com/example/akila/datenavigationbar/
                    ExampleUnitTest.java
build.gradle
gradle/
    wrapper/
gradle.properties
gradlew
gradlew.bat
local.properties
mylibrary/
    .gitignore
    build/
    build.gradle
    libs/
    mylibrary.iml
    proguard-rules.pro
    src/
        main/
            java/
                com/example/mylibrary/
            res/
                values/
                    strings.xml
            AndroidManifest.xml
        androidTest/
            java/
                com/example/mylibrary/
                    ExampleInstrumentedTest.java
        test/
            java/
                com/example/mylibrary/
                    ExampleUnitTest.java
settings.gradle
```

## Getting Started

### Prerequisites

- Android Studio 3.2.1 or later
- Gradle 4.6 or later
- Java Development Kit (JDK) 8 or later

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/DateNavigationBar.git
    ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files.

### Building the Project

To build the project, use the following command:
```sh
./gradlew build
```

### Running the Project

To run the project on an Android device or emulator, use the following command:
```sh
./gradlew installDebug
```

## Usage

To use the DateNavigationBar component in your project, add the following dependency to your 

build.gradle

 file:

```gradle
implementation project(':mylibrary')
```

Then, you can include the 

CustomView

 in your layout XML file:

```xml
<com.example.akila.datenavigationbar.CustomView
    android:id="@+id/customView"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:artistText="Artist Name"
    app:trackText="Track Name"
    app:buyButton="Buy" />
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Android Support Libraries
- Gradle Build System
