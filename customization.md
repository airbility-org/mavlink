## Custom messages

| name                | id  | field type  | field name        | units |
| ------------------- | --- | ----------- | ----------------- | ----- |
| TILT_ANGLE_SETPOINT | 513 | uint32_t    | time_boot_ms      | ms    |
|                     |     | float       | tilt_fl           | deg   |
|                     |     | float       | tilt_fr           | deg   |
|                     |     | float       | tilt_rl           | deg   |
|                     |     | float       | tilt_rr           | deg   |
| TILT_STATUS         | 514 | uint32_t    | time_boot_ms      | ms    |
|                     |     | uint16_t[4] | realtime_tick     |       |
|                     |     | uint8_t[4]  | error_status      |       |
|                     |     | float[4]    | angle             | deg   |
|                     |     | float[4]    | angular_vel       | deg/s |
|                     |     | float[4]    | voltage           | V     |
|                     |     | int32_t[4]  | current           | mA    |
|                     |     | float[4]    | temperature       | degC  |
|CONTROL_SURFACE_CMD  | 515 | uint32_t    | time_boot_ms      | ms    |
|                     |     | float       | left_aileron      | deg   |
|                     |     | float       | right_aileron     | deg   |
|                     |     | float       | left_ruddervator  | deg   |
|                     |     | float       | right_ruddervator | deg   |
