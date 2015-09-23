# ImageTextButton
Button with icon and text. 
��ͼ������ֵİ�ť��֧��ͼ�����������������ĸ����򣬿�ָ��ͼ��ߴ��Լ�������֮��ľ��룬֧��ָ������ɫ��֧��Բ�ǡ�

# Useage
```
dependencies {
    compile 'cn.dxjia:imagetextbutton:1.0.0'
}
```

|�ֶ�|��ѡ|����|˵��|
|----|----|----|----|
|itb_icon|false|reference|ͼ����Դ����ָ��ʱ����ʾ|
|itb_icon_size|false|dimension|ͼ��ߴ磬Ĭ��24dpx24dp|
|itb_text|false|string|��ť����|
|itb_text_color|false|color|��ť������ɫ��Ĭ�ϰ�ɫ|
|itb_icon_text_marggin|false|dimension|ͼ��������֮��ļ��|
|itb_icon_position|false|string|ͼ����������ֵ�λ�ã�`"left"` `"top"` `"right"` `"bottom"`����|
|itb_bg|false|color|��ͨ״̬�µİ�ť����ɫ��Ĭ����ɫ|
|itb_bg_pressed|false|color|����״̬�µİ�ť����ɫ����ָ��ʱĬ��Ϊitb_bg�İ�͸��״̬|
|itb_bg_disabled|false|color|������״̬�İ�ť����ɫ��Ĭ�ϻ�ɫ|
|itb_radius|false|dimension|��ťĬ��Բ��,Ĭ��Ϊ0dp|

# Sample
```xml
    <com.dxjia.library.ImageTextButton
	    xmlns:view="http://schemas.android.com/apk/res-auto"
        android:id="@+id/btn_1"
        android:layout_marginTop="20dp"
        android:layout_centerHorizontal="true"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        view:itb_bg="@color/button_bg"
        view:itb_text="Click to Share"
        view:itb_radius="3dp"
        view:itb_icon="@mipmap/ic_share_white_48dp">
    </com.dxjia.library.ImageTextButton>
```

# ScreeShot
![Img](https://github.com/dxjia/ImageTextButton/blob/master/screeshots/imagetextbutton-screenshot.jpeg)

More reference the `Sample` module
# License
```
Copyright (C) 2015 dxjia

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```