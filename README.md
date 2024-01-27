# officeAddinDev
## yo office报错
Unable to download project zip file for "https://github.com/OfficeDev/Office-Addin-TaskPane-JS/archive/yo-office.zip".
Error: connect ETIMEDOUT 20.205.243.166:443

解决方法：

在 https://ping.chinaz.com/ 站长工具中ping github.com

挑选可以ping通的ip加入到localhost中。例如德国的ip:140.82.121.3.

## npm一直卡在sill idealTree buildDeps的步骤

中断任务。然后按照提示手动安装：

Running npm install for you to install the required dependencies. If this fails, try running the command yourself.

不适用npm命令，而是用 cnpm install来替代。


## 给GIT设置proxy

git config --global http.proxy socks5://127.0.0.1:1080

## 入门示例
代码解释详见：

[教程：创建 Excel 加载项](https://learn.microsoft.com/zh-cn/office/dev/add-ins/tutorials/excel-tutorial)。

## Excel JavaScript 对象模型示例

文档详见：[Excel 加载项中的 Excel JavaScript 对象模型](https://learn.microsoft.com/zh-cn/office/dev/add-ins/excel/excel-add-ins-core-concepts)。