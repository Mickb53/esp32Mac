

My first time using git hub so....slowIgo looking to build a communications device using two esp32 microcontrollers. All thats required is about six digital switching opperations. The requiments are as follows:

1) The major switching is going to change direction of the machine opperation (needs to be fast, 800ms max).

2) Needs to be wireless as the objective of this project is to remove wiring that needs regular replacement and can proove expensive.

3) Low power consumption and low battery warning must be applied in the circuit if the supply voltage to the esp32 is a battery.

 
4) Estop must be implimented as a N.C switch.

5) Emf emited from other sources should be considered where possiblity of false triggers.
i.e inverters that controls the motor speeds.

				

					Description

  I will try describe the opperation of the machine although its very simple there is one axis. The machine simply travals right to left then left to right at approx 1m per second, hits a carrage return and well returns..this is a constant loop till stop command or timmer off. The machine is 24v switching and three phase 415v powered.

 