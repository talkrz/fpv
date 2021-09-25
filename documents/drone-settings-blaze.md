# DemonRC Blaze 4s 2306 motors (Emuflight)

### Rates

```
# rateprofile
rateprofile 0

set roll_rc_rate = 110
set pitch_rc_rate = 110
set yaw_rc_rate = 95
set roll_expo = 10
set pitch_expo = 10
set yaw_expo = 10
set roll_srate = 60
set pitch_srate = 60
set yaw_srate = 60
set rate_center_sensitivity = 70
set rate_center_weight = 35
set rate_end_weight = 35
```

### Diff without rates

```
# version
# EmuFlight / REVOLTOSD (ROSD) 0.3.2 Oct  7 2020 / 19:01:06 (e0270d5fd) MSP API: 1.49

board_name 
manufacturer_id 

# name

# resources
resource MOTOR 2 A03
resource MOTOR 3 A02
resource MOTOR 4 B01

# mixer

# servo

# servo mix


# feature
feature OSD

# beeper

# beacon

# map

# serial
serial 0 0 115200 57600 0 115200
serial 2 64 115200 57600 0 115200
serial 5 2048 115200 57600 0 115200

# led

# color

# mode_color

# aux
aux 0 0 0 1900 2100 0 0

# adjrange

# rxrange

# vtx

# rxfail

# master
set gyro_lowpass_hz_roll = 110
set gyro_lowpass_hz_pitch = 110
set gyro_lowpass_hz_yaw = 110
set imuf_roll_q = 5000
set imuf_pitch_q = 5000
set imuf_yaw_q = 5000
set imuf_sharpness = 3000
set serialrx_provider = CRSF
set min_throttle = 1070
set use_unsynced_pwm = OFF
set motor_pwm_protocol = DSHOT600
set motor_pwm_rate = 480
set current_meter = ADC
set battery_meter = ADC
set yaw_motors_reversed = ON
set osd_vbat_pos = 2369
set osd_rssi_pos = 2049
set osd_current_pos = 2359
set osd_mah_drawn_pos = 2393
set osd_avg_cell_voltage_pos = 2337

# profile
profile 0

set dterm_lowpass_hz_roll = 100
set dterm_lowpass_hz_pitch = 100
set dterm_lowpass_hz_yaw = 100
set witchcraft_roll = 0
set witchcraft_pitch = 0
set iterm_relax_cutoff = 0
set iterm_relax_cutoff_yaw = 0
set p_pitch = 71
set i_pitch = 75
set d_pitch = 35
set p_roll = 64
set d_roll = 33
set p_yaw = 72
set i_yaw = 75
set d_yaw = 10
```
