# ABPlayerHTML5*ABPlayerHTML5* is a sub project of ABPlayer. By porting the core classes neededfor comments in the ABPlayer project to JS, ABPlayerHTML5 attempts to achieve a simple but highly adaptable comment engine embeddable as HTML5.## Current StatusABPlayerHTML5 currently can work with color, size, movement, 3d and opacity properties concerning comments and by default supports scrolling, top, bottom, reverse and fixed position comments. ABPlayerHTML5 is built to be compatible across multiple browsers and supports current versions of Chrome (25+), Firefox(24+), Safari and Internet Explorer (9+). We use a very limited set of features and try not to use any HTML5 or CSS3 hacks.We have moved the main line into the **old** and will be actively developingthe simplified extensible player.### DemoTo test out on your browser, try our [demo](http://jabbany.github.io/ABPlayerHTML5/build).**NOTE** : Support for H.264 is not readily available on all versions of Firefox. For best results when deploying, try to use a combined H.264 with webm. CommentCoreLibrary, our display library, works best with webkit based browsers as it is developed and tested mainly on Google Chrome. It is also periodically tested on Firefox and Internet Explorer to maintain high compatibility. Don't bother trying with anything that does not support HTML5. For versions of IE below 7, this does not work at all.**NOTE** : Due to current optimization problems comments may lag significantly if you have too many DOM elements on the page. More specifically the if you have the comment list open (as it is a dom table that contains many thousands of cells) in the old version, you will experience severe lagging. Switch over to the settings tab to make comment flow more fluid.### MobileABPlayerHTML5 is also designed to work with mobile devices allowing swipe gestures and enhanced display. **NOTE** : When using in iOS versions for iPhone & iPod, embedded playback is not supported so there will be no comments displayed as the video is played inthe system's player. For iPad and OS X, Safari allows inline videos so there is no problem.## CommentCoreLibraryABPlayer employes a compiled version of CommentCoreLibrary. If you are only interested in the implementation for danmaku comments, please move on to [CommentCoreLibrary](https://github.com/jabbany/CommentCoreLibrary)## DocumentationFull English documentation has yet to be released, though you may use Google Translate or any similar translation service to get insights into inner workingsby translating the Chinese documentation. I will try to provide documentation inboth languages.# 中文## ABPlayerHTML5？ABPlayerHTML5是一个ABPlayer的子项目。通过把ABPlayer的核心弹幕类重写成JS来实现一个简单但是能高度整合HTML5的原生弹幕播放控件。目前我们支持移动端和桌面端。## 项目状态目前项目支持弹幕的颜色、大小、轨迹运动和透明度属性，同时默认支持：滚动，顶部，底部，逆向和定位弹幕。目前可以完整的实现，还原所有二维运动弹幕和多数三维运动弹幕。为了简便，我们不支持代码弹幕，在近期也不会支持的。本项目主线包括一个简单的播放器界面和一个和Bilibili联通的API端口（jslib/mottobilibili.js）。原版的含弹幕列表的播放器將被放置在 old 文件夹中以供参考。新版的简单播放器将会是研发的重点指向。如果你对项目的效果感兴趣，请[戳这里](http://jabbany.github.io/ABPlayerHTML5/build)来观看本项目在你浏览器下的效果。**注意** 由于缺乏H.264解码器支持， 某些版本Firefox下无法观看一些测试Demo。如果你的浏览器不支持HTML5就更不要尝试了。**注意2** 由于优化问题，旧版播放器在弹幕列表开放时可能导致弹幕播放非常卡，请切换到播放器设置标签。# LicenseCopyright (c) 2014 Jim Chen (http://kanoha.org/), under the [MIT license](http://www.opensource.org/licenses/mit-license.php).