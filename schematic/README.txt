PCB分为3层：
底层电源板支持5v舵机、9v摄像头图传供电，
中层为主控板带5v系统供电，顶层为标识盖板；
pwm使用gh1.25接线座引出到底层接口。

主控：stm32f405rgt6
IMU：icm-42688
气压计：spl-06
OSD：at7456e
供电：mp9943 x 2，mp9447 x 1
存储：tf卡
舵机：10路PWM输出
串口：6路uart        
    
How to use：

At editor, open the document via: Top menu - File - Open - EasyEDA... , and select the json file, then open it at the editor, you can save it into a project.

如何使用：

打开编辑器，通过：顶部菜单 - 文件 - 打开 - 立创EDA... ，选择 json 文件打开在编辑器，你可以保存文档进工程里面。