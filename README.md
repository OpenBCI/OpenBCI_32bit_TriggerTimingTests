# OpenBCI_32bit_TriggerTimingTests

This firmware extends the standard OpenBCI firmware to allow software to send event tags to the board to AUX channel XX and code to read analog sensor data from pin D13 to AUX channel XX.  To send software triggers, send a backtick character to the board ('`').

The purpose of this firmware is to test for latency differences between when stimuli are presented to the computer screen ( as measured by the analog sensor (a photoresistor) and when the software trigger is 

Refer to this tutorial to set up the photoresistor and this tutoral to analyze your results.
