# Carsim_Matlab_RLAgent
# 项目描述：
    Carsim_Matlab_RLAgent是一个基于carsim，matlab以及强化学习算法TD3，建立的汽车横向运动控制的项目
    软件版本：Carsim2024.0，matlab2024b，

# RL_Env说明：
    carsim设置：
    输入：IMP_STEER_SW
    输出：L_Drv_i
        A_Drv_i
        X_Drv_i
        X_Targ_i
        Y_Drv_i
        Y_Targ_i
        xo
        yo
        该项目用了三个预瞄点i的取值为1 2 3
    
    Carsim_simulink强化学习环境建模：
        RL_Runcontrol.slx
        注：carsim软件生成的simfile.sim 文件路径设置

    强化学习算法：
        RL_Runcontrol.mlx
        使用RL_Runcontrol.mlx脚本调用simlink环境完成训练