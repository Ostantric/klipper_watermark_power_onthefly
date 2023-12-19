# Change watermak power setting on the fly in Klipper
This simple code change in heater.py and pid_calibrate.py, lets you adjust the total power output to the heater. For some heaters you may want to change your pwm_cycle_time.

# Gcode command
Now you can do this:
``` bash
    #Full Power
    SET_HEATER_TEMPERATURE HEATER=cabinet TARGET=50 POWER=1
    #%25 Power
    SET_HEATER_TEMPERATURE HEATER=cabinet TARGET=50 POWER=0.25
```
### TODO
* ~~Fix PID_CALIBRATE gcode crush~~


