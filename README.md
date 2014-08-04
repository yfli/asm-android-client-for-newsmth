aSM: Android Client for NewSMTH
==============================

aSM -- android上的水木清华客户端

项目介绍和使用说明
------------------------------
http://asm.zfdang.com/

下载地址
==============================
Build Date: 2014-08-04.

<a href="https://github.com/zfdang/asm-android-client-for-newsmth/raw/master/dist/aSM.apk">aSM.apk</a>

更新历史
==============================

2014-08-04:
------------------------------
1. 附件文件显示真实的文件名，不过中文没处理好

2014-08-03:
------------------------------
1. 修正了一个null pointer的bug，这样在网络不好的时候，就不会频繁crash了
2. 调整了图片缩放的实现，优先调整宽度，不再要求高度也在一屏内

2013-12-24:
------------------------------
1. 更新了IP数据库，现在用的是一个14M的大库，造成安装文件变大

2013-12-23:
------------------------------
1. revert vt100 related changes

2013-12-12:
------------------------------
1. 修复回复帖子时，app签名换行的问题

2013-12-09:
------------------------------
1. 所有版面列表的快速滚动条增加了索引
2. 同主题看帖时，也增加了快速滚动条的索引

2013-12-07:
------------------------------
1. 让asm像cterm那样支持颜色控制符等简单的ANSI控制符, by flash2

2013-12-02:
------------------------------
1. 同主题模式下，显示帖子的楼号

2013-10-04:
------------------------------
1. 帖子字体大小将控制帖子的作者、时间、正文、附件等文本

2013-08-06:
------------------------------
1. 长按GIF图片，将弹出保存图片到本地的选项
2. 退出时不再通知服务器，加快程序关闭的速度

2013-08-05:
------------------------------
1. 增加了google analytics, 统计aSM的安装情况

2013-08-01:
------------------------------
1. 优化了获取图片类型的代码，使用HEAD方法(原来使用GET)方法

2013-07-31:
------------------------------
1. 正确显示附件图片的文件类型
2. 显示GIF动画

2013-06-20:
------------------------------
1. 修正了在android 2.3上crash的问题

2013-06-13:
------------------------------
1. 在设置里可以选择全屏看图时的屏幕方向：系统默认，或者跟随重力感应

2013-05-17:
------------------------------
1. 在branch实现了允许用户手工调整收藏夹版面的功能, 没有merge到master.
下载地址：https://github.com/zfdang/asm-android-client-for-newsmth/raw/favorite/dist/aSM.apk

2013-05-15:
------------------------------
1. 全屏看图模式下，可使用音量键翻页
2. 在主题列表、帖子列表和邮件里，增加了up caret

2014-22:
------------------------------
1. fix issue 6

2013-04-05:
------------------------------
1. 修正了帖子正文中链接无法点击的问题；

2013-03-31:
------------------------------
1. 更新了aFileChooser库
2. 调整了上传附件时的布局，显示真实的文件名和文件大小，增加了上载的进度提示，返回时提示是否放弃已选择附件

2013-03-30:
------------------------------
1. 修复了一个crash的bug
2. 更新了actionbarsherlock，不知道有没有隐藏的问题

2013-03-29:
------------------------------
1. 长按帖子的操作里，增加了转寄到站内其他用户的功能
2. 查询用户信息的界面，增加了用户IP/位置信息
3. 查询用户信息的界面，增加了给用户发信的功能
4. 查询用户信息的其他一些改进

2013-03-26:
------------------------------
1. 在收藏夹界面，长按版面可将版面从收藏夹删除
2. 在版面的主题列表界面，按菜单键，可将版面加入到收藏夹
3. 小幅调整了左右划动的阈值

2013-03-25:
------------------------------
1. 修正了全屏看图的一个bug: 所有的操作（保存、查看Exif）都是基于初始的那张图

2013-03-24:
------------------------------
1. 重构了部分代码
2. 修正了全屏看图在android 4.0之前无法正常工作的bug, 使得全屏看图真的全屏了
3. 调整了帖子长按菜单的顺序，“在浏览器里打开”在匿名登录时打开m版的同主题页面
4. 全屏看图时，使用line indicator来标示当前图片的位置

2013-03-22:
------------------------------
1. 同主题模式下，在首页向右划动，返回到版面列表
2. 在设置里增加选项：左右划动，右划返回
3. 改进了升级的代码，现在可以在android 2.3下面正常工作了
4. 手势提示的文字可以在设置里取消了
5. 优化了翻页的代码, 避免了不必要的重新加载

2013-03-21:
------------------------------
1. 稍微调整了一下显示帖子时的布局，和搜索窗口的字体颜色
2. 对输入数字的编辑框，缺省打开输入法的数字输入模式
3. 在首页导读、个人收藏夹、版面列表里，允许使用音量键上下滚屏

2013-03-20:
------------------------------
1. 修正了当帖子非正常加载时，长按crash的问题
2. 限制了左划、右划的生效范围，只在同主题或者正常模式看帖子时有效
3. 修正了aSM在低版本android无法使用的问题: 获取屏幕高度时，使用旧版api
4. 修正了weibo风格下，编辑帖子crash的bug
5. 修改了编辑帖子时，正文的字体大小
6. 使用ant自动编译项目并换了release key来编译，带来的后果是这次必须把旧版的卸载了才能安装...
7. 长按帖子时，根据系统设置"触摸时震动"来决定是否震动
8. 在文章列表的界面，增加了“切换置底”的图标，将搜索图标移到了actionbar
9. 搜索帖子的界面，在上面增加了一个搜索的图标

2013-03-19:
------------------------------
1. 改善了显示IP的效果, 重构了代码
2. 修改了bug: 十大->帖子->回版面->非同主题模式->帖子无法加载的bug
3. 暂时禁掉了帖子里的超链接，因为这个会导致同主题是长按、划屏等的问题；没找到解决的办法
   同时在菜单里增加了将当前帖子“在浏览器里打开”，如果有什么东西需要点击的话，在浏览器打开吧
4. 给long click增加了震动提示
5. 改善了下载更新时的提醒


2013-03-18:
------------------------------
1. 在“关于”对话框里，增加了检测新版本的功能
2. 在全屏看图的模式下，除了长按出菜单外，使用菜单键也可以弹出菜单


2013-03-17:
------------------------------
1. 为github项目启用了定制化的域名: http://asm.zfdang.com
2. 增加了程序的使用说明: http://asm.zfdang.com/help.html
3. 一些小bug fix

2013-03-16:
------------------------------
1. 优化了加载信息的进程，防止多次加载
2. 重构了同主题时，gesture/touch/longclick listener, 使得页面上下、左右切换更顺畅
   存在一个bug:当帖子里有超链接时，长按和点击翻页都不好使。还不知道怎么fix
3. 修正了长按帖子时crash的一个bug
4. 当缓存的收藏夹为空时，从web直接下载
5. 一些代码的重构

2013-03-15:
------------------------------
1. 在非同主题显示帖子时，显示IP和位置信息

2013-03-14:
------------------------------
1. 更改了全屏看图时，图片切换的条件：即使图片处于放大状态，只要到了图片的边缘，就允许切换
2. 在主题列表时，允许使用音量键翻页

2013-03-13:
------------------------------
1. 修正了无网络时，匿名登录crash的问题
2. 修正了oRo报的一个bug:
"如果有人回复了我的帖子，然后他又删除了这个回复，这个回复在回复提醒中还在，点进去提示无法加载，出来后再看其它帖子就崩溃退出了"
3. 修正了帖子日期显示问题，现在日期和时间都有了

2013-03-12:
------------------------------
1. 更改了翻页的实现，原来是一个帖子一个帖子的翻，现在是在竖直方向上滚动95%。音量键和点击屏幕上下部的行为都改了
2. 修正了exif显示错行的问题
3. 将图片的最大放大数值从4改成12
4. 禁用hardware accelerate, 希望能避免"Bitmap too large to be uploaded into a texture exception"的错误
5. 开启了largeHeap，降低out-of-memory的问题

2013-03-09:
------------------------------
1. 优化了listview的性能，按理说滚动时会更平滑
2. 缺省使用夜间模式
3. 稍微调整了界面的padding/margin值

2013-03-08:
------------------------------
1. 同主题查看帖子时，使用音量键来翻页

2013-03-06:
------------------------------
1. 改进了全屏看图的实现方法，避免了内存不足的问题;

2013-03-05:
------------------------------
1. 改进了查看帖子里图片的方法：
1.1 点击帖子里的图片，进入全屏看图模式; 支持屏幕旋转;
1.2 双指缩放图片;
1.3 左右滑动图片，在同一帖子的不同附件之间切换(图片在未放大状态下, 否则是移动图片; 需先将图片缩小再切换);
1.4 图片左上角会提示 当前图片序号/所有图片数;
1.5 长按图片，弹出菜单，可查看图片的exif信息，或者将图片保存到SDCARD中aSM/images/;
1.6 返回键退出全屏查看模式.
2. 增加了删除自己帖子的功能(长按弹出菜单);
3. 显示exif信息时使用ScrollView，避免横屏下信息显示不全

2013-03-04:
------------------------------
1. 区分了新信和新的回复；但是现在没法检测新的@,看了一下，www2和m版的都没有@的提示，只有nform的有，等以后有机会再改吧


2013-03-01:
------------------------------
1. 增加了"微博方式"来显示同主题列表(设置中可配置，缺省打开)，by Daniel;
2. 增加了显示IP地址的功能(设置中可配置，缺省打开)，by Daniel; 由于增加了IP地址库，安装文件体积增加到了2.1M

2013-02-27:
------------------------------
1. 修正了搜索版面偶尔crash的问题;

2013-02-26:
------------------------------
1. 修正导读页面->帖子详情->回到版面->搜索->搜索结果->点击帖子 内容无法显示;
1. 将图片缓存移到SDCARD;

2013-02-25:
------------------------------
1. 全屏显示图片时，增加了显示图片EXIF信息的功能(长按弹出的菜单中);
2. 修正了搜索帖子时，"附件"选项不工作的bug;

2013-02-24:
------------------------------
1. 按两次“返回”退出；将“退出确认”的默认值改为false
2. 更新了版本信息，从manifest中读取

2013-02-23:
------------------------------
1. 修正点击状态栏notification无法打开程序的bug;
2. 更改了屏幕方向里"系统默认"的实现方法：如果用户在系统里设置了禁止旋转，则屏幕不会旋转;
3. 在帖子阅读页面开启了屏幕旋转功能;
4. 修改了全屏查看图片页面，并开启了屏幕旋转功能;
5. TouchImageView增加了长按功能

2013-02-22:
------------------------------
1. 修正无法编辑帖子的bug;
2. 全屏显示图片的时候，不缩小图片
3. 如果图片加载失败，显示“加载失败”


2013-02-21:
------------------------------
1. 搜索版面的时候，支持中文、英文的部分搜索：比如输入"米兰"，会自动提示"AC米兰"，"国际米兰";
2. 修正了原来无法搜索中英文混杂的版面(如"IT业界特快")的问题;
3. 去除了UrlImageViewHelper的in memory cache机制, 并且增加了设置下载文件最大size的接口;
4. 如果附件的数量超过8个，不再放大图片，防止内存不足;
5. 修正了设置中的2G/3G附件最大尺寸下载设置无效的bug;


2013-02-20:
------------------------------
1. 修正收藏夹版面加载的问题，原来的实现没能利用本地的缓存;
2. 修正了对帖子列表的处理，上次在标题后添加回复数量后，除了同主题模式，其他模式都会crash

2013-02-19:
------------------------------
1. 修正了分类目录的刷新，弃用了资源里缺省分类目录，第一次会自动从web加载;
2. 修改了UrlImageViewHelper库, 对图片自动缩放, 使得图片可以占用屏幕的全部宽度;
3. 增加了帖子回复数量，在标题后面的括号中显示;
4. 登录时，区分网络连接错误和认证错误;

2013-02-17:
------------------------------
1. 更新了UrlImageViewHelper库。原来附件里图片，缺省的显示大小是200X400，在高分辨率的屏幕下看起来效果不好；升级了之后，如果图片较大，可以充分利用屏幕了
2. 增加了退出是否需要确认的设置；缺省需要确认退出；
3. 在底部的工具栏中增加了夜间模式，这样可以快速切换白天、夜间模式了
4. 缺省展开了水木十大
5. 收藏夹里，首先显示“我的收藏夹”的内容并缺省展开，然后再显示最近访问的版块
