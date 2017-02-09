# JWplayer
找一个相对比较好点的播放器，国内的ckpkayer用的多，但是bug也很多，国外知名的jwplaye播放器很出名，比如慕课网使用的就是jw播放器，看了官方的文档之后简单的操作进行了记录。

``` javascript
 //具体配置参数
    jwplayer('container').setup({               //通过js调用播放器并安装到指定容器（container）内
        'flashplayer': 'jwplayer.swf',          //所依赖的falsh插件
        'image': 'jwplayer/preview.jpg',        //视频预览图片
        'file': videoRelativePath,              //所依赖的falsh插件  播放路径
        'streamer': videoBasePath,              //展示标题
        'controlbar': 'none',                   //控制条的位置（'over'）
        'width': '100%',                        //视频播放器的宽度
        'height': '100%',                       //视频播放器的高度
        'screencolor' :'#fff',                  //播放器颜色
        'repeat': "always",                      //是否重复播放
        'autostart': true                        //打开自动播放
    });


```
