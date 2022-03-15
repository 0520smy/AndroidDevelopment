## lab03——Homework

1913182-邵敏依

#### 作业要求：

1. 向 TitleFragment 的布局中添加 Rules 按钮和 About 按钮，当用户点按 Rules 或 About 按钮时，应用会导航到 RulesFragment 或 AboutFragment 。
2. 在 RulesFragmen t和 AboutFragment 的布局中添加一个可使应用导航到 GameFragment 的 Play 按钮。

#### 问题与解决：

在 RulesFragment.kt 和 AboutFragment.kt 增加 DataBinding 时，我发现代码会标红报错

![b3b73929f4adfd5865397fc5e2072b7e2a0c6eb5.png (1524×802) (hdslb.com)](https://i0.hdslb.com/bfs/album/b3b73929f4adfd5865397fc5e2072b7e2a0c6eb5.png)

尝试多次之后，我修改了 fragment_rules.xml 和 fragment_about.xml ，将原先的 ScrollView 放入 layout 中

![d925faa28f095e4eee7e2f618d796ce82153f8d3.png (1420×870) (hdslb.com)](https://i0.hdslb.com/bfs/album/d925faa28f095e4eee7e2f618d796ce82153f8d3.png)

发现代码不报错了

![ad416bbf8709c35a43cf7a5016f5dbb91f4768ad.png (1524×934) (hdslb.com)](https://i0.hdslb.com/bfs/album/ad416bbf8709c35a43cf7a5016f5dbb91f4768ad.png)

