说明：
=====

该包为工具包，当前添加的工具，请查看项目文档。


使用步骤：
=====

dependencies {<br>
compile 'com.tools.zh:android_tweak:1.0.3' exclude group: 'com.android.support'//当前版本为1.0.3版本；<br>
}<br>

在project根目录下的build.gradle中添加如下代码

allprojects {<br>
repositories {<br>
maven{<br>
url "https://github.com/ZHAndroidTweak/AndroidTweak/raw/master"<br>
    }<br>
      }<br>
        }<br>
