# stunning-waffle<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.zaydboon.helloandroid1.MainActivity"
    android:background="#0091EA">


    <ImageView
        android:id="@+id/image"
        android:layout_width="match_parent"
        android:layout_height="215dp"
        android:src="@drawable/mwu"
        android:layout_alignParentTop="true"
        android:scaleType="centerCrop"/>

    <ImageView
        android:layout_width="24dp"
        android:layout_height="24dp"
        android:layout_below="@+id/thirdtxt"
        android:layout_toStartOf="@+id/firsttxt"
        android:src="@drawable/ic_call_black_24dp" />

    <TextView
        android:id="@+id/firsttxt"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"
        android:paddingBottom="8dp"
        android:paddingTop="24dp"
        android:text="@string/udacity"
        android:textColor="#FFFFFF"
        android:textSize="30sp" />

    <TextView
        android:id="@+id/secondtxt"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/thirdtxt"
        android:layout_centerHorizontal="true"
        android:gravity="center"
        android:paddingBottom="8dp"
        android:text="@string/addressline1"
        android:textColor="#FFFFFF"
        android:textSize="16sp" />

    <TextView
        android:id="@+id/thirdtxt"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/textView"
        android:layout_centerHorizontal="true"
        android:gravity="center"
        android:paddingBottom="8dp"
        android:text="@string/addressline2"
        android:textColor="#FFFFFF"
        android:textSize="16sp" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:gravity="center"
        android:text="@string/website"
        android:textColor="#424242"
        android:textSize="32sp"
        android:fontFamily="cursive"
        android:autoLink="web"/>

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/textView2"
        android:layout_alignEnd="@+id/secondtxt"
        android:layout_marginBottom="43dp"
        android:gravity="center"
        android:text="@string/number"
        android:textColor="#FFFFFF"
        android:textSize="16sp" />



</RelativeLayout>
