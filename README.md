EasyCountDownTextureView
==
   
<br>
   
![Language](https://img.shields.io/badge/language-Java-EE0000.svg) [![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/CaMnter/EasyCountDownTextureView/blob/master/LICENSE) 
![Version](https://img.shields.io/badge/version-1.6-8470FF.svg) 
![SDK](https://img.shields.io/badge/SDK-14%2B-orange.svg) 
[ ![Download](https://api.bintray.com/packages/camnter/maven/EasyCountDownTextureView/images/download.svg) ](https://bintray.com/camnter/maven/EasyCountDownTextureView/_latestVersion)   

**Easy count down by TextureView**
   
<br>
<br>
   
## Attention

**minSdkVersion >= 14**
   
<br>
<br>
   
## Gradle

```gradle
dependencies {
	compile 'com.camnter.easycountdowntextureview:easycountdowntextureview:1.6'
}
```
   
<br>
<br>
   
## Attributes

```xml
<declare-styleable name="EasyCountDownTextureView">
    <attr name="easyCountRectWidth"
        format="dimension"/>
    <attr name="easyCountRectHeight"
        format="dimension"/>
    <attr name="easyCountRectRadius"
        format="dimension"/>
    <attr name="easyCountRectBorderSize"
        format="dimension"/>
    <attr name="easyCountRectBorderColor"
        format="color"/>
    <attr name="easyCountRectBorderStroke"
        format="dimension"/>
    <attr name="easyCountRectSpacing"
        format="dimension"/>
    <attr name="easyCountTimeColor"
        format="color"/>
    <attr name="easyCountTimeSize"
        format="dimension"/>
    <attr name="easyCountTimeStroke"
        format="dimension"/>
    <attr name="easyCountColonColor"
        format="color"/>
    <attr name="easyCountColonSize"
        format="dimension"/>
    <attr name="easyCountColonStroke"
        format="dimension"/>
    <attr name="easyCountBackgroundColor"
        format="color"/>
    <attr name="easyCountHour"
        format="integer"/>
    <attr name="easyCountMinute"
        format="integer"/>
    <attr name="easyCountSecond"
        format="integer"/>
</declare-styleable>
```
   
<br>
<br>
   
## Easy use
 
```xml
<RelativeLayout
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:layout_marginBottom="50dp"
    android:background="#ffffffff">

    <ImageView
        android:layout_width="196dp"
        android:layout_height="158dp"
        android:layout_marginTop="26dp"
        android:scaleType="centerCrop"
        android:src="@mipmap/bg_fruit" />

    <com.camnter.easycountdowntextureview.EasyCountDownTextureView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:easyCountHour="6"
        app:easyCountMinute="6"
        app:easyCountSecond="26" />

</RelativeLayout>
```
   
<br>  
      
![TextureView_1](https://github.com/CaMnter/EasyCountDownTextureView/raw/master/screenshot/textureview_1.gif) 

<br>
  
```xml
<com.camnter.easycountdowntextureview.EasyCountDownTextureView
    android:id="@+id/style_tv"
    android:layout_width="132dp"
    android:layout_height="36dp"
    app:easyCountBackgroundColor="#ffdddddd"
    app:easyCountColonColor="#ffdddddd"
    app:easyCountColonSize="20sp"
    app:easyCountHour="6"
    app:easyCountMinute="6"
    app:easyCountRectHeight="34dp"
    app:easyCountRectRadius="5dp"
    app:easyCountRectSpacing="12dp"
    app:easyCountRectWidth="36dp"
    app:easyCountSecond="26"
    app:easyCountTimeColor="#ff3A94FF"
    app:easyCountTimeSize="20sp" />
```

<br>
  
![TextureView_2](https://github.com/CaMnter/EasyCountDownTextureView/raw/master/screenshot/textureview_2.gif) 
   
<br>
<br>
   
## Performance

Without scrolling, only time in the refreshing

<img src="http://ww1.sinaimg.cn/large/006lPEc9gw1f30vnkpd1ej31ay298k20.jpg" width="420x"/> 
<img src="http://ww4.sinaimg.cn/large/006lPEc9gw1f30vo7yaqaj31ay298wzw.jpg" width="420x"/>
   
<br>
<br>
   
## License

      Copyright (C) 2016 CaMnter yuanyu.camnter@gmail.com

      Licensed under the Apache License, Version 2.0 (the "License");
      you may not use this file except in compliance with the License.
      You may obtain a copy of the License at

         http://www.apache.org/licenses/LICENSE-2.0

      Unless required by applicable law or agreed to in writing, software
      distributed under the License is distributed on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
      See the License for the specific language governing permissions and
      limitations under the License.


