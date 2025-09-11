
$$
电容: I = C\frac{\mathrm{d}u}{\mathrm{d}t},
\quad
电感: E = -L\frac{\mathrm{d}i}{\mathrm{d}t}
$$



# Buck电路

$Buck$ 是抵抗的含义, 也称降压斩波器 ( $Buck Chopper$ ).

效率高, 纹波大. 
与之对应的线性电压 ( $Linear regulator$ ) 纹波小, 降低电压的同时不能提高电流, 能量以热量释放.

Buck电路的动作状态为:

<p align="central">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Buck_operating.svg/1024px-Buck_operating.svg.png" width="70%">
</p>

1. 开关导通: 输入电源通过开关给电感充电, 电流上升, 电感产生感应电动势来对抗电流上升, 减缓电流上升速度. 电流从电源经过开关, 电感流向负载. 同步给输出电容充电.
2. 开关断开: 电感为了维持电流连续性, 会产生一个反向电动势,



# Boost电路


Boost电路的动作状态为:

<p align="central">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/09/Boost_operating.svg/800px-Boost_operating.svg.png" width="60%">
</p>
