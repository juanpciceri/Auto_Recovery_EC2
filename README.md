# Auto_Recovery_EC2
This lambda will autorecover any EC2 instance after system status checks fails. 

The python function will create an alarm for current running ec2 instance and will associate autorecover action after the system status check fails 5 consecutive period, in this case each period is 1 minute.
