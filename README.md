# TLE-MP28600-DK-HW

This is simply a development kit for the MPM MP28600 boost IC.

It promises 600nA IQ, and high efficiency, which should let me run 3V3 systems from a 1S lithium configuration. Considering the datasheet is extremely minimal - I shall have to test for a few things:

 * Output ripple. Ideally this would be low enough that it doesnt mess with my ADC reference.
 * The IQ is consistent across the 2.5 - 4.2V VIN range of 1S.
 * What is the efficiency when in "down mode". Does this just behave as an LDO?
