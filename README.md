# Arduino_Tone


通过ardunio 操控蜂鸣器，执行输入的频率，演奏音乐。

================================

以 arduino uno 为例，

需要：蜂鸣器一个（10块钱包邮的游戏机喇叭，或者废旧电话听筒都可以，其它大功率设备需要接电阻）

   公对母杜邦线 2 条


接线方式 ：蜂鸣器正极接 digit 8 号。
          
   蜂鸣器负极接 digit GND 
    
================================  
    

演示方式：确定 pitchesNMN.h 和 xxx.ino 在同一文件夹，或者修改路径。

   打开电脑，用 Arduino IDE 打开需要播放的 ino 文件，
   
   【验证】无误后，执行【上传】就可以听到乐曲播放了。

================================

调音提示：

1，每次只可发出一个音节，即使同一台 Arduino 接上多个扬声器，也只能依序播放。

2，在 ino 文件里 ，找到 #include "pitchesNMN.h"这一行， 可以自己修改 pitchesNMN.h 的路径。

3，该程序包含两个 pitches 文件， pitchesNMN.h 为简谱记法。设置了 7个高音，7个中音，7个低音，和5个倍低音，可自行修改； pitches12ET.h 为十二平
均律设定，可选范围更大，不过因为蜂鸣器频率范围，建议设定在 330Hz~4000HZ 以内。






=================================


目前更新的曲子：

yingtixu ..........莺啼序 

yihonglian.........忆红莲
