# Embedded-Lab-7

The code for Lab 7 is attached to this repository.
The purpose of the code is to read two external sensors with the MSP430.  The first sensor is a 10k Thermistor and the second sensor is a 200k ohm Photoresistor.  The code takes the values from these sensors and then converts there raw values into something that is more comprehensive for humans to see.  For instance the Thermistor value is scaled so that it will produce a value that will be in celsius.  The values for this code are then writen to the terminal of Code Composer.  This is done so that the C# HUD wihtin Visual Studios is able to take there value and send that information to ThingSpeak completing IOT loop.
