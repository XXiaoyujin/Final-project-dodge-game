# FPGA FINAL PPROJECT

## Authors : 109321012, 109321018

#### Input Output unit:<br>

* 8x8 LED 矩陣，用來顯示初始畫面。<br>
* 七段顯示器用來計分。<br>
* LED陣列用來顯示血條<br>
<img src="https://github.com/XXiaoyujin/Repository/blob/main/271738680_469284888144783_1152397442109072666_n.jpg" width="300"/><br>
* 過關後顯示V<br>
<img src="https://github.com/XXiaoyujin/Repository/blob/main/270478707_1602324516771563_1154833053520341710_n.jpg" width="300"/><br>
* 血條沒了之後顯示OVER<br>
<img src="https://github.com/XXiaoyujin/Repository/blob/main/270758475_329276382400550_1266349717002691878_n.jpg" width="300"/><br>


#### 功能說明:<br>
躲避上下左右不同顏色的物體。得到一定分數過關或失去血條失敗。<br>

#### 程式模組說明:<br>
module doge_game(output reg [7:0]position_R//紅燈, position_B\\藍燈, position_G\\綠燈, output reg [2:0]S\\控制燈亮在第幾行,output reg touch\\上下左右物體與player碰撞, input CLK, Clear,up\\控制上,down\\控制下,right\\控制右,left\\控制左,output reg A,B,C,D,E,F,G\\顯示七段顯示器,output reg [7:0]b\\LED陣列代表血條,output reg COM1,COM2,COM3,COM4\\七段COM,output reg En\\8*8 ENABLE,output reg beep\\蜂鳴器);

#### demo video:
<<a href="https://drive.google.com/file/d/1nLneBhWzplRThr9KScHGHqeY99jctkxI/view?usp=sharing" title="Demo Video1"><img src="https://github.com/XXiaoyujin/Repository/blob/main/271539886_473859630795939_9043617664230681628_n.jpg" alt="Demo Video" width="300"/></a>
<<a href="https://drive.google.com/file/d/1TrK-0UfrPCgodOJC6Pg3BTMHljn6qdNF/view?usp=sharing" title="Demo Video"><img src="https://github.com/XXiaoyujin/Final-project-dodge-game/blob/main/270322726_1302410663606503_2230219931829089542_n.jpg" alt="Demo Video2" width="300"/></a>

