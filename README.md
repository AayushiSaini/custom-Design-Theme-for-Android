# custom-Design-Theme-for-Android
Creating a custom design theme in Android allows you to define your own set of styles and attributes that can be applied to various UI elements throughout your app. You can customize colors, fonts, dimensions, and more to create a consistent and unique look for your app. 


Prebuild Design 
you can directly paste this theme to your theme file


<!--  theme for the main activity -->
<style name="AppTheme_MainActivity" parent="Theme.AppCompat.Light.DarkActionBar">
        <item name="colorPrimary">@color/blue</item>
        <item name="colorPrimaryDark">@color/blue</item>
        <item name="android:navigationBarColor">@color/blue</item>

      </style>

------------------------------------------------------------------------------------------------------------------------------------------

   <!--  theme for the other activity -->
   <style name="AppTheme_OtherActivities" parent="Theme.AppCompat.Light.NoActionBar">
        <item name="colorPrimary">@color/white</item>
        <item name="colorPrimaryDark">@color/Dark_red</item>
        <!-- Other theme attributes for other activities -->
    </style>

    
