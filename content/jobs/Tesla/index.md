---
date: '2017-11-20'
title: 'Firmware Engineering Intern'
company: 'Tesla'
location: 'Palo Alto, CA'
range: 'November 2017 - June 2018'
url: 'https://www.tesla.com/'
---

Worked independently as well as in a team environment to design, develop and validate, validation infrastructure for Tesla Model S, Model X, and Model 3.

- Developed firmware for ARM-based CAN router to inject faults, modify/corrupt CAN message, or make ECUs go MIA. Added capabilities enabled the existing dyno platform to validate the Electronic Stability Programme (ESP) and Brake Booster (iBooster) functionality at the system level.
- Created a testing framework to automate firmware validation of the Redundant Electronic Brake Request (R-EBR) feature.
- Designed and implemented firmware for the vehicle lock state machine for automated firmware validation. These different behavioral state models were the alarm control model, vehicle locking/unlocking model, NFC, and BLE authentication model, multidoor unlock model, and doors and windows model.
- Developed hardware to integrate the behavioral models in the existing testing framework such that it guarantees precise control over various security components.
- Developed a Jenkins pipeline to detect new firmware builds, OTA update them on a vehicle, test critical features and upload results for nightly automation testing.
- Improved and supported the health of testing platforms by troubleshooting bugs.
