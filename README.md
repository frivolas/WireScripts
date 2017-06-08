# WireScripts
Scripts and apps for automated shape creation for the DIWire
All scripts by Oscar Frias @_frix_
www.oscarfrias.com

## 1 - Hawley Generator
- This is a Macro-enabled Excel spreadsheet that runs a VBA script to automatically generate a GCode script for bending a customized Hawley retainer pre-form.
- Wrote to enable ortho labs to quickly and without much hassle create the relevant GCode script to bend the pre-form for a Hawley Retainer. Without this app, it takes significant time and testing to get a viable script running.
- It also allows for very quick edition of the critical dimensions that define the shape, without having to dig into the GCode.
- It requires some appliance design skills, to know how to obtain the dimensions from a cast or printed model.
- It asks for the basic dimensions of the pre-form and spits out the corresponding code (commented) that can then be copied-pasted into WireWare to get the shape bent. Some values are hard-coded and could be made variable, but would need to collect calibration data for A and Z axes... (maybe in the future?)
