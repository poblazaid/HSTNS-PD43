**A control board / BMS to use 6x HP HSTNS-PD43 as a battery pack charger**

Battery pack is composed of 16x Eve MB31 cells, in a 8S2P configuration, for 16Kwh total power.  
Charger should output 29.2V @ 275A for 0.5C charge  
Total admissible charging power for 16x cells: 8.038 KW  
Total theoretical power for 6x power supplies: 8.400 KW  

**Cell info:**  
Rated:           3.2V / 314 Ah  
Minimum voltage: 2.5 V  
Maximum voltage: 3.65 V  
Charge at 0.5C:  502.4 W  

**Targets:**
- Increase voltage protection to 14.8 V
- Isolate power supplies to be able to work in parallel
- Monitor voltage output for each PSU
- Control voltage output for each PSU
- Monitor total amps in for PSU
- Monitor amps out per PSU pair
- Monitor amps in in the battery packs
- Monitor individual cell voltage
- Monitor individual cell SOC
- Balance cell across both packs  
