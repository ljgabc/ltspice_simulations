# 电源电流有限制时电容充电时间仿真

V1：100V电源，用PULSE模拟电源商店瞬间
D1：二极管，在此的唯一作用是限制充电电流（导通电阻为0，电流限制为1A）
R1：模拟电源及走线电阻
L1：模拟走线及电容ESL
C1：2000uF的电容

![结果](https://github.com/ljgabc/ltspice_simulations/blob/master/capacitor_charging_with_limited_current/simulation.png)