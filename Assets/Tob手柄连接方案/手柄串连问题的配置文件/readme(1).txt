一、配置文件地址：
1.SD卡根目录ControllerConfig/hmbirdsn.pre
2.本地存储根目录ControllerConfig/hmbirdsn.pre
3.可更换2D提示背景图片 ControllerConfig/background.png

注：以上都为固定格式

二、配置文件格式
sn:B0F7            （四位mac号）
overtime:60        （单位为s）
notification：true （或者false，true为弹出系统2D提示，false为不弹出）
冒号和前后都不包含空格



三、信息提示以Android广播形式发出

Action为：com.picovr.hmbird.connect.message
获取参数：
         从intent中直接获取信息，
              key值为：data
              value为：code码 ：msg信息
Code信息为三种：
		  1. code值为 11 表示 搜索超时
		  2. code值为 14 表示 连接超时
		  3. code值为 10 表示 无配置文件（此时没有2D界面提示）
		  4. code值为 1  表示 连接成功

