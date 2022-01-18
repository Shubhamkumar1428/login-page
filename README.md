# login-page 
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:id="@+id/content"
    tools:context=".MainActivity">
    <!--<TextView-->
        <!--android:layout_width="wrap_content"-->
        <!--android:layout_height="wrap_content"-->
        <!--android:text="Login Page"-->
        <!--android:textSize="52dp"-->
        <!--android:textColor="#FFF"-->
        <!--android:textAlignment="center"-->
        <!--android:background="#03A9F4"-->
        <!--android:layout_marginRight="30dp"-->
        <!--android:layout_marginLeft="70dp"-->
        <!--android:layout_marginTop="30dp"-->
        <!--android:textStyle="bold"/>-->
    <ImageView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:src="@drawable/hackr"
        android:layout_marginTop="50dp"/>
  <android.support.design.widget.TextInputLayout
        android:id="@+id/et_username"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="30dp"
        android:layout_marginRight="30dp"
        android:layout_marginTop="70dp"
        app:boxStrokeColor="#223CD6"
        style="@style/Widget.MaterialComponents.TextInputLayout.OutlinedBox">
        <android.support.design.widget.TextInputEditText
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter Username"
            android:inputType="text"
            android:maxLines="1"/>
    </android.support.design.widget.TextInputLayout>
    <android.support.design.widget.TextInputLayout
        android:id="@+id/et_password"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="30dp"
        android:layout_marginRight="30dp"
        android:layout_marginTop="20dp"
        app:boxStrokeColor="#223CD6"
        style="@style/Widget.MaterialComponents.TextInputLayout.OutlinedBox">
        <android.support.design.widget.TextInputEditText
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Enter Password"
            android:inputType="text"
            android:maxLines="1"/>
    </android.support.design.widget.TextInputLayout>
    <Button
        android:id="@+id/login_button"
        android:layout_width="189dp"
        android:backgroundTintMode="multiply"
        android:layout_height="wrap_content"
        android:layout_marginLeft="120dp"
        android:layout_marginRight="120dp"
        android:layout_marginTop="30dp"
        android:backgroundTint="#03A9F4"
        android:text="Login"
        android:textColor="#FFFFFF"
        android:textSize="28dp" />
    <TextView
        android:id="@+id/create"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="120dp"
        android:layout_marginRight="120dp"
        android:textAlignment="center"
        android:layout_marginTop="20dp"
        android:textSize="18dp"
        android:textStyle="bold"
        android:textColor="#03A9F4"
        android:text="Create Account"/>
    <TextView
        android:id="@+id/change_password"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="120dp"
        android:layout_marginRight="120dp"
        android:textAlignment="center"
        android:layout_marginTop="20dp"
        android:textSize="18dp"
        android:textStyle="bold"
        android:textColor="#03A9F4"
        android:text="Change Password" />
</LinearLayout>
