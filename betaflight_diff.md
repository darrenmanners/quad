
feature -BLACKBOX
feature -SDCARD
feature RSSI_ADC
map TAER1234
serial 2 32 115200 57600 0 115200
aux 0 0 0 1700 2100
aux 1 27 0 1700 2100
aux 2 18 3 1875 2100
adjrange 0 0 1 975 1100 18 2
adjrange 1 0 1 1100 1225 19 2
adjrange 2 0 1 1200 1350 20 2
adjrange 3 0 1 1325 1450 15 2
adjrange 4 0 1 1425 1575 16 2
adjrange 5 0 1 1550 1675 17 2
adjrange 6 0 1 1650 1775 9 2
adjrange 7 0 1 1775 1900 10 2
adjrange 8 0 1 1900 2025 11 2
set motor_pwm_protocol = DSHOT300
set ibat_scale = 235
set acc_hardware = NONE
set acc_trim_roll = -4
set pid_process_denom = 1
set osd_units = METRIC
set osd_time_alarm = 3
set osd_vbat_pos = 2059
set osd_rssi_pos = 2066
set osd_flytimer_pos = 2551
set osd_ontimer_pos = 2519
set osd_flymode_pos = 364
set osd_horizon_pos = 200
set osd_current_pos = 2072
set osd_mah_drawn_pos = 2104
set osd_pid_roll_pos = 2464
set osd_pid_pitch_pos = 2496
set osd_pid_yaw_pos = 2528
profile 0

rateprofile 0
rateprofile 0

set roll_srate = 80
set pitch_srate = 80
set yaw_srate = 80
