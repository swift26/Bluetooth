# Beacon Using Liard Module.

   File Name: edy.beacon.sb
   
      This file contains the edystone URL and UID implementation. 
      There are two timer in this code
               1. Advertisement time out
               2. ADC read timer  (Timer 2)
       The module advertise in every 250ms till 2000ms(timeout time). In every 20000ms it reads ADC to update voltage
       or temperature reading.
       
   Version: 0.1
   
       1. Working code with (ADC reading + Edystone advertisement)
   
   Enhancement Plans:
   
       1. GATT based URL change.
       2. Button implementation to toggle between advertisement mode and connection mode.
       3. Button pressed wake up and advertise for 5 times and go to deep sleep. ( Beacon used as calling bell)
       4. Creating format of data saving in URL to incorporate more data in 32bit payload (reference ruuvi tag)
       
       
    
