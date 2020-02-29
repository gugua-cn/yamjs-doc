# YamJs 是什么？

YamJS ![](https://img.shields.io/badge/yamjs-0.2.5-brightgreen.svg)受vue和react启示，结合现在的趋势，成为一个向html看齐的组件编写基类，让你的组件不受框架的约束，达到即写即用，完美结合vue，react等框架，编写出来的组件贴近html原生用法；

yamjs是使用jsx语法去编写组间的，所以在写法上和react类似；后期会根据需要去完善jsx语法的编写方式。

借助webComponents渲染机制来渲染组件标签，兼容非webComponents模式渲染；

它的特点在于：

|                         兼容                         |                             干净                             |                             小巧                             |                 自驱动                 |
| :--------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------: |
| 不惧你的使用什么技术栈，都可以使用，区别在方法传递上 | 改基类只有标签渲染的主程序，保留了插件扩展功能，其他的例如state，router，ajax，animate...都是单独的插件根据需要添加； | gzip后只有12kb左右；若是去除一些提示信息，也就只有gzip后也就11kb左右； | 使用时只需填写标签即可，无需手动挂在； |

* 兼容：不惧你的使用什么技术栈，都可以使用，区别在方法传递上

* 干净：改基类只有标签渲染的主程序，保留了插件扩展功能，其他的例如state，router，ajax，animate...都是单独的插件根据需要添加；

* 小巧：gzip后只有12kb左右；若是去除一些提示信息，也就只有gzip后也就11kb左右；

* 自驱动：使用时只需填写标签即可，无需手动挂在；

*目前编写只能用构建工具去构建(yam-cli)*