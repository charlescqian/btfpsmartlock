# btfpsmartlock
Bluetooth Smart Lock using Fingerprint Sensor with an Android phone. Prototype with Arduino Uno

## Overview
This project is intended to be a smart home device in the form of a bluetooth lock for improved home security and convenience. I intend to focus on the "multi-factor authentication" features of this device, as I believe the market is missing a device with a strong focus on security. Multi-factor authentication is a commonly used technique in enterprise and consumer markets for securing an user's account. For this project, I would like to utilize 3 factors: possession of the smartphone device linked to the smart lock, to be in the proximity for a secure bluetooth connection to the smart lock and utilizing the biometrics profiles (fingerprints and facial scans) stored in the smartphone to unlock the smart lock. This provides the user with a convenient yet secure method for home security.

## Change Log
08/31/2018 - Added "First Step" Section. Added "Change Log"

## First Step: Physical Prototype
My first step is to ensure that this idea works physically. The idea is simply to attach a servo motor to the locking mechanism of a door, and use a microcontroller such as an Arduino Uno to control the servo motor. Before trying anything on my front door, I decided to prototype on my room's door instead in case I mess up the lock.

### Requirements
- Servo Motor must be able to couple to the locking mechanism and turn the mechanism

### Nice to Have's
- Minimum changes to the locks

