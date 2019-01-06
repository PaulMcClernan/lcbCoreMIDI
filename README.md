# lcbCoreMIDI

IT'S ALIVE!!!

So far this library consists of:
- LiveCode Builder (LCB) Bindings to create a Virtual MIDI Source.
- Handlers which creates a byte buffer that enables sending binary MIDI data out from LiveCode Script (LCS)
- TimeStamping, it has a seperate Send handeler that allows for sending MIDI messages with millisecond offsets from 0 (or now) from LiveCode Script (LCS), obsuring away the nanosecond time stampings (mach_kernel time, a struct that includes division values to use to get most accurate timming on different clock speed processors) retreived from the OS. 
- LiveCode Builder (LCB) Bindings to retreive various infos about the present state of the MIDI Setup on the system. (WIP)
