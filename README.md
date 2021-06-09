# Auto_Recovery_EC2
This lambda will autorecover any EC2 instance after system status checks fails. 

The python function will create an alarm for current running ec2 instance and will associate autorecover action after the system status check fails 5 consecutive period, in this case each period is 1 minute.

![image](https://user-images.githubusercontent.com/32818490/121433098-88cf1380-c949-11eb-90f9-a6a32f4b7e7b.png)
