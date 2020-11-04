# Electret Condensor Microphones

## Electret Mic preamp

* [instructables.com/Pre-amp-to-electret-mic/](https://www.instructables.com/Pre-amp-to-electret-mic/)
  ![FFMLVLDGMON5YBF](https://user-images.githubusercontent.com/638189/97815407-c5bc8480-1c5b-11eb-9095-5810aa7195b1.png)
* Transister is 2N3904
* Discussion: If the output is very low, [replace the 100K resistor](https://www.diyaudio.com/forums/analog-line-level/279174-transistor-mic-preamp.html) with something like 1 or 1 meg ohm

## Low Noise Mini Electret Microphone Preamplifier

* This one says it can amplify the output signal to line level
* Requires 9v to operate
* Uses OPA172 IC (hard to find) [TI spec sheet](https://www.ti.com/lit/ds/symlink/opa172.pdf)
  ![IMG_5973](https://user-images.githubusercontent.com/638189/97815677-db32ae00-1c5d-11eb-868f-7f9e28db2b94.jpg)
  <img src="https://user-images.githubusercontent.com/638189/97815678-dbcb4480-1c5d-11eb-8646-d04d0384173d.jpg" width="640" />

## Mini project: Amplified electret microphone

* [Bitluni Youtube](https://www.youtube.com/watch?v=SToBPCajwc0)
  <img src="https://user-images.githubusercontent.com/638189/97826746-6dec4080-1c90-11eb-9677-a4702aa592fe.png" width="640" />
* Appears strong enough for line level
* Uses BC547C transistor, but BC5479C also works (has lower noise)

## Low Noise Microphone Preamplifier Circuit Using NE5534 IC
* [circuits-diy.com](https://circuits-diy.com/low-noise-microphone-preamplifier-circuit-using-ne5534-ic/)
  ![Low-Noise-Microphone-Preamplifier-Circuit](https://user-images.githubusercontent.com/638189/98065206-17167080-1e22-11eb-819e-501d27b6cd38.png)
* Uses NE5534 IC [TI Datasheet](https://www.ti.com/lit/ds/slos070d/slos070d.pdf)
  * this IC high unity-gain, low noise, low harmonic distortion, and low consumption of power with short circuit protection
  * alternatives: TL082 or TL071
* This circuit can be operated by a 9-12V battery

## Microphone Preamplifier Circuit Using TL071 Op-Amp
* [circuits-diy.com](https://circuits-diy.com/microphone-preamplifier-circuit-using-tl071-op-amp/)
  ![Microphone-Preamplifier-Circuit](https://user-images.githubusercontent.com/638189/98065883-7de85980-1e23-11eb-9aa2-a8443c3eb407.png)
* operating voltage of this circuit is 9-12V
* uses TL071 Low-Noise JFET-Input General-Purpose Operational Amplifier [TI Datasheet](https://www.ti.com/lit/ds/symlink/tl071.pdf)
