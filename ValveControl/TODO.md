# Things to fix in the valve control PCB
* Use MOSFETs instead of SSRs
  * Solenoids connected to 24v on one terminal
  * Connections on board from other side of solenoids to MOSFET sources
  * No longer need 24v input on board
* Valve master high = disable arduino instead of enabling
  * Swap pairs of inputs on mux
* Add jumper headers for arduino-side mux inputs to arduino pins to allow for multiple valve boards
* Test stand blinkenlights
  * 4 of valve outputs?
  * Ignition arm/fire?
  * Use switch on test stand: valve master on / off / use control panel valve master
