# Hello，这是我的第一个小Demo项目

## BB8球型机器人

目前长这样子

![BB8球形机器人_01](./../../Markdown博客Blog/Typora_image/BB8球形机器人_01.png)

准备上个L3级别的辅助驾驶功能
## 软件部分
把参照Zephyr的集成方式，把RT-Thread高效的集成到openEuler Embedded中，要有MICA，可以baremetal的方式（可以不用虚拟化） https://gitee.com/openeuler/yocto-meta-openeuler/tree/master/rtos/meta-rtthread 之前的工作基础， 对于工具链可以参照 https://gitee.com/openeuler/yocto-meta-st/tree/master/meta-st-stm32mp/recipes-devtools/gcc-arm-none-eabi 集成好之后，刷新一下文档，后面可能还要写个小文章，需要往openEuler和RT-Thread的公众号上推 同步的，开始为第2个任务准备：

研究vsomip的代码，
集成到openEuler Embedded中的，并准备相应的文档和demo
