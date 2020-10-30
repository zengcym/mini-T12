# Mini T12焊台-基于Arduino平台-Atmege328p-au
## 2020-10-30 V0.93功能完善99%
* 动态PID
* 取消电流传感器
* 主界面取消电流显示改为显示PWM百分比
* 设置菜单增加曲线拟合校准
* 休眠计时改用定时器2
* 新增息屏显示环境温度，无加热无操作3分钟后进入
* 开机提示音和开机画面
* 休眠时自动保存当前设置温度到eeprom
* 待机功耗8.8ma 息屏待机功耗6.4ma
### 观看视频 https://www.bilibili.com/video/BV1vf4y1B7Xa?p=2
### PCB11月验证最终板后放出
#### 按键功能定义
* 长按操作（5下短音最后1下长音）
  * 主界面，进入设置界面
  * 其他界面，退出至主界面
* 双击操作（2下短音）
  * 主界面，加热或停止状态切换
  * 其他界面，无
* 单击（1下短音）
  * 主界面，无
  * 设置界面，进入二级菜单
  * 二级菜单，切换数值更改选中状态，或确认更改数值，无选框状态则退出至一级菜单
#### 菜单选项
* PID
  * P
  * I
  * D
* 休眠
  * 休眠时间
  * 休眠温度
* 屏幕
  * 屏幕亮度
  * 屏幕方向
  * 编码器方向
* 电源
  * 基准电压
  * 电源电压
  * 低压报警
* 校准
  * 调节曲线1段温度
  * 调节曲线2段温度
  * 调节曲线2段温度
  * 调节曲线3段温度
  * 运行曲线拟合并校准曲
* 烙铁
  * 冷端补偿
  * 开机加热
  * 重置
![](https://github.com/jie326513988/mini-T12/blob/main/Picture/1.jpg)
![](https://github.com/jie326513988/mini-T12/blob/main/Picture/2.JPG)
