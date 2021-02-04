# android-apssdc-qiscet
This Repo is for sample creation of git&amp;github class for QISCET 3rd CSE Greate Students

=================================================================================================================================================

# Andhra Pradesh State Skill Development Corporation[APSSDC]

-------------------------------------------------------------------------------------------------------------------------------------------------
## Andhra Pradesh State Skill Development Corporation[APSSDC]
### Andhra Pradesh State Skill Development Corporation[APSSDC]
#### Andhra Pradesh State Skill Development Corporation[APSSDC]
##### Andhra Pradesh State Skill Development Corporation[APSSDC]
###### Andhra Pradesh State Skill Development Corporation[APSSDC]

* Oredered List & Un-Ordered List
  1. QIS Collge 
      * PG
          * M.TECH
          * MBA
          * MCA
      * UG
          * B.TECH
          * B.Pharmacy
  2. APSSDC
      * Engineering
          1. Android
          2. Python
          3. Djano
          4. IOT
          5. Embeded Systems
          6. AutoCad
      * Degree 
          1. Python
          2. C-Laung
          3. Tally

<img src="https://www.apssdc.in/home/images/apssdc_final.png" width=400>

[Click here for web Link](https://www.apssdc.in/home/)

```XML
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
        android:text="Registration Page!"
        android:textColor="@color/colorAccent"
        android:textSize="30sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintHorizontal_bias="0.458"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.08" />

    <EditText
        android:id="@+id/et_username"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="28dp"
        android:ems="10"
        android:hint="Enter the User name "
        android:inputType="textPersonName"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView" />

    <EditText
        android:id="@+id/et_mobilenumber"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="1dp"
        android:layout_marginLeft="1dp"
        android:layout_marginTop="20dp"
        android:ems="10"
        android:hint="Enter The Mobile Number"
        android:inputType="number"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="@+id/et_username"
        app:layout_constraintTop_toBottomOf="@+id/et_username" />

    <EditText
        android:id="@+id/editText3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:layout_marginEnd="4dp"
        android:layout_marginRight="4dp"
        android:ems="10"
        android:hint="Enter the Email_id"
        android:inputType="textEmailAddress"
        app:layout_constraintEnd_toEndOf="@+id/et_mobilenumber"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/et_mobilenumber" />


    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="74dp"
        android:layout_marginLeft="74dp"
        android:layout_marginTop="152dp"
        android:layout_marginEnd="74dp"
        android:layout_marginRight="74dp"
        android:onClick="submitValues"
        android:text="submit"
        app:layout_constraintEnd_toEndOf="@+id/et_username"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="@+id/textView"
        app:layout_constraintTop_toBottomOf="@+id/editText3" />

    <RadioGroup
        android:id="@+id/radioGroup"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginTop="7dp"
        android:orientation="vertical"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editText3">

        <RadioButton
            android:id="@+id/rb_male"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Male" />

        <RadioButton
            android:id="@+id/rb_female"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Female" />
    </RadioGroup>

    <RadioButton
        android:id="@+id/radio"
        android:visibility="invisible"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="36dp"
        android:layout_marginEnd="20dp"
        android:layout_marginRight="20dp"
        android:text="Male"
        app:layout_constraintEnd_toEndOf="@+id/editText3"
        app:layout_constraintTop_toBottomOf="@+id/editText3" />

    <RadioButton
        android:id="@+id/rb_female1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginTop="18dp"
        android:text="Female"
        android:visibility="invisible"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="@+id/editText3"
        app:layout_constraintTop_toBottomOf="@+id/editText3"
        app:layout_constraintVertical_bias="0.057" />

    <CheckBox
        android:id="@+id/checkBox"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="16dp"
        android:layout_marginLeft="16dp"
        android:layout_marginTop="26dp"
        android:text="CheckBox"
        app:layout_constraintEnd_toStartOf="@+id/checkBox2"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/rb_female1" />

    <CheckBox
        android:id="@+id/checkBox2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="7dp"
        android:layout_marginLeft="7dp"
        android:layout_marginBottom="22dp"
        android:text="CheckBox"
        app:layout_constraintBottom_toTopOf="@+id/button"
        app:layout_constraintEnd_toStartOf="@+id/checkBox3"
        app:layout_constraintStart_toStartOf="@+id/button" />

    <CheckBox
        android:id="@+id/checkBox3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginEnd="26dp"
        android:layout_marginRight="26dp"
        android:text="CheckBox"
        app:layout_constraintBaseline_toBaselineOf="@+id/checkBox2"
        app:layout_constraintEnd_toEndOf="parent" />

    <Spinner
        android:id="@+id/spinner"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginStart="1dp"
        android:layout_marginLeft="1dp"
        android:layout_marginTop="8dp"
        android:layout_marginEnd="1dp"
        android:layout_marginRight="1dp"
        android:entries="@array/branchNames"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/checkBox3" />


</androidx.constraintlayout.widget.ConstraintLayout>
```
