# puredata_drum_machine
A drum machine built in Pure Data, intended to run on iOS using MobMuPlat as a GUI

HOW TO USE IT on iOS
0. Get the free MobMuPlat iOS app
1. Transfer the .pd file and the .mmp file to your iOS device via iTunes
2. Run MobMuPlat and choose the "drum_machine" file
3. Make awesome sequenced sounds!

WHY?
I'm building a DIY modular synth and wanted a drum machine to play along with it. There are plenty of other ways I could accomplish this, but I wanted to try building a drum machine from scratch so I could have all the features I wanted.

FEATURES
• All sounds generated in real time using Pure Data for synthesis, no samples
• 4 drum modules: Sine (bass drum), noise (digital and white noise through bandpass filter), fm (modulator and carrier with multiple waveforms), and bang (similar to sine module but will be different in the future)
• Various clock modes, including external clock input (send audio into your device, the sequencer moves forward)
• Audio clock output (very short pulse on every 16th note) for syncing/controllinganalog hardware

PLANNED FEATURES
• Modulation matrix so anything can modulate anything else (turning the machine into a semi-modular sound generator)
• MIDI clock sync
• LFOs and S&H modules for more modulation fun

