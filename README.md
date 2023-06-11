# mobius
This is my github about Mobius.

# Version 2.6.0
- Fix #001 | Reverse Loop in Load/Save Mobius Project 
- Fix #002 | "setup" while loading Mobius Project was not set - Now the setup is set correctly 
- Add #003 | Add new section in ui.xml
- Add #004 | Radar Diameter and Level Meter is now configurable
- Upd #005 | Increase Messages Lenght to 50 characters
- Fix #007 | Fix issue in loopRadar when you change color of radar (some pixel still visible in wrong color due to approximation. - Now when the color is changed the black background is redrawn)
- Add #008 | Get Configuration from Current Directory and not from Registry (Works with Vst DLL and Standalone Exe)
- Fix #009 | Overlap counter EDP Issue
- Add #010 | Customizable AudioMeter Size
- Add #011 | Customizable LoopMeter Size
- Add #012 | Customizable Beater Diameter
- Add #013 | Customizable Layer Bars Size
- Fix #014 | Midi Out and VST Host Port! [HostMidiInterface] Now the midi events generated by the scripts from the MidiOut command are send to the MidiOut port of the Plugin! (not only in Plugin Output Devices set in Midi Device Selection)
- Add #015 | Implemented decay in AudioMeter (a kind of peak meter)
 -Fix #016 | Fix flickering background AudioMeter
