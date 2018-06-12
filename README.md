相册查看

图片加载采用ImageLoader框架，图片展示采用PhtotoView框架

ImageLoader框架的好处

1、多线程下载图片，图片可以来源于网络，文件系统，项目文件夹assets中以及drawable中等

2、支持随意的配置ImageLoader，例如线程池，图片下载器，内存缓存策略，硬盘缓存策略，图片显示选项以及其他的一些配置

3、支持图片的内存缓存，文件系统缓存或者SD卡缓存

4、支持图片下载过程的监听

5、根据控件(ImageView)的大小对Bitmap进行裁剪，减少Bitmap占用过多的内存

6、较好的控制图片的加载过程，例如暂停图片加载，重新开始加载图片，一般使用在ListView,GridView中，滑动过程中暂停加载图片，停止滑动的时候去加载图片

7、提供在较慢的网络下对图片进行加载

<img src="https://github.com/FrankdeBoers/AndroidAlbum/blob/master/screenshot/androidalbum.gif" width="50%">
