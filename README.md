# LPT2MIDI
- LPT2MIDI is a parallel printer port (LPT) to MIDI adapter.
- KiCAD 10 PCB project is included.
- Uses Arduino IRQ to trigger pin reads and forwards the data to MIDI serial buffer (MIDI uses 31250 bps).
- A simple port trapping code for MS-DOS is included. This for the time being works for direct midi commands to port 330h only.
- Quickly modified version of SOFTMPU for MPU-401 compatibility.
- Tested with mt32pi and Secret if Monkey Island.
- Requires power through USB on Arduino Nano while operating.