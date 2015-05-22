# PAL2CRO
Composite Video to CRT converter

<b>This repository will be filled with data within the next weeks.</b>

<b>If you have gotten one of our boards, you can contact me for details under: pcb-25 [at] posteo [dot] net</b>

Basically a rip-off of Alan Wolkes "Improved NTSC video to Oscilloscope converter" (see below for the links). He came up with the circuit, which I wouldn't have been able to, since I never worked with video signals before. But I liked the idea so much, that I wanted to make a board for it and share the design files with anyone interested (the license below is only for my work, i.e. the schematic and board-files).

The converter takes a composite video input (PAL, NTSC or SECAM) and splits it into a X, Y and Z signal for an analog CRT-oscilloscope. If you connect the X and Y signal to the corresponding channels on your oscilloscope in X-Y mode, the Z signal to the Z or "trace modulation" input and fiddle a bit with the knobs, the CRT of your scope should act like a monochrome screen.

There is also an inverted-X signal, if the picture is mirrored and your oscilloscope can't flip the signal, and a contrast and brightness control.<br /><br />

Sources:<br />
[1] <a href="http://www.qsl.net/w2aew/W2AEW_NTSC_2_Scope_2.pdf">Alan Wolkes Rev. 2 circuit schematic</a><br />
[2] <a href="https://www.youtube.com/watch?v=5FYF5uhCzAM">First video, explaining the circuit</a><br />
[3] <a href="https://www.youtube.com/watch?v=yf4kOMSPbM0">Second video, explaining improvements made to the circuit</a><br />
(The other videos on his channel are well worth watching too)<br /><br />

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">PAL2CRO</span> on <a xmlns:cc="http://creativecommons.org/ns#" href="github.com/pcb-25/PAL2CRO" property="cc:attributionName" rel="cc:attributionURL">github.com/pcb-25/PAL2CRO</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://www.youtube.com/watch?v=yf4kOMSPbM0" rel="dct:source">https://www.youtube.com/watch?v=yf4kOMSPbM0</a> by Alan Wolke (idea and circuit design).
