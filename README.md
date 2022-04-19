# Monotron_CV_mod
A modification for Korg's Monotron Delay, which makes it accept standard Eurorack CV voltages (Pitch, Gate and Cutoff CV). The mod also provides an option to power the monotron via micro-USB.
<br />
<br />
Input specs:<br />
Pitch CV: 1V/oct (0-10V) <br />
Gate CV: GATE ON-> 5-12V <br />
Cutoff CV: 0-10Vpp (possibly more if you attenuate the signal using the Cutoff Trimmer, but it can damage the op-amp if the trimmer is in the wrong position).
<br />
<br />
Micro-usb: 5 +/- 10%

Output:<br />
Connect GATE, VCC, GND, CUTOFF and LFO testpads of Monotron to GATE, +5V, GND, CUTOFF and LFO pins of the mod PCB respectively, by soldering wires between them.<br />
GATE and CUTOFF are output signals being provided by the mod PCB. LFO is an input signal generated on the monotron board and routed into the mod PCB, which includes a proper output jack.
<br />
<br />
If you wish to use USB power, you need to cut the track as shown on Figure 1 to disconnect the batteries from Vcc. Then you need to solder a wire from the positive lead of the capacitor to the Bat pin of the mod PCB (Figure 2). This is done to prevent current flowing from USB to the batteries, potentionally damaging them (Figure 3).
<br />
<br />
Figure 1: <br />
![ReadmeFigure1](https://user-images.githubusercontent.com/101595484/164016741-ba5b5a88-95c2-4f2e-ae75-5b52a6252b88.jpg)
<br />
<br />
Figure 2: <br />
![Figure2](https://user-images.githubusercontent.com/101595484/164017516-625cd39a-99eb-4a7a-b0f3-3d4f5ca23494.jpg)
<br />
Figure 3: <br />
<img width="710" alt="ReadMeGithub" src="https://user-images.githubusercontent.com/101595484/164013894-c8fbc97c-9806-45da-8eef-2b9a8f1a70c8.png">
