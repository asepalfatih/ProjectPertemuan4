# ProjectPertemuan4

  <?xml version="1.0" encoding="utf-8"?>
  <RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
      android:layout_width="match_parent"
      android:layout_height="match_parent"
      android:paddingBottom="@dimen/activity_vertical_margin"
      android:paddingHorizontal="@dimen/antivity_horizontal_margin"
      android:paddingTop="@dimen/antivity_horizontal_margin">




      <Button
          android:id="@+id/button"
          android:layout_alignparentbottom="true"
          android:layout_width="match_parent"
          android:layout_height="wrap_content"
          android:text="Scan Qr Code"
          android:layout_alignParentBottom="true" />




      <LinearLayout
          android:layout_width="match_parent"
          android:layout_height="wrap_content"
          android:orientation="vertical"
          >

          <ImageView
              android:layout_width="wrap_content"
              android:layout_height="wrap_content"
              android:layout_gravity="center"
              android:src="@mipmap/ic_launcher"/>

          <TextView
              android:id="@+id/textNama"
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:paddingBottom="10dp"
              android:text="Nama" />

          <TextView
              android:id="@+id/textViewXYZ"
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:text="XYZ" />

          <TextView
              android:id="@+id/textViewKElas"
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:text="Kelas" />

      </LinearLayout>


  </RelativeLayout>
