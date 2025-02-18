# MEMS-Microphone-Phantom-Power
A micro-electromechanical microphone and custom preamp, designed to be powered using a phantom power supply. Used to monitor the sound from the inside of my saxophone, play thru FX loops without feedback issues.

I want to be able to play saxophone thru my DAW's FX chain. When I attempt to do this using a standard microphone placed close to the saxophone I am running into some pretty bad feedback issues when monitoring live in my speakers. The solution is some kind of small microphone that isnt very sensitive, that i can place inside the saxophone, such that noise external to the horn does not get picked up by the microphone to a large extent. 


Criteria 

Must be small

Analog - DSPing the mic would be a waste if i want to use pedal boxes, plus this adds a layer of electrical complexity which would make the solution fit worse, and look less appealing

Fairly low sensativity- cannot pick up too much noise from outside the horn

No external power wall wart or battery - I want to use the phantom power built into the audio interface for a more beautiful solution.

MEMS Microphones to test

IM70A135V01XTMA1

IM73A135V01XTSA1

SPH18C3LM4H-1

SPM0687LR5H-1



To power these microphones I will be using a custom PCB which utilizes Nichion SLB batteries. The charging circuit for these batteries is the modified Development board for these batteries, which utilizes Torex silicon. I borrowed the application reference design schematic from TOREX, which uses a BMS, and overcharge protection, my schematic is linked in the project files for this repository. 
