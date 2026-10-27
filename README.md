PRAVHA

Intelligent Rainwater Harvesting & Adaptive Stormwater Management

Every Drop Should Have a Purpose.

A low-cost Arduino Uno system that manages rainwater from roof to tank to overflow: first-flush separation, filtration, automated level monitoring, and servo-controlled overflow diversion.

How it works
Detect: rain sensor starts the control process.
Separate: Servo 1 diverts the first runoff into a flush chamber.
Filter: remaining water passes through a filtration chamber.
Store and monitor: an ultrasonic sensor tracks tank level.
Divert: when the tank is full, Servo 2 redirects water to the overflow outlet.
Indicate: LCD and LEDs show status; push buttons handle reset and manual override.
Hardware
Arduino Uno
1× rain-drop sensor
2× HC-SR04 ultrasonic sensors (mounted above the water)
2× SG90 servos (separate regulated 5 V supply, common GND)
16×2 I2C LCD, 2× push buttons, 4× LEDs
Applications
Rural: overflow to recharge pits or trenches (site assessment required)
Urban: overflow to rain or sponge gardens
Status

Design-stage proposal for Falling Sun 2026 (Robotics & Hardware). No experimental results are claimed; expected benefits need prototype validation.

SDGs: 6 · 11 · 13
