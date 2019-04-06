# 缓启动电路仿真

解决单板上电瞬间电流过大问题，同时可以避免电源极性接反时烧坏单板。


V1：12V输入电源，用PULSE模拟电源上电瞬间
C1：通过C1的充电时间控制VGS电压
R1：控制C1的充电电流
M1：通过VGS控制内阻，实现缓慢的上电电流控制
C2、R2：模拟负载

![结果](https://github.com/ljgabc/ltspice_simulations/blob/master/soft_start_circuit/simulation.png)