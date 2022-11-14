# ES100 WWVB-BPSK Receiver Module V1.1

* Written by François Allard
* Modified by matszwe02 & mattrude

## Everset ES100 WWVB (BPSK) receiver Library V1.1

ES100-MOD is a receiver module for the phase-modulated time signal broadcasted by the NIST radio station WWVB near Fort Collins, Colorado, and is based on Everset® Technology’s fully self-contained receiver-demodulator-decoder Chip ES100. With a size of just 12 x 16 mm and it’s direct-PCB-mount design, it can be integrated in new or current applications when exact time keeping is necessary but the legacy WWVB AM signal is to weak and GPS not available (e.g. in-house).

• Receives new phase modulated WWVB signal
• Significantly outperforms all other WWVB receivers
• Low power dissipation
• 2-wire serial interface
• Two antenna inputs
• 3.3V (2.0-3.6V max.) supply and logic level
• Max. current consumption 28mA (processing)
• Min. current consumption <0.1mA (standby)
• Full-Frame reception time 134 seconds
• Tracking Mode reception time 24.5 seconds
• I2C Pull-Up Resistors on-board (selectable)

## Introduction

Everset® ES100 is a fully self-contained phase modulation time code receiver that receives and decodes the 60 kHz time signal from the National Institute of Standards and Technology’s WWVB transmitter located near Fort Collins, Colorado, USA. It contains a digital correlation receiver to extract the time code information from the received signal. It also has a simple serial interface to transfer the date, time, and DST information to a host microcontroller. The ES100 is compatible with existing WWVB receiver antennas and offers significantly improved performance in low signal-to-noise and low signal-tointerference scenarios when compared to amplitude modulation receivers. The ES100 chip is only available as bare die. ES100-MOD is designed for any application where the bare die can not be used. UNIVERSAL-SOLDER® Everset® ES100-MOD adds the minimal necessary periphery to the ES100 chip, which is a high precision 16MHz crystal as time base for the microcontroller, several capacitors and resistors for stable operation, and pull-up resistors for the 2-wire serial interface (I2C). The latter can be activated or deactivated by closing or opening 2 solder bridges (jumpers) on the module.

## License

UNIVERSAL-SOLDER invests time and resources to provide this open source code; please support UNIVERSAL-SOLDER by purchasing products from UNIVERSAL-SOLDER.com online store!

Copyright (c) 2020 UNIVERSAL-SOLDER Electronics Ltd. All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
