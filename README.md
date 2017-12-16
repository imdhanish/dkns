# dkns
basic of android xml
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#BBDEFB"
    android:visibility="visible"
    tools:context="com.example.android.dknsgc.MainActivity">

    <TextView
        android:id="@+id/main"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="dkns"
        android:textColor="#4CAF50"
        android:textSize="30dp"
        tools:layout_editor_absoluteX="145dp"
        tools:layout_editor_absoluteY="109dp" />

    <TextView
        android:id="@+id/main1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="group of companies"
        android:textColor="#4CAF50"
        android:textSize="30dp"
        tools:layout_editor_absoluteX="57dp"
        tools:layout_editor_absoluteY="150dp" />

    <EditText
        android:id="@+id/editText"
        android:layout_width="260dp"
        android:layout_height="50dp"
        android:ems="10"
        android:hint="Email "
        android:inputType="textEmailAddress"
        tools:layout_editor_absoluteX="62dp"
        tools:layout_editor_absoluteY="241dp" />

    <EditText
        android:id="@+id/editText2"
        android:layout_width="269dp"
        android:layout_height="wrap_content"
        android:ems="10"
        android:hint="Password"
        android:inputType="textPassword"
        tools:layout_editor_absoluteX="60dp"
        tools:layout_editor_absoluteY="312dp" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Login"
        tools:layout_editor_absoluteX="135dp"
        tools:layout_editor_absoluteY="385dp" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="click here to Signup"
        android:textColor="#F44336"
        android:textSize="20dp"
        tools:layout_editor_absoluteX="104dp"
        tools:layout_editor_absoluteY="468dp" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="OR"
        android:textColor="#FFFF00"
        android:textSize="20dp"
        tools:layout_editor_absoluteX="163dp"
        tools:layout_editor_absoluteY="441dp" />

</android.support.constraint.ConstraintLayout>
