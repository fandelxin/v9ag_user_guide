# Instructions for use of the spreader
## Spreader connection
<div  align="center"> <img src="pictures/Spreader.png" width="50%" height="50%">
</div>

## connection Description:

### 飞The flight control is connected to the spreader in two ways connection

1，PWM MODE：Value -> PMU A1

            Speed -> PMU A2
            
            Empty -> PMU L1

2，CAN MODE：  CanBus -> PMU CAN

## Notice:

1.V9 CAN baud is 1000K，if use spreader CanBus，need the can baud rate of the spreader is also 1000K.

2.Connect flight control，APP’s Drone type page，choose Seed(F).

3.Check whether the spreader supports the CAN mode, If it does not support the CAN mode.select the PWM mode only.

4.The EFT transmitter defaults to PWM mode,and can be changed to CAN mode througt APP after connecting CANBUS.

## APP Spreader instruction video

1 https://www.bilibili.com/video/BV1pF411L7Da?spm_id_from=333.999.0.0

2 https://www.bilibili.com/video/BV1ge4y1y7TQ?spm_id_from=333.999.0.0&vd_source=4813f9de887ce27b46ffac5a84756332
