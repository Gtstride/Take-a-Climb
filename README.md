# Take-a-Climb
My very first repository here 
Hey, i am Godstime, and an android developer, it feel awesome to be using this platform with great minds, hope to learn from all, thanks.
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical">

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content">

        <TextView
            android:id="@+id/text_view_p1"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Player 1: 0"
            android:textSize="30sp" />

        <TextView
            android:id="@+id/text_view_p2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_below="@+id/text_view_p1"
            android:text="Player 2: 0"
            android:textSize="30sp" />

        <Button
            android:id="@+id/button_reset"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_alignParentEnd="true"
            android:layout_alignParentRight="true"
            android:layout_centerVertical="true"
            android:layout_marginEnd="33dp"
            android:layout_marginRight="0dp"
            android:text="reset" />

    </RelativeLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1">

        <Button
            android:id="@+id/button_00"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:textSize="60sp" />

        <Button
            android:id="@+id/button_01"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:textSize="60sp" />

        <Button
            android:id="@+id/button_02"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:textSize="60sp" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1">

        <Button
            android:id="@+id/button_10"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:textSize="60sp" />

        <Button
            android:id="@+id/button_11"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:textSize="60sp" />

        <Button
            android:id="@+id/button_12"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:textSize="60sp" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1">

        <Button
            android:id="@+id/button_20"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:textSize="60sp" />

        <Button
            android:id="@+id/button_21"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:textSize="60sp" />

        <Button
            android:id="@+id/button_22"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:textSize="60sp" />

    </LinearLayout>

</LinearLayout>
