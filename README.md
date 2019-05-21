<p align="center"><img src="/logo/logotype-horizontal.png"></p>


zoomable android ImageView
simply move & zoom images with gestures


JitPack project integration:

[![](https://jitpack.io/v/nuclearfog/ZoomView.svg)](https://jitpack.io/#nuclearfog/ZoomView)



Example:
```xml
<org.nuclearfog.zoomview.ZoomView
  android:id="@+id/zoom_image"
  android:src="@drawable/image"
  android:layout_width="match_parent"
  android:layout_height="match_parent" />
```


```java
ZoomImage zoomImage = findViewById(R.id.zoom_image);

zoomImage.setImageBitmap(image);  // Set Image
zoomImage.reset();                // Reset Zoom to default
```


Notes:
- SVG images are not supported
- wrap_content is not supported
- high resolutions may lead to lag

logo design by <a href="https://github.com/Tobaloidee" title="">@Tobaloidee</a>
