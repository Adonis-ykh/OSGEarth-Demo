关于QSS：
1.TotalQSS中包含了大部分控件的属性自定义，如需要更改哪些样式效果，直接找到相关控件，修改TotalQSS，然后引用这个QSS即可。
2.请勿把一个QSS复制多个，然后再在新复制上的QSS上修改！（会导致冗余！）
3.如果想设定的样式不是全局通用的，而是特定地方的特定显示，可参考QSS内设置，利用指定对象名的方法单独设置（注意，变量命名必须要具有独特性，避免重名出现误设置！）
4*.如样式设置过于繁杂，放到一个文件中显得非常庞大，可以单独新建一个QSS具体对某一个控件进行详细设计，必须是单独一个控件，引用时对多个文件同时引用即可。（该点在大部分情况下不需要）