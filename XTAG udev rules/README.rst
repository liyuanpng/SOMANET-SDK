* To use your XTAG adaptor please move the 99-xmos.rules files into /etc/udev/rules.d/ directory.
* To update EtherCAT EEPROM file with the IgH driver installed type: ethercat sii_write -p <your node position in topology> <path to the EEPROM binary>
  example: ethercat sii_write -p 0 CiA402-mk2-noEoE
