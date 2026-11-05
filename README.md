# mudravaani

Smart gloves that recognise Indian Sign Language (ISL) signs and turn them into text and speech (English/Hindi).

## What it does
- Two gloves (left and right) read finger bend and hand motion
- A laptop app recognises the sign, shows the text on screen and speaks it
- Speech can be routed to video calls through a virtual microphone

## Hardware
- ESP32 DevKit V1 (one per glove)
- 5 flex sensors per glove + MPU6050 accelerometer/gyroscope
- LiPo battery with TP4056 charger and MT3608 boost converter

## Software
- Arduino IDE for the firmware
- Python (pyserial, scikit-learn, text-to-speech) for the laptop app

## Project status
Parts ordered. Building in progress.

## Roadmap
- [ ] Build and test the gloves
- [ ] Record ISL sign data
- [ ] Train the recognition model
- [ ] Laptop app with text and speech
- [ ] Future: ASL support and Hindi output

## License
MIT