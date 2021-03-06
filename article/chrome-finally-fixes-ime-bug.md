```meta
{
    "title": "Chrome 终于修复了高 DPI 下 IME 漂移的 bug",
    "date": "Thu Apr 20 2017 13:47:15 GMT+0800",
    "tags": [ "Linux" ]
}
```

今天，北京时间 2017 年 4 月 20 日，Chrome for Linux 浏览器更新了 `58.0.3029.81` 版本。此次更新修复了一个陈年旧 bug ：在 HiDPI 下输入法定位漂移的问题。相信高 DPI Linux 用户都会有亲身体会，而且基于 Chromium 的 Electron 应用也会有这个问题。现在这个 bug 终于被修复了，喜大普奔！接下来就坐等 Electron 同步最新的 Chromium 源码，皆大欢喜了！！！

![喜大普奔](https://rocka.me/static/img/877509-20170420135244352-1206956544.png)

而在修复之前，输入法定位逻辑是这样的（Chrome已经更新，姑且拿 Typora 来做演示）：

![buggy IME](https://rocka.me/static/img/877509-20170420140245087-1106572292.png)

可以看到输入焦点与 IME 面板的偏移，而且屏幕的 DPI 越高，偏移越厉害。

另外，这次 Chrome 的更新还用白色的菜单样式覆盖了 GTK 主题样式，有了一些 Material 的味道，就是感觉高亮颜色有些浅了，不太习惯。

![Context Menu](https://rocka.me/static/img/877509-20170420140623868-1733743167.png)

~~哈哈，就这么又水了一篇~~

最近的新文章都是在本地用 Typora 写，然后用搬瓦工的文件浏览器把 Markdown 源码贴进去...这样下去这个破博客吃枣药丸，肯定要重构一波...选型我都选好了，就用 `Koa@2` ，但至于什么时候开始呢，这个，再议，再议........
