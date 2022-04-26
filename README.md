# androidstdioexpt1
# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Android Studio(Min. required Artic Fox)

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as “ex.no.1″ and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:

### Program to print the text “Hello World”.
### Developed by: H.Dhayanitha
### Registeration Number :212220230010

### MainActivity.java
```
package com.example.exno1;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;
public class MainActivity extends AppCompatActivity {
    @Override
protected void onCreate(Bundle savedInstanceState) { super.onCreate(savedInstanceState); setContentView(R.layout.activity_main);
    Toast toast=Toast.makeText(getApplicationContext(),"OnCreate Invoked",Toast.LENGTH_LONG);
    toast.show();
}

    protected void onStart(){ super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume(){ super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"OnResume Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause(){ super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop(){ super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onRestart(){ super.onRestart();

        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy(){ super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Invoked",Toast.LENGTH_LONG);
        toast.show();
    }
}
```
### activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```
## OUTPUT
![java1](https://user-images.githubusercontent.com/75235032/163918030-75535d82-9c8a-4940-9a4a-6bda13e4b2d0.png)
![java2](https://user-images.githubusercontent.com/75235032/163918797-42ddbed6-438e-431b-b4f1-74995747d3ee.png)
![java3](https://user-images.githubusercontent.com/75235032/163918812-d9678509-e318-4c3c-8ea2-97f7438f8990.png)
![java4](https://user-images.githubusercontent.com/75235032/163918836-ac2d037d-e094-4bb4-860b-8ff1728493d7.png)
![java5](https://user-images.githubusercontent.com/75235032/163918857-7eff5285-40ac-455c-9ead-babafd0436b6.png)
![java6](https://user-images.githubusercontent.com/75235032/163918892-675e49c7-953b-4af3-a51f-42bf6fa19cdc.png)
![java7](https://user-images.githubusercontent.com/75235032/163918974-3732b686-49d4-41e2-934a-7c6c4265ebde.png)

## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.

