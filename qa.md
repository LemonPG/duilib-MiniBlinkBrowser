# 常见问题

1. 为什么```TAB```键无法使用？

    其实不是```TAB```键不能使用，而是```TAB```键被```DuiLib```拦截用来在```DuiLib```控件间跳转，你需要在窗口类中处理```TAB```键的消息。

2. 应用必须携带```node.dll```文件吗？

    可以将```node.dll```打包到资源文件中，再修改```wke.h```中初始化相关的代码，从内存中加载```node.dll```。