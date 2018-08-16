# RoundedImageView
A library to implement RoundedImageView like User Interface for Profile Image in your App.

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
Step 2. Add the dependency to Gradle.

	dependencies {
	     implementation 'com.github.Jay268:RoundedImageView:0.1.0'
	}

XML usage.

	<?xml version="1.0" encoding="utf-8"?>
	<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
	    xmlns:app="http://schemas.android.com/apk/res-auto"
	    xmlns:tools="http://schemas.android.com/tools"
	    android:layout_width="match_parent"
	    android:layout_height="match_parent"
	    android:orientation="vertical"
	    tools:context=".MainActivity">

	    <RelativeLayout
		android:layout_width="match_parent"
		android:layout_height="match_parent">

		<com.jay.RoundedImageView
		    android:layout_width="50dp"
		    android:layout_height="50dp"
		    android:layout_centerInParent="true"
		    android:src="@drawable/sample_rounded"
		    app:riv_border_color="@color/color_77ABFF"
		    app:riv_border_width="2dp" />

	    </RelativeLayout>


	</LinearLayout>
