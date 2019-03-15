# OEM7配置
## master
#### COM1 

#### COM2
serialconfig com2 115200
interfacemode com2 novatel novatelx on
movingbasestation enable
log com2 novatelxobs ontime 1
log com2 novatelxref ontime 1
COM3


## rover
#### COM1

#### COM2
serialconfig com2 115200
interfacemode com2 novatelx novatel on
log com2 headingextb onchanged

#### COM3

