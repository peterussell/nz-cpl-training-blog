---
layout: post
title:  "Radio Navigation Aids"
date:   2018-03-06 07:32:00
categories: nzcpl
---

# Introduction

The purpose of this section is to give a brief technical explanation of the predominant aids. Note that
the **ADF, VOR, and DME have been removed from the PPL and CPL Navigation syllabus topic list**, meaning
most of that text here is not required reading. **GPS and Radar have been retained** and must be studied.

# Automatic Direction Finder (ADF)

 * The ADF is a radio reciever, which when tuned to a (ground-based) NDB, or any other suitable beacon,
   can indicate the direction of the NDB from the aircraft.
 * You can determine the **position line** between the aircraft and NDB

The ADF/NDB can be used for:

 * Orientation (where am I).
 * Navigation (tracking to/from a beacon).

**Components and Principles of Operation**

Four basic components:

 1. **Receiever:** plus associated control panel.
     * Used to tune the ADF to the frequency of the NDB.
     * Each NDB has a Morse code ID which must be checked.
 2. **Antenna:**
     * An ADF uses two aerials: a **loop aerial** and a **sense aerial**. Receiever combines the signals
       from these two aerials.
     * This signal activates the motor-driven needle of the cockpit indicator, so that it *points to the
       direction the signal came from.*

**The ADF needle points directly towards the selected NDB.**

 3. **Cockpit Display**
     * Consists of compass card and a needle (rotates through 360&deg;) so that:
        * (000&deg; relative) Needle points to the top of the card: station is ahead of you.
        * (180&deg; relative) Needle points to the bottom of the card: station is behind you.
        * ...
        * **NB. the needle shows a *relative bearing*.**
     * In some installations, the compass card can be rotated so the top of the card reads the magnetic
       direction being flown.
     * **The RMI** is a development of the (manually) rotatable compass card which automatically
       synchronises the top of th ecard with the magnetic heading being flown at the time.
 4. **Control Panel** - most have the following features in common:
     * Mode selector, or function switch, with the following positions:
        * **OFF** - ADF is off.
        * **ANT** or **REC** (depending on country of origin) - sense aerial only is used (loop aerial is
          off). No bearing information is obtained (needle remains steady). Prime use is to tune the beacon
          freq.
        * **ADF** or **COMP** (depending on country of origin) - ADF is fully automatic, provides bearing
          information to the NDB. *Although frequencies can be selected in this mode, the needle responds
          quickly to changes, and most training organisations teach tuning while in the ANT/REC mode.*
     * **BFO** (beat frequency oscillator) - also referred to as the **CW switch**. Adds a tone to the wave
       from the NDB to make the IDENT audible to the pilot. Not recommended when ADF (COMP) is selected.
     * **TEST** - When in automatic mode, moves the needle Left or Right, and return to its original position
       when released. If faulty, the needle in ADF mode may not move and can be hard to verify any issues.
       Therefore, *immediately after you hae seleted ADF (COMP) and the needle has stabilised, you should
       press the test button to confirm it's working properly.
     * **Frequency Selector** - digital displays are correct, older style ones have three frequency bands
       they can be tuned to so may not be. **Always check the IDENT before turning function switch to ADF.**
     * Refer to the AFM/POH for full details.
