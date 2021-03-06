# 面板

**Kibana** 仪表板由面板(`panels`)块组成。面板在行中可以起到很多作用，不过大多数是用来给一个或者多个请求的数据集结果做可视化。剩下一些面板则用来展示数据集或者用来为使用者提供插入指令的地方。

面板可以很容易的通过 Kibana 网页界面配置。为了了解更高级的用法，比如模板化或者脚本化仪表板，这章开始介绍面板属性。你可以发现一些通过网页界面看不到的设置。

每个面板类型都有自己的属性，不过有这么几个是大家共有的。

## span

一个从 1-12 的数字，描述面板宽度。

## editable

是否在面板上显示编辑按钮。

## type

本对象包含的面板类型。每个具体的面板类型又要求添加新的属性，具体列表说明稍后详述。

-----------------------

## 译作者注

官方文档中只介绍了各面板的参数，而且针对的是要使用模板化，脚本化仪表板的高级用户，其中有些参数甚至在网页界面上根本不可见。

为了方便初学者，我将在每个面板的参数介绍之后，自行添加界面操作和效果方面的说明。
