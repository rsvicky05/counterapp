Step 1: Setting Up the Project
    Open Android Studio and create a new project:
    
      Select Empty Activity.
      Name the project "CounterApp".
      Choose Java as the language.
      Leave other options at their default values.
      Click Finish to create the project.
      Android Studio will generate basic project files, including MainActivity.java and activity_main.xml.

Step 2: Design the User Interface (UI)
    Open activity_main.xml under res/layout.
    
    Edit this file to create a layout with a TextView to display the counter, two buttons for increasing and decreasing the counter, and a third button to reset it.

Step 3: Implement the Functionality in MainActivity.java
    Open MainActivity.java in the java directory.
    
    Define variables and set up OnClickListener for each button to update the counter and display it in tvCounter.

Step 4: Run the App
    Connect an Android device via USB or use an emulator in Android Studio.
      Click the Run button (green play button) in the Android Studio toolbar to build and launch the app.
      Test the App:
        Press Increase to increment the counter.
        Press Decrease to decrement the counter.
        Press Reset to reset the counter back to zero.
