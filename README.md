# notebook

## 下载youtube视频，最佳质量，使用ffmpeg合并

```
youtube-dl.exe --proxy 127.0.0.1:1080 -f "bestvideo+bestaudio" --ffmpeg-location "location of ffmpeg"  https://www.youtube.com/videourl
```

## vmware虚拟机使用主机代理

[该链接6楼](https://www.v2ex.com/t/581584)

1. 虚拟机设置-网路配置里，选择桥接模式，勾上复制物理网络连接状态；
2. 设置你的代理（右键图标，菜单里找到）允许其它设备连入；
3. 直接在虚拟机里设置代理，IP 填入你物理机的 IP地址，以及你的代理端口；

# [我的读书笔记](https://github.com/kevingbwu/my_notebook)