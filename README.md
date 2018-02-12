# LocationDebug
虚拟定位

1、用[高德地图](http://lbs.amap.com/console/show/picker)查询想要定位的经纬度，在 ViewController 里面替换对应的坐标，运行一遍，控制台打印出对应的转换后的经纬度，拷贝到 location.gpx 文件替换对应的经纬度
2、真机运行，然后选择 DeBug -> simulator location -> location, 然后把后台运行，打开企业微信，位置已经切换到模拟的。

### notice
模拟定位成功后 不需要点 stop，直接断开手机与电脑的连接，虚拟定位则会一直运行，要想恢复则需要重启手机或者用项目再运行一遍，把上面的第2步选择 Don't location
