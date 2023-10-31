# MadellOpenPnpConversion
This documents all the hardware and software changed to make the Madell PX3700 work with OpenPnp

This is a work in Progress started on 2023-10-31..

The PX3700 controller will be replaced by the Makerbase MKS Robin Nano V3 Eagle 32Bit 168Mhz F407 Control Board. 
Later I will create my own board (maybe with an ESP32 using fluidnc)

Information on the board is at : https://github.com/makerbase-mks/MKS-Robin-Nano-V3.X
( I will test the firmware that comes with the board. I believe it is Marlin V2 but if required i will make some changes)

For all the Upgrade tasks and parts that i requie for this confersion I will place here.

Part 1 - Hardware
        Replacing the Controller and rewiring all the stepper drivers and solenoids to the New board

Part 2 - Firmware
        Testing with the default firmware on the board, and if required, modifying it.

Part 3 - Software
        Test OpenPNP 2.0 software with the unit. https://openpnp.org/
        OpenPnP Project:          https://github.com/openpnp/openpnp
        
        Also investigate OpenCV to test the vision aspect of the CNC system.
        (I am a C# Developer and will probably try to write some application for the PickandPlace machine and create a seperate repository for it)
        




