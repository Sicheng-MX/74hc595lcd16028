# 74hc595lcd16028
突发奇想所改，还有很多重复累赘...
串2个74hc595，通过3引脚驱动,LCD1602，8位工作模式
PB(13,14,15)为默认脚(太懒未写定义脚的函数)
ST_CP--PB13；
SH_CP--PB14;
DS-----PB15;

Q0--RS;
Q1--RW;
Q2--E;

Q3--D0;
Q4--D1;
Q..-D..;
