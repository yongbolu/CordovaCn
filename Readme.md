#CordovaCn 提交规则 Ver 1.0<br>
01基础知识 主要提供官方使用手册相关内容(以Android和iOS为主)<br>
02插件使用 主要提供各种插件的使用说明类文章，比如插件Readme的翻译以及api使用经验<br>
03代码分享 大家分享自己的各种有意义和复用价值的代码(如果是公司生产级别代码请注意知识产权保护)<br>
04常见问题及解决办法 大家分享在Cordova开发过程中遇到的各种坑以及解决办法<br>
05学习和参考资料(Blog or Referance) 分享网络上Cordova相关资料<br>
06imgs     用于提交Readme关联的图片<br>
<br>
#####所有站内信息一定要提交后在本页添加一个link到你对应的*.md文件上或者是Demo首页
本站内容提交方式    标题 link(@作者XXX)<br>
本站外内容提交方式  标题 link(转@作者XXX)<br>
Example: <br>
01.[GitHub上README.md教程](http://blog.csdn.net/kaitiren/article/details/38513715) (转@作者kaitiren)<br>
02.[Github简要指南](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem&Experience)/03.Git%E7%AE%80%E8%A6%81%E6%8C%87%E5%8D%97.md) (@作者Ryouaki)<br>
<br>
##01基础知识<br>
01.[Cordova介绍](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/01.What-is-Cordova.md) (@作者ShangXinbo)<br>
02.[Platform Support(平台支持)](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/02.Platform%20Supports(%E5%B9%B3%E5%8F%B0%E6%94%AF%E6%8C%81).md) (@作者Ryouaki)<br>
03.[Install Cordova(Cordova的安装)](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/03Install%20Cordova(Cordova%E7%9A%84%E5%AE%89%E8%A3%85).md) (@作者Ryouaki)<br>
04.[Cordova-Cli(Cordova命令行)](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/04.Cordova%20Command-Line-Interface(Cordova%E5%91%BD%E4%BB%A4%E8%A1%8C).md) (@作者Ryouaki)<br>
05.[config.xml Guide(config.xml指南)](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/05.config.xml%20Guide(config.xml%E6%8C%87%E5%8D%97).md) (@作者Ryouaki)<br>
06.[Customize Icons(自定义图标)](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/06.Customize%20Icons(%E8%87%AA%E5%AE%9A%E4%B9%89%E5%9B%BE%E6%A0%87).md) (@作者Ryouaki)<br>
07.[Event(事件)](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/07.Event(%E4%BA%8B%E4%BB%B6).md) (@作者Ryouaki)<br>
08.[Plugin.xml Guide(Plugin配置文件指南)](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/08.Plugin.xml%20Guide(Plugin%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6%E6%8C%87%E5%8D%97).md) (@作者Ryouaki)<br>
09.[Plugin Development Guide(插件开发指南)](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/09.Plugin%20Development%20Guide(%E6%8F%92%E4%BB%B6%E5%BC%80%E5%8F%91%E6%8C%87%E5%8D%97).md) (@作者kebenxiaoming)
<br>
10.[Android Plugins(Android插件开发)](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/10.Android%20Plugins(Android%E6%8F%92%E4%BB%B6%E5%BC%80%E5%8F%91).md) (@作者kebenxiaoming)<br>
11.[iOS Plugins(iOS插件开发)](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/11.iOS%20Plugins(iOS%E6%8F%92%E4%BB%B6%E5%BC%80%E5%8F%91).md) (@作者Ryouaki)<br>
12.[Storage](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/12.Store(%E5%AD%98%E5%82%A8).md) (@作者Ryouaki)<br>
13.[Hooks](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/13.hooks.md) (@作者Ryouaki)<br>
14.[Android WebViews](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/14.Android%20Webview(Android%E5%B5%8C%E5%85%A5%E5%BC%8FWebview).md) (@作者Ryouaki)<br>
15.[iOS WebViews](https://github.com/CordovaCn/CordovaCn/blob/master/01%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86(Basic%20Knowledge)/15.iOS%20Webview(iOS%E5%B5%8C%E5%85%A5%E5%BC%8FWebview).md) (@作者Ryouaki)<br>

#02插件使用<br>
00.[自定义插件](https://github.com/CordovaCn/CordovaPluginsDemo/blob/master/cordova-plugin-custom/README.md) (@作者Ryouaki)<br>
01.[Battery Status 使用说明(电源状态)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/01.cordova-plugin-battery-status.md) (@作者Ryouaki)<br>
02.[Camera 使用说明(照相机)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/02.cordova-plugin-camera.md) (@作者Ryouaki)<br>
03.[Console 使用说明(日志)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/03.cordova-plugin-console.md) (@作者Ryouaki)<br>
04.[Contacts 使用说明(通讯录)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/04.cordova-plugin-contacts.md) (@作者Ryouaki)<br>
05.[Device 使用说明(设备信息)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/05.cordova-plugin-device.md) (@作者Ryouaki)<br>
06.[Motion 使用说明(速度传感器)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/06.cordova-plugin-device-motion.md) (@作者Ryouaki)<br>
07.[Device Orientation 使用说明(方向传感器)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/07.cordova-plugin-device-orientation.md) (@作者Ryouaki)<br>
08.[Dialogs 使用说明(消息提示框)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/08.cordova-plugin-dialogs.md) (@作者Ryouaki)<br>
09.[File 使用说明(文件系统)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/09.cordova-plugin-file.md) (@作者Ryouaki)<br>
10.[File Transfer 使用说明(文件上传下载)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/10.cordova-plugin-file-transfer.md) (@作者Ryouaki)<br>
11.[Geolocation 使用说明(定位)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/11.cordova-plugin-geolocation.md) (@作者Ryouaki)<br>
12.Globalization<br>
13.Inappbrowser<br>
14.Media<br>
15.Media Capture<br>
16.[Network Information 使用说明(网络状态)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/16.cordova-plugin-network-information.md) (@作者Ryouaki)<br>
17.[Splashscreen 使用说明(启动画面)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/17.cordova-plugin-splashscreen.md) (@作者Ryouaki)<br>
18.[Vibration 使用说明(振动)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/18.cordova-plugin-vibration.md) (@作者Ryouaki)<br>
19.[Statusbar 使用说明(状态栏)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/19.cordova-plugin-statusbar.md) (@作者Ryouaki)<br>
20.[Whitelist 使用说明(白名单)](https://github.com/CordovaCn/CordovaCn/blob/master/02%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8(About%20Plugin)/20.cordova-plugin-whitelist.md) (@作者Ryouaki)<br>
21.[Cordova-Plugin-Photos Demo(获取多图插件)](https://github.com/ryouaki/Cordova-Plugin-Photos/blob/master/README.md) (@作者Ryouaki)<br>
<br>
##03代码分享<br>
*请在CordovaCn创建单独的Repository然后将连接Link到这里*<br>
00.[自定义插件Demo](https://github.com/CordovaCn/CordovaPluginsDemo) (@作者Ryouaki)<br>
01.[Battery Status Demo](https://github.com/CordovaCn/CordovaPluginsDemo) (@作者Ryouaki)<br>
02.[Camera Demo](https://github.com/CordovaCn/CordovaPluginsDemo) (@作者Ryouaki)<br>
03.[Console Demo](https://github.com/CordovaCn/CordovaPluginsDemo) (@作者Ryouaki)<br>
04.[Contacts Demo](https://github.com/CordovaCn/CordovaPluginsDemo) (@作者Ryouaki)<br>
05.[Device Demo](https://github.com/CordovaCn/CordovaPluginsDemo) (@作者Ryouaki)<br>
20.[Whitelist Demo(简要Demo)](https://github.com/CordovaCn/CordovaPluginsDemo) (@作者Ryouaki)<br>
21.[Cordova-Plugin-Photos Demo(获取多图插件)](https://github.com/ryouaki/Cordova-Plugin-Photos) (@作者Ryouaki)<br>
22.[一个简单的前后台通信演示程序(基于JQuery+Bootstrap)](https://github.com/ryouaki/Mobile-Module-Js) (@作者Ryouaki)<br>
<br>
##04常见问题及解决办法<br>
01.[iOS域访问限制(statusCode==0)](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem&Experience)/01.iOS%E5%9F%9F%E8%AE%BF%E9%97%AE%E9%99%90%E5%88%B6(Ajax%E8%AF%B7%E6%B1%82%E8%BF%94%E5%9B%9EstatusCode==0).md) (@作者Ryouaki)<br>
02.[长按屏幕引起的提示菜单或者提示框问题](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem%26Experience)/02.%E9%95%BF%E6%8C%89%E5%B1%8F%E5%B9%95%E5%BC%95%E8%B5%B7%E7%9A%84%E6%8F%90%E7%A4%BA%E8%8F%9C%E5%8D%95%E6%88%96%E8%80%85%E6%8F%90%E7%A4%BA%E6%A1%86%E9%97%AE%E9%A2%98.md) (@作者Ryouaki)<br>
03.[Git简要指南](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem%26Experience)/03.Git%E7%AE%80%E8%A6%81%E6%8C%87%E5%8D%97.md) (@作者Ryouaki)<br>
04.[App内部打开外部连接跳转浏览器的解决办法](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem%26Experience)/04.App%E5%86%85%E9%83%A8%E6%89%93%E5%BC%80%E5%A4%96%E9%83%A8%E8%BF%9E%E6%8E%A5%E8%B7%B3%E8%BD%AC%E6%B5%8F%E8%A7%88%E5%99%A8%E7%9A%84%E8%A7%A3%E5%86%B3%E5%8A%9E%E6%B3%95.md) (@作者杭州-毛毛熊)<br>
05.[Android调试方法](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem&Experience)/05.Android%E8%B0%83%E8%AF%95%E6%96%B9%E6%B3%95.md) (@作者Ryouaki)<br>
06.[iOS调试方法](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem%26Experience)/06.iOS%E8%B0%83%E8%AF%95%E6%96%B9%E6%B3%95.md) (@作者Ryouaki)<br>
07.[打不开Chrome Inspector，一直显示白屏](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem%26Experience)/07%E6%89%93%E4%B8%8D%E5%BC%80Chrome%20Inspector%EF%BC%8C%20%E4%B8%80%E7%9B%B4%E6%98%BE%E7%A4%BA%E7%99%BD%E5%B1%8F.md) (@作者Vaenow)<br>
08.[XCode 7.X中Cordova:CDVPlugin.h file not found](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C%28Problem&Experience%29/08.XCode%207.X%E4%B8%AD%3CCordova:CDVPlugin.h%3E%20file%20not%20found.md) (@作者Ryouaki)<br>
09.[App运行后屏幕分辨率异常](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem%26Experience)/09.App%E8%BF%90%E8%A1%8C%E5%90%8E%E5%B1%8F%E5%B9%95%E5%88%86%E8%BE%A8%E7%8E%87%E5%BC%82%E5%B8%B8.md) (@作者Ryouaki)<br>
10.[iOS设备@media匹配(iOS)](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem%26Experience)/10.iOS%E8%AE%BE%E5%A4%87%40media%E5%8C%B9%E9%85%8D(iOS).md) (@作者Ryouaki)<br>
11.[No SIM Card Installed显示2次(iOS)](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem%26Experience)/11.No%20SIM%20Card%20Installed%20Twice(iOS).md) (@作者Ryouaki)<br>
12.[读Cordova源代码，看看是为什么prepare/build你修改的代码](https://github.com/CordovaCn/CordovaCn/blob/master/04%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E5%8F%8A%E8%A7%A3%E5%86%B3%E7%BB%8F%E9%AA%8C(Problem&Experience)/12.%E8%AF%BBCordova%E6%BA%90%E4%BB%A3%E7%A0%81%EF%BC%8C%E7%9C%8B%E7%9C%8B%E6%98%AF%E8%B0%81%E5%B9%B2%E6%8E%89%E4%BA%86%E4%BD%A0%E4%BF%AE%E6%94%B9%E7%9A%84%E4%BB%A3%E7%A0%81.md) (@作者Ryouaki)<br>
<br>
##05学习和参考资料(Blog or Referance)<br>
01.[Cordova iOS4.1.0 Released](https://github.com/CordovaCn/CordovaCn/blob/master/05%E5%AE%98%E6%96%B9%E5%8D%9A%E6%96%87(Blog%20from%20Cordova)/02-Mar-2016%20Cordova%20iOS%204.1.0%20Released.md) (@作者Ryouaki)<br>
02.[JavaScript学习资料](http://www.runoob.com/js/js-tutorial.html) (转@菜鸟教程)<br>
03.[CSS学习资料](http://www.runoob.com/css/css-tutorial.html) (转@菜鸟教程)<br>
04.[CSS3学习资料](http://www.runoob.com/css3/css3-tutorial.html) (转@菜鸟教程)<br>
05.[HTML学习资料](http://www.runoob.com/html/html-tutorial.html) (转@菜鸟教程)<br>
06.[HTML5学习资料](http://www.runoob.com/html/html5-intro.html) (转@菜鸟教程)<br>
07.[Ionic学习资料](http://www.runoob.com/ionic/ionic-tutorial.html) (转@菜鸟教程)<br>
<br>
----------------------------Notes-------------------------<br>
CordovaCn官方QQ群:38840127
