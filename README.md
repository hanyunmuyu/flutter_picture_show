# flutter_picture_show

A new Flutter application.

## Getting Started

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).

[github地址](https://github.com/hanyunmuyu/flutter_picture_show)


添加依赖
```

dependencies:
  flutter:
    sdk: flutter

  cached_network_image: ^0.5.0

```

用法：

```

  String img = 'http://pic1.win4000.com/wallpaper/2018-01-13/5a59bb362eb18.jpg';
  String img1 =
      'http://pic1.win4000.com/wallpaper/2018-08-30/5b878eec0d4cf.jpg';

PictureShow(
          picList: [
            img,
            img1,
            img,
            img1,
            img1,
            img,
          ],
        )

```


!['插图'](Screenshot_1542963454.png)

!['插图'](Screenshot_1542963645.png)
