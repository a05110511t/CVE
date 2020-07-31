# Spirent TestCenter C1, CF20, N4U, C50 Privilege Escalation
- [Spirent CF20 for CyberFlood](https://www.spirent.com/-/media/datasheets/security/ds_cyberflood_cf2_datasheet.pdf)
- [Sprent TestCenter c1](https://www.spirent.com/-/media/datasheets/broadband/pab/spirenttestcenter/stc_c1-appliance_datasheet.pdf?la=en&hash=CF69574CB0CBC15EE20F669D419B560F5C7E54D6)
- [Spirent SPT-N4U](https://www.spirent.com/-/media/datasheets/broadband/pab/spirenttestcenter/spirent_n4u_chassis_datasheet.pdf)
- [Spirent C50](https://www.spirent.com/-/media/datasheets/broadband/pab/spirenttestcenter/spirent_testcenter_on_c50_appliance_datasheet.pdf)

## Description
The attacker can through Privilege Escalation vulnerability to get root privilege from ssh initial shell(restricted, only for network setting). This vulnerability affects the vendor that attacker can backup all sensitive files (all programs/source code/configs) on the device.


## Impact
The attacker can backup all sensitive files (all programs/source code/configs) on the device.
The attacker can access the Company intranet if they use public IP.

## Known Affected Firmware
|Product|Chasis Version|
|---|---|
|Spirent C1| <= 4.91.5436|
|Spirent C50| <= 5.03.8466|
|Spirent CF20| <= 5.03.0389|
|Spirent N4U| <= 4.90.5126|

## Details
Get root privilege via Privilege Escalating by ssh initial shell(restricted, only for network setting).

## Contributor
- CW Tzeng (CHT Security)
- Will Chen (CHT Security)
- Wei Sun (CHT Security)
