# raspi-supercap
Open source Raspberry Pi supercapacitor UPS hat

## Goal 
Make reliable turn on / shutdown shield for Raspberry Pi

## BOM
* PCB – https://easyeda.com/adoconnection/raspi-supercap
* 20F x 2 supercapacitors
* ATMega328
* resistors

## Status
PoC assembly

## Сhecklist / use cases

- [ ] On power on wait for capacitors to be charged and turn on Raspberry
- [ ] I2C slave to query expternal power status and capacitors charge level
- [ ] Reset Raspberry pi if shutdown was activated and power is restored
- [ ] Customizable power off behavior


## Sources of inspiration
* https://juice4halt.com/
* https://www.youtube.com/watch?v=m20o3P-S5s8
* http://www.hackerspace-ffm.de/wiki/index.php?title=Raspi_EDLC_UPS
* https://raspberrypi.stackexchange.com/questions/74641/how-to-make-a-simple-reliable-15-second-ups-for-shutdown
* https://raspberrypi.stackexchange.com/questions/22579/pi-headless-how-to-confirm-that-the-pi-is-shut-down
* https://raspberrypi.stackexchange.com/questions/5489/how-do-i-turn-on-my-raspberry-pi-after-shutdown
* https://code.google.com/archive/p/tinkerit/wikis/SecretVoltmeter.wiki
* https://www.arduino.cc/en/Tutorial/MasterWriter