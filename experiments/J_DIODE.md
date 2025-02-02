Diode
---

### One way traffic for current: The semiconductor Diode

* CH1 is used to measure the input to the diode, and CH2 will measure the output from it.
	
####	Testing with a DC voltage
	
![](https://github.com/fossasia/pslab-experiments/blob/master/images/schematics/diodeDC.svg)
		
* Connect PV1 to the P side of the diode (N side has a black band, P does not ) . Also connect PV1 to CH1 for simultaneous monitoring. Use a light emitting diode for more interactive results

* Connect The N side to CH2 to monitor the output voltage. Also connect this end to GND via a high resistance so that some current flow occurs.
	
* Try different values of PV1, and observe that diodes only allow current flow in one direction. If PV1 is less than GND (0 VOlts), the output voltage is zero. In case of the LED, It will only light up for positive voltages
	
#### Testing with an AC voltage
	
![](https://github.com/fossasia/pslab-experiments/blob/master/images/schematics/diodeAC.svg)
	
* Repeat the same with a voltage input that is already oscillating, and observe that current only flows when the input exceeds the potential at GND
	
* Set a very low frequency for W1, such as 10Hz so that you are able to see the LED actually blinking

#### Screenshot

![](https://github.com/fossasia/pslab-experiments/blob/master/images/screenshots/diodeSimple.png)


