[![](https://travis-ci.org/SouthernBox/ParallaxRecyclerView.svg?branch=master)](https://travis-ci.org/SouthernBox/ParallaxRecyclerView)
[![](https://api.bintray.com/packages/southernbox/maven/ParallaxRecyclerView/images/download.svg)](https://bintray.com/southernbox/maven/ParallaxRecyclerView/_latestVersion)
![](https://img.shields.io/badge/platform-android-green.svg)
[![](https://img.shields.io/badge/API-15+-green.svg?style=flat)](https://android-arsenal.com/api?level=15)
![](https://img.shields.io/badge/language-java-orange.svg)
[![](https://badge.juejin.im/entry/58dca9212f301e0062f8cca3/likes.svg?style=flat)](https://juejin.im/entry/58dca9212f301e0062f8cca3/detail)

# ParallaxRecyclerView

A RecyclerView with parallax folding effect.

![](/images/ParallaxRecyclerView.gif)

# Usage

**Add the dependencies to your gradle file:**

```javascript
dependencies {
    compile 'com.southernbox:ParallaxRecyclerView:1.0.0'
}
```
**In the layout file, replace the RecyclerView with ParallaxRecyclerView:**

```xml
<com.southernbox.parallaxrecyclerview.ParallaxRecyclerView
    android:id="@+id/rv"
    android:layout_width="match_parent"
    android:layout_height="match_parent" />
```