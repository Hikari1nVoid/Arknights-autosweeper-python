# Arknights-autosweeper-python

一个半自动刷关器，使用python瞎编且需要配合adb一起食用。
目前仅为单设备版，同时连接多个Android设备将会报错。
多设备版在鸽。
不支持IOS设备。
##系统要求
已安装好adb并配置环境变量。
或者丢一份adb.exe至程序同一目录下。
Win10下已通过测试，Linux/MacOS暂无测试计划。
##用法
 直接启动本程序，第一次使用将会尝试生成配置文件，如需在使用后生成新的配置文件请删除目录下的config.ini
 需要收集模拟点击的坐标数据，请打开开发者模式的指针位置选项。
action key:关卡所在按钮坐标
start key：开始行动按钮所在坐标
请注意，由于每次关卡通关/失败后关卡位置会回到屏幕正中，请初始化时将关卡图标移动至屏幕中央再记录坐标。

初始化完成后将会尝试启动，输入通关时间(单位：秒)与刷关次数。
*本程序不负责代做作业，仅负责代理指挥。*
*对于超出理智值的刷关请求，本程序将无法运作，如造成博士的损失，概不负责。*

##已知问题
部分第三方ROM(如MIUI)针对adb模拟点击进行了额外的控制，如使用该类型ROM请在开发者选项中开启**adb调试(安全选项)**
**USB调试与USB调试(安全选项)并非同一选项！！**



