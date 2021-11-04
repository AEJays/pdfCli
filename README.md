# PDF转换工具

### 工具说明

这个工具可以用于转换本地的HTML文件和网站成PDF

### 命令说明

./app.sh (-I) (-P 端口) (-S) (-U) (-N pdf名称) (-B 转换地址) (-T) (-H) (-L)

-H：查看帮助

./app.sh -H

-I：初始化工具

./app.sh -I

-P：更改工具端口（如果端口冲突，先更改工具端口，再打开工具）

./app.sh -P 8000

-S：打开工具

./app.sh -S

-U：更新工具

./app.sh -U

-T：生成pdf 并自动存放入pdf文件夹

./app..sh -T

-N：设定pdf名称 默认pdf名称为defaultPdf 需要配合 -T 使用

./app.sh -N newPdf -T

-L：查看今天的log

./app.sh -L

-B：设定地址url 可为本地dist 也可为网络链接 需要配合-T 使用

./app.sh -B http://www.baidu.com -T

-T -N -B 的综合应用

./app.sh -N newPdf -B http://www.baidu.com -T

注意：默认的 -N 名称是defaultPdf 默认 -B 的地址是http://www.baidu.com -B 的地址可以使用绝对路径 或相对于pdf-cli目录的路径
