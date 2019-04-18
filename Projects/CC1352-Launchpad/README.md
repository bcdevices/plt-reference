# Test Plans for TI CC1352

- [cc1352-program.yaml](cc1352-program.yaml): Program CC1352 over JTAG

## PLT-200A connection

![image](images/plt200a-cc1352-launchpad-hookup.jpg)

| PLT-200A      | UART/TP pin | CC1352  |
|---------------|:-----------:|---------|
| JTAG\_TMS     | 2           | TMS     |
| GND           | 3           | GND     |
| JTAG\_TCK     | 4           | TCK     |
| JTAG\_VCC     | 5           | 3V3     |
| JTAG\_TDO     | 6           | TDO     |
| JTAG\_TDI     | 8           | TDI     |
| JTAG\_TRST    | 10          | RST     |
