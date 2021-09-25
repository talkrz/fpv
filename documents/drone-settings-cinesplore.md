# FPVCycle Cinesplore 4s 2203 3450kV motors (Emuflight)

### Rates

```
# rateprofile
rateprofile 0

set roll_rc_rate = 99
set pitch_rc_rate = 99
set yaw_rc_rate = 99
set roll_srate = 63
set pitch_srate = 63
set yaw_srate = 63
set rate_center_sensitivity = 60
set rate_center_correction = 20
set rate_center_weight = 90
set rate_end_weight = 50
```

### Diff without rates

```
# version
# EmuFlight / MATEKF411 (MK41) 0.3.1 May 19 2020 / 04:45:55 (9366544) MSP API: 1.47

board_name 
manufacturer_id 

# name

# resources
resource MOTOR 3 B07
resource MOTOR 4 B06

# mixer

# servo

# servo mix


# feature

# beeper

# beacon

# map

# serial
serial 0 2048 115200 57600 0 115200
serial 1 64 115200 57600 0 115200

# led

# color

# mode_color

# aux
aux 0 0 0 1950 2100 0 0

# adjrange

# rxrange

# vtx

# rxfail

# master
set gyro_lowpass2_hz_roll = 300
set gyro_lowpass2_hz_pitch = 300
set gyro_lowpass2_hz_yaw = 300
set imuf_roll_q = 6500
set imuf_pitch_q = 6500
set imuf_yaw_q = 6500
set imuf_w = 64
set baro_hardware = NONE
set serialrx_provider = CRSF
set align_board_yaw = -45
set osd_vbat_pos = 2423
set osd_rssi_pos = 2082
set osd_tim_1_pos = 2401
set osd_throttle_pos = 2409
set osd_current_pos = 2414
set vtx_band = 5
set vtx_channel = 8
set vtx_power = 2
set vtx_freq = 5917

# profile
profile 0

set throttle_boost = 0
set p_pitch = 60
set i_pitch = 75
set d_pitch = 32
set p_roll = 52
set i_roll = 75
set d_roll = 30
set p_yaw = 65
set i_yaw = 75
```
