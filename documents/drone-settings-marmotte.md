# Armattan Marmotte 4s 2306 2400kV motors (Betaflight 4.1.1)

### Rates

```
rateprofile 0

# rateprofile 0
set roll_rc_rate = 110
set pitch_rc_rate = 110
set yaw_rc_rate = 94
set roll_expo = 20
set pitch_expo = 20
set yaw_expo = 20
set roll_srate = 60
set pitch_srate = 60
set yaw_srate = 60
```

### Diff without rates

```
# version
# Betaflight / MATEKF722SE (MF7S) 4.1.1 Nov 15 2019 / 12:36:09 (1e5e3d369) MSP API: 1.42

# start the command batch
batch start

board_name MATEKF722SE

# serial
serial 2 8192 115200 57600 0 115200

# aux
aux 0 0 0 1900 2100 0 0

# vtxtable
vtxtable bands 5
vtxtable channels 8
vtxtable band 1 BOSCAM_A A CUSTOM  5865 5845 5825 5805 5785 5765 5745 5725
vtxtable band 2 BOSCAM_B B CUSTOM  5733 5752 5771 5790 5809 5828 5847 5866
vtxtable band 3 BOSCAM_E E CUSTOM  5705 5685 5665 5645 5885 5905 5925 5945
vtxtable band 4 FATSHARK F CUSTOM  5740 5760 5780 5800 5820 5840 5860 5880
vtxtable band 5 RACEBAND R CUSTOM  5658 5695 5732 5769 5806 5843 5880 5917
vtxtable powerlevels 5
vtxtable powervalues 25 100 200 400 600
vtxtable powerlabels 25 100 200 400 600

# master
set gyro_lowpass2_hz = 375
set dyn_notch_width_percent = 0
set dyn_notch_q = 250
set dyn_lpf_gyro_min_hz = 300
set dyn_lpf_gyro_max_hz = 750
set rc_smoothing_auto_smoothness = 20
set serialrx_provider = CRSF
set dshot_idle_value = 450
set dshot_bidir = ON
set use_unsynced_pwm = OFF
set motor_pwm_protocol = DSHOT600
set bat_capacity = 1500
set yaw_motors_reversed = ON
set small_angle = 180
set pid_process_denom = 1
set osd_vbat_pos = 2423
set osd_rssi_pos = 33
set osd_link_quality_pos = 2081
set osd_rssi_dbm_pos = 97
set osd_tim_2_pos = 2401
set osd_throttle_pos = 2408
set osd_current_pos = 2413
set osd_mah_drawn_pos = 2391
set osd_altitude_pos = 2102
set vtx_band = 5
set vtx_channel = 8
set vtx_power = 3
set vtx_freq = 5917

profile 1

# profile 1
set dyn_lpf_dterm_min_hz = 105
set dyn_lpf_dterm_max_hz = 255
set dterm_lowpass2_hz = 225
set feedforward_transition = 40
set iterm_relax_cutoff = 10
set p_pitch = 74
set i_pitch = 77
set f_pitch = 26
set p_roll = 66
set i_roll = 70
set d_roll = 34
set f_roll = 14
set i_yaw = 77
set f_yaw = 0
set d_min_roll = 0
set d_min_pitch = 0

# end the command batch
batch end
```