# Documentation

#Toolbar
'''
<android.support.v7.widget.Toolbar
android:id="@+id/toolbar"
android:layout_width="match_parent"
android:layout_height="?attr/actionBarSize"
app:layout_collapseMode="pin"
app:popupTheme="@style/ThemeOverlay.AppCompat.Light" />
'''

<FrameLayout xmlns:android="http://schemas.android.com/apk/res/android"
xmlns:app="http://schemas.android.com/apk/res-auto"
android:id="@+id/fl_root"
android:layout_width="match_parent"
android:layout_height="wrap_content"
android:orientation="vertical">

<LinearLayout
android:layout_width="match_parent"
android:layout_height="@dimen/actionbar_height"
android:layout_below="@+id/img_plan"
android:gravity="center"
android:orientation="horizontal">

<ImageView
android:id="@+id/btn_action_left"
android:layout_width="wrap_content"
android:layout_height="wrap_content"
android:layout_gravity="left"
android:layout_weight="0.5"
android:gravity="center"
android:onClick="actionLeft"
app:srcCompat="@mipmap/ic_back_white" />

<TextView
android:id="@+id/txt_title"
android:layout_width="wrap_content"
android:layout_height="wrap_content"
android:layout_weight="3"
android:gravity="center"
android:text="Control"
android:textColor="@color/color_text_white"
android:textSize="@dimen/connect_text_size_title" />

<TextView
android:id="@+id/btn_action_right"
android:layout_width="wrap_content"
android:layout_height="wrap_content"
android:layout_weight="1"
android:gravity="center"
android:onClick="actionRight"
android:text="Close"
android:textColor="@color/color_text_white"
android:textSize="@dimen/connect_text_size_title" />

</LinearLayout>

</FrameLayout>
