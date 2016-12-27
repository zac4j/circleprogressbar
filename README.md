# CircleProgressBar
Circle Progress Bar

## Screenshots


## Integration
**CircleProgressBar** (min API 16):

## Usage
- include this in your layout file
```xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/activity_main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.zac4j.sample.MainActivity"
    >

  <com.zac4j.widget.CircleProgressBar
      android:id="@id/progress_bar"
      android:layout_width="wrap_content"
      android:layout_height="wrap_content"
      android:layout_centerInParent="true"
      android:textSize="16sp"
      app:size="large"
      app:strokeBgColor="@color/gray"
      app:strokeColor="@color/purple"
      app:strokeWidth="4dp"
      />

</RelativeLayout>
```

## License
The code is available under the [Apache License][license]

[license]:https://github.com/zac4j/CircleProgressBar/blob/master/LICENSE
