# casette_synth 

The goal is to make a simple casette tape synthesizer that can be played with a midi keyboard. A MIDI keyboard connects to a computer, where a Chrome browser captures the input and sends it to a server. The server relays the voltage change data to the Arduino, which modulates the casettes voltage in response to the MIDI input. 

Aduino_DAC code interfaces arduino nano with MCP4725 DAC to modulate specific voltages coming from arduino. 

To Do: Server to send serial commands to arduino nano.  

**I got the idea for the tape synth from [schollz](https://github.com/schollz/tape-synth) who was inspired by Onde Magnétique among other people. The YouTube video ["How to Hack a Casette Player"](url) was also helpful for understanding how to add voltage controls to the casette, and ultimately code a midi controller to modulate voltages for each note.  
