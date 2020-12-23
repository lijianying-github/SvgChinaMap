# 基于svg文件绘制中国地图

## 已实现功能
1. svg解析以及地图绘制
1. 地区区域封装以及点击高亮
1. 区域颜色层级展示封装实现


通过svg文件绘制中国地图
## 涉及技术
* xml文件解析
* svg 路径信息与Path转换
* Canvas绘制path
* 自定义控件手势处理
* RxJava 异步任务处理

[APK下载](https://raw.githubusercontent.com/ljying/ChinaMap/master/screenshot/China_Map.apk)

## 使用方式
```xml
<com.nemo.mapdemo.map.ChinaMapView
        android:id="@+id/view_map"
        android:layout_width="match_parent"
        android:layout_height="wrap_content" />
```

## 效果图
![效果图](https://github.com/lijianying-github/SvgChinaMap/blob/master/screenshot/effect.png)



