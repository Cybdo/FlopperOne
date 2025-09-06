---
Title: "FlopperOne"
Author: "Cybdo"
Description: "Open Source Single Board Hacker Multitool based off the Flipper Zero"
Created On: 2025-09-06
---

# Journal 1: September 6th: Everything set up! (3 hours)
- Set up project in EasyEDA
- Laid out basic schematics for USB-C 5V input and a step-down for 3V3 for the RP2040 microcontroller
- made a concept plan for features:
-   OLED screen for display
-   6 buttons in a DPAD + OK/Back configuration
-   SD card for volatile storage
-   rechargable battery for power
-   NFC/RFID antenna
-   IR reciever
-   Sub-GHz antenna
-   (flipper compatiable GPIO??)

<img width="1672" height="1032" alt="image" src="https://github.com/user-attachments/assets/57a28603-0fe8-455e-8bd7-5500cc2525d8" />


# Journal 2: September 6th: Power to the RP2040 (0.5 hours)
- Spent a while researching power to the RP2040
- Laid out capacitors for the RP2040 at 3.3v and 1.1v
- Reorganised the schematic doc. might need more than one page

All is going well so far
<img width="1672" height="1032" alt="image" src="https://github.com/user-attachments/assets/bf7b642a-0a42-481e-ad2f-208a0da4cbfe" />

**Journal 2.1 Edit: Changed some caps around, I thought I was smart with the different capacitors for frequency impedance but theres 6 pins so 6 caps haha**
<img width="1118" height="634" alt="image" src="https://github.com/user-attachments/assets/06feab77-7deb-4bbd-8444-e733cd697b42" />



**Total time spent: 3.5h**
