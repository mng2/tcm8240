Toshiba TCM8240 to Avnet Spartan 3A breakout
=======

This is an old project that's been sitting on the back burner for years and years now. It's an implementation of a FPGA to camera module interface, with a SDRAM cache. Using multiplexing, data can be stuffed directly in the SDRAM without having to go into the FPGA first; this architecture is necessary due to the limited number of available pins, the limited block RAM, and the (presumably) serial port readout.

This project is probably of limited interest to anybody because 1) Sparkfun no longer sells the TCM8240, thankfully 2) Avnet no longer sells the Spartan 3A dev board 3) I haven't even written the FPGA side yet. 
