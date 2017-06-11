# Rate
自定义星评控件
**使用方式：**
 custom_rate_size：星星的总个数
 custom_rate_active_size：选中星星的个数
 custom_rate_padding：星星之间的间距
 custom_rate_active_drawable：选中星星的图片，可以不用，不用就是用默认的
 custom_rate_disactive_drawable：未选中星星的图片，可以不用，不用就是用默认的
 custom_rate_height：每一个星星的高度
 custom_rate_width：每一个星星的宽度
 custom_rate_touch：是否可以支持触摸，默认是不支持
 
  **实列：**
<com.example.rate.view.Rate
        android:id="@+id/mRate"
        android:layout_width="wrap_content"
        android:layout_height="40dp"
        app:custom_rate_size="5"
        app:custom_rate_active_size="4"
        app:custom_rate_padding="3dp"
        app:custom_rate_active_drawable="@mipmap/custom_rateingbar_active"
        app:custom_rate_disactive_drawable="@mipmap/custom_rateingbar_disactive"
        app:custom_rate_height="50dp"
        app:custom_rate_width="50dp"
        app:custom_rate_touch="true"
        android:background="#FFFFFF"
        android:layout_centerVertical="true"
        android:layout_centerHorizontal="true" />
