# mygreetingscard
A project for a greeting card for Udacity Android Beginners course


<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:src="@drawable/card_winter"
        android:scaleType="centerCrop"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Pozdrowienia z ferii zimowych!"
        android:textSize="36sp"
        android:fontFamily="sans-serif-bold"
        android:textColor="@android:color/white"
        android:padding="20dp"
        android:layout_centerHorizontal="true"
        android:id="@+id/greeting_textView"/>

    <ImageView
        android:layout_width="120dp"
        android:layout_height="120dp"
        android:src="@drawable/card_skis"
        android:scaleType="centerCrop"
        android:id="@+id/skis_ImageView"
        android:layout_centerVertical="true"
        android:layout_centerHorizontal="true"
        android:layout_margin="20dp"    />

    <ImageView
        android:layout_width="120dp"
        android:layout_height="120dp"
        android:src="@drawable/card_kid"
        android:scaleType="centerCrop"
        android:layout_toRightOf="@id/skis_ImageView"
        android:layout_centerVertical="true"
        android:id="@+id/kid_ImageView" />

    <ImageView
        android:layout_width="120dp"
        android:layout_height="120dp"
        android:src="@drawable/card_snowboard"
        android:scaleType="centerCrop"
        android:layout_toLeftOf="@id/skis_ImageView"
        android:layout_centerVertical="true"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="WISLA NOWA OSADA"
        android:textSize="36sp"
        android:fontFamily="sans-serif-bold"
        android:textColor="@android:color/white"
        android:layout_margin="20dp"
        android:layout_above="@id/signature_textView"
        android:layout_centerHorizontal="true"    />


      <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Leon, Laura i Ignacy z rodzicami"
        android:textSize="36sp"
        android:fontFamily="sans-serif-bold"
        android:textColor="@android:color/white"
        android:layout_margin="20dp"
        android:layout_alignParentBottom="true"
        android:id="@+id/signature_textView"
        android:layout_centerHorizontal="true"      />

</RelativeLayout>
