Arduino Mega 2560 Driven Step Sequencer with 16x32 LED display





Changes for ArdStepSeq.c:
#Changed button inputs to facilitate LED pins (hard coded pins for LCD) fixed throughout code



Changes to Drawing:
#Moved LED pins from 2-7 PWM to --> 24-29 respectively

#Notes:
Just realized that there are 2 each parameter Phase/Decay 1/2 and freq -- one live, one global,
plus one tempo button.  total of 11 knobs.  There is only one knob left.

