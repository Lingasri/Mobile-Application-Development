# Ex.No: 2 To develop an application that uses GUI Components with Fonts and Colors. 
Note: Create button for colors and fonts while clicking color or font button should change 


## AIM:

To create an application that uses GUI Components with Fonts and Colors using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:


## PROGRAM:
```
/*
Program to print the text “GUIcomponent”.
Developed by:Lingasri P
Registeration Number :212221040089
*/
```
activity_main.xml:

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/head"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"

        android:text="Mobile Application Development"

        android:textSize="20sp"
        app:layout_constraintBottom_toTopOf="@+id/body"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/body"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="356dp"

        android:text="HELLO WORLD"

        android:textSize="20sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent" />
</androidx.constraintlayout.widget.ConstraintLayout>

mainActivity.java:

package com.example.guicomps;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast t = Toast.makeText(getApplicationContext(),"onCreate Called",Toast.LENGTH_LONG);
        t.show();
    }

    protected void onStart(){
        super.onStart();
        Toast t = Toast.makeText(getApplicationContext(),"onStart Called",Toast.LENGTH_LONG);
        t.show();
    }

    protected void onRestart(){
        super.onRestart();
        Toast t = Toast.makeText(getApplicationContext(),"onRestart Called",Toast.LENGTH_LONG);
        t.show();
    }

    protected void onPause(){
        super.onPause();
        Toast t = Toast.makeText(getApplicationContext(),"onPause Called",Toast.LENGTH_LONG);
        t.show();
    }

    protected void onResume(){
        super.onResume();
        Toast t = Toast.makeText(getApplicationContext(),"onResume Called",Toast.LENGTH_LONG);
        t.show();
    }

    protected void onStop(){
        super.onStop();
        Toast t = Toast.makeText(getApplicationContext(),"onStop Called",Toast.LENGTH_LONG);
        t.show();
    }

    protected void onDestroy(){
        super.onDestroy();
        Toast t = Toast.makeText(getApplicationContext(),"onDestroy Called",Toast.LENGTH_LONG);
        t.show();
    }
}

## OUTPUT




## RESULT
Thus a Simple Android Application that uses GUI Components with Fonts and Colors using Android Studio is developed and executed successfully.


