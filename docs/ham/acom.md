---
sidebar_position: 2
id: acom
title: ACOM 2000A
---

# Operating the ACOM 2000A

Our main HF amplifier is a world-class ACOM 2000A. This amplifier is capable of 1500W output on all HF bands. It is a tube-based amplifier, and is capable of automatic band switching and tuning.

:::warning

This is a high-voltage device. It should always be handled with care. If you are ever unsure about something, please contact the club officers. Do not try to fix an issue or worsen an existing one by yourself.

:::

## Parts of the Amplifier

The main amplifier unit sits on the while wooden riser platform behind the main HF station desk. It is large, and contains a big red switch on the front. This is the power switch, and can generally be left in the "on" position.

The amplifier is powered off the 208V circuit normally used for the rear shack air conditioner. this will be rewired (eventually), but is this way for now. If it's not turning on, check the circuit breaker for the air conditioner in the front shack.

The amp is controller by a RCU, or remote control unit. This is a small box that sits on the desk, and is connected to the amplifier via a long cable. All user interaction with the amplifier is done through this unit (pictured below).

![ACOM 2000A RCU](/img/acom_rcu.png)

## Turning on the Amplifier

To turn the amp on, press and hold the red `ON/OFF` button on the RCU until you hear a beep. The amp will go through a self-test and 150 second warmup procedure. Do not touch any buttons or the amp during this time.

## Entering operating mode.

:::info

Before you attempt to drive the amplifier, validate that the power output of the ICOM 7610 is set **to 30% or less.** This will ensure we do not over-drive the amp, and extend its life.

:::

When the amp is first turned on, the STB light will be yellow, indicating that the amp is in standby mode. To enter operating mode, press the `OPR/STB` button on the RCU. The `OPR` light will turn green, indicating that the amp is ready to operate. Being in standby passes all signals through the amp, but does not amplify them.

## Switching Bands

When you first boot up the amp, you may notice that the RCU does not display the correct band. The amplifier is capable of determining which band you're operating on, and *automagically* switching to it, but only if you transmit first. A short transmission should be enough for the amp to recognize which band you're on and switch to it. If it does not, try a CW transmission as that's easier to detect.

## Tuning the Amplifier

The ACOM 2000A is capable of automatic tuning. To tune the amplifier, press the `ENT` button on the RCU *TWICE*. Then, begin a transmission at 15-20% power on the 7610, that includes a carrier. This can be a constant CW transmission (by enabling straight key mode), or an AM transmission (by switching the mode on the 7610 to AM and pressing the `TRANSMIT` button). The amp will tune itself, and beep when complete.

:::info

The amp's internal tuner is only capable of tuning a 2:1 SWR. If you have a higher SWR, the amp will not tune. Please make sure the 40M and 80M antennas are properly tuned using the external tuners located in the rack on the wall.

:::

## Turning off the Amplifier

To turn off the amplifier, press and hold the red `ON/OFF` button on the RCU until you hear a beep. The amp will go through a shutdown procedure. It may give a message about cooling the tubes, and this is normal. Do not touch the amp, or attempt to turn it back on until the shutdown procedure is complete.

## [Full Manual](/pdf/ACOM-2000A-manual.pdf)