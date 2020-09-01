# Phase-Locked-Loop
The goal is to design a complete phase-locked circuit operating over a wide output frequency range with a low frequency reference clock, while minimizing the overall power consumption.

The target specifications for the PLL are
Parameter                                                 Specified Value

Technology -                                              TSMC 180nm CMOS
Supply voltage, VDD -                                          1.8 V
Operating frequency (fout) -                                100 MHz fixed 
Fixed feedback divider (N) -                                     16
Total capacitance used -                                       Minimum
Power consumption -                                            Minimum
Figure of Merit -                               Power × Total capacitance [mW×pF]
Absolute rms jitter -                                     0.2% of the period

Design Expectation: A typical PLL design requires trade-off between phase-noise/jitter performance and power consumption to ascertain the PLL loop-bandwidth.
