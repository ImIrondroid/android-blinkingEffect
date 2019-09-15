# Blink

by C.H.Choi

## The most easiest way to apply the blinking effect to .xml in Android Studio

 Just add this Tag 'blink' like this below .xml and then start building your app
 
  ```bash
     <?xml version="1.0" encoding="utf-8"?>

     <blink
      xmlns:android="http://schemas.android.com/apk/res/android"
      xmlns:app="http://schemas.android.com/apk/res-auto"
      xmlns:tools="http://schemas.android.com/tools"
      android:layout_width="match_parent"
      android:layout_height="match_parent">

      <androidx.constraintlayout.widget.ConstraintLayout
         android:layout_width="match_parent"
         android:layout_height="match_parent"
         tools:context=".MainActivity">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="43dp"
            android:layout_marginTop="8dp"
            android:text="Blinking"
            android:textSize="32sp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintHorizontal_bias="0.498"
            app:layout_constraintLeft_toLeftOf="parent"
            app:layout_constraintRight_toRightOf="parent"
            app:layout_constraintTop_toTopOf="@id/imageView"
            app:layout_constraintVertical_bias="0.125" />

       </androidx.constraintlayout.widget.ConstraintLayout>

      </blink>
   ```
 
