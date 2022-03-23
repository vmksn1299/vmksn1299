<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:layout_gravity="center"
    android:background="@drawable/layout_bg"
    android:gravity="center"
    android:orientation="vertical"
    android:padding="20dp">

    <TextView
        android:id="@+id/dialog_header"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center_horizontal"
        android:padding="10dp"
        android:text="Error"
        android:textColor="#000" />

    <TextView
        android:id="@+id/message_text"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center_horizontal"
        android:padding="10dp"
        android:text="Error-Message"
        android:textColor="#000" />


    <Button
        android:id="@+id/dialogButtonOK"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/message_text"
        android:layout_gravity="center_horizontal"
        android:layout_marginTop="5dp"
        android:text="Ok" />


</LinearLayout>
