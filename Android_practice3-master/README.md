利用 Intent来启动Activity有很多种方法，用带有Action或Category属性的方法都能实现。但是当我创建了第二个Activity之后，我的AndroidManifest.xml里面并没有为我的第二个Activity创建Action和Category属性。然后在隐式启动拨打电话的时候，我在.xml文件中添加电话权限的时候放错了位置，放在了ACtivity里面了，结果调试了半天也不知道错在哪儿了，最后把位置弄好才终于完成。