---
sidebar_position: 1
id: base-doc
title: HF Station Setup
---

# Setup and Operation of the HF Station

Our HF station is a world-class setup, capable of operating on all HF bands. This document will guide you through the setup and operation of the station.

:::warning

The station is comprised of many expensive and dangerous components. If you are ever unsure about something, please contact the club officers. Do not try to fix an issue or worsen an existing one by yourself.

:::

Below is an image of the main shack desk with labelled components. Below, there is a section describing the operation and quirks of each component.

![Main HF Station Desk](/img/Shack-Annotated.png)

# Setup Guides

## Standard SSB Casual Operation

1. Turn on the ICOM 7610 radio by pressing the power button on top left.
2. Go the general band and mode you want to operate on.
   1. To change the band, press the corresponding frequency button on the right side.
   2. To change the mode, press the blue colored touch screen button in the top left of the screen.
3. Start up N1MM logger on the computer.
   1. NOTE: you must launch the logger from the desktop shortcut, NOT the windows start menu.
   2. Select "run" when prompted on your operating style.
   3. Enter your callsign as the current operator by pressing `CTRL + O`.
4. Make sure *either* the desk Mic or Headset is plugged in to the mic port on the bottom left of the radio.
5. Verify that the MOD OFF input is set to MIC on the radio.
   1. This is done by pressing the `menu` hardkey, then the `settings -> connectors -> MOD OFF input` menu.
6. If you would like to use the amp as well, read the [power on guide here](acom#turning-on-the-amplifier).

## Turning off the Station

1. Turn off the ICOM 7610 radio by pressing and holding the power button on top left.

:::info

Do not shutdown the radio completely. Simply place it in standby (from the power off menu), to allow remote operation.

:::

2. Close any open software. This may include, but is not limited to:
   1. N1MM Logger
   2. Green Heron Everywhere
   3. Elecraft W2
   4. FLDigi
   5. WSJT-X
3. Turn off the amplifier by following the [shutdown procedure](acom#turning-off-the-amplifier).

## Parts of the Station

### Radios (ICOM 7610)

Our two main HF radios are ICOM 7610s. These radios are capable of 100W output on all HF bands. They are SDR-based radios, and are capable of interfacing with a computer for digital modes.

The primary radio is the rightmost radio on the desk. It is connected to the main HF amplifier, and is the radio that should be used for most operations. The left radio is generally used for multi-operator contests, and is not connected to the amplifier.

A more detailed guide to these radios can *eventually* be found in the TODO:[ICOM 7610] document.

[Basic Manual](/pdf/IC-7610_BASIC.pdf) | [Advanced Manual](/pdf/IC-7610_ADV.pdf)

### Rotator Controller (Green Heron RT-21)

This is the device that controls the tower rotator, which allows us to aim our 10/15/20/40M yagi antenna. It is a simple device, and can be controlled via the buttons on the front, or via a computer interface.

The computer interface is called Green Heron Everywhere, and the "server" component must be launched first from the desktop shortcut. The client should launch automatically. 

If you are running N1MM and want to get the rotator to turn to your currently entered contact via hotkey, select `control -> N1MM` inside the Green Heron Everywhere client. Then, simply press `ALT + J` while in N1MM to get the rotator to turn to the correct heading.

Manual: [Green Heron RT-21](/pdf/RT-21_Manual.pdf)

### Amplifier (ACOM 2000A)

The amp and associated RCU (remote control unit) have documentation in the [ACOM 2000A](acom) page.

### Power Meter (Elecraft W2)

We have a power meter that can be used to measure the output power of from the amp. It is more accurate than the ACOM's internal power meter, and has a computer interface, for confidence while operating remotely.

The meter is comprised of the main box located on the desk, and a sensor that is connected to the amplifier's output. The sensor is a small silver box, and is connected to the main box via a black ethernet cable.

The software for the power meter is called W2.exe, and can be launched from the desktop shortcut. The software will automatically detect the power meter, and display the output power in real-time. If it does not detect the meter, turn the meter off and on via the power button on the meter's front panel.

Manual: [Elecraft W2](/pdf/W2-Manual.pdf)