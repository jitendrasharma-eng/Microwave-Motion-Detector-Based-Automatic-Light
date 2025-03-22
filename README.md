# Microwave-Motion-Detector-Based-Automatic-Light
This project is an automatic light control system using a microwave motion detector. When motion is detected, the system automatically turns on a connected light and keeps it ON for a defined period. It is a touchless, energy-saving solution for smart lighting applications.

How It Works
The microwave motion detector module continuously scans for movement.

When motion is detected, the opto-isolated TRIAC driver (MOC3020) triggers the BT136 TRIAC to turn on the AC light.

The light remains ON as long as motion is detected.

After a short delay, the light turns OFF automatically if no movement is detected.

Circuit Description
The circuit is divided into three sections:

1. Power Supply Section
AC voltage is rectified using a bridge rectifier (1N4007 diodes).

A 5V Zener diode ensures a regulated 5V output for the motion detector module.

2. Motion Detection & Control Section
The microwave motion sensor detects motion and sends a signal.

An indicator LED (LED1) turns ON when motion is detected.

A 100Ω resistor (R8) limits current to the optocoupler.

3. Light Switching Section
The MOC3020 optocoupler isolates the low-power control circuit from the high-power AC load.

The BT136 TRIAC is triggered to switch the AC light ON.

A snubber network (capacitor + resistor) ensures stable operation of the TRIAC.

Components Used
Component	Description
Microwave Motion Detector	Detects movement
MOC3020	Optocoupler for isolation
BT136	TRIAC for AC load switching
1N4007 Diodes	Bridge rectifier
Zener Diode (5V)	Voltage regulation
LED & Resistors	Indicator and current limiting
Capacitors	Filtering and snubber network
Working Principle
Motion Detected → Sensor triggers the circuit.

Optocoupler Activates → MOC3020 isolates and triggers the TRIAC.

Light Turns ON → The TRIAC allows AC power to the bulb.

No Motion → Light turns OFF after a delay.

Applications

Automatic Room Lighting

Corridor & Staircase Lighting

Smart Home Automation

Security Lighting
