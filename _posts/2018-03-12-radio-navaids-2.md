---
layout: post
title:  "Radio Navigation Aids (2)"
date:   2018-03-12 21:23:00
categories: nzcpl
---

# Non Directional Beacon (NDB)

 * Ground based transmitter that broadcasts in all directions (omni-directional).
 * Basic signal is called the **carrier**, radiated at the frequency specified for the navaid.
 * In NZ: 24 hours/day, between **200kHz and 1700kHz** - in the *upper part of the low frequency (LF) band*
   and the *low part of the medium frequency (MF) band.*
 * These bands are susceptible to **static interference** (thunderstorms, heavy precipitation), and can
   also be bent/scattered by **mountainous terrain.** The result is a fluctuating (rather than steady) needle.
 * Can't do much about TS/rain, but can fly high to avoid terrain interference.

**Rated Coverage**

 * This is the range of the NDB.
 * Normally restricted to **about 200nm.** Some provide much larger ranges, mostly for international traffic.

**Identification**

 * Two-letter station idenfication & name, frequency, and ident Morse code are printed on:
    * VNCs.
    * AIPNZ ENR 4.1-1 onward.
    * Aerodrome charts in AIPNZ Vol 4.
 * Some NDBs also have voice modulation capability, and may broadcast ATIS. In some cases they may
   provide **limited voice communication in case of emergency.**
 * *NB. other broadcast stations between 200kHz and 1700kHz can be used (except for IFR), with some
   drawbacks -- infrequent identification, unreliable hours of operation, no guaranteed range.*

# Operation NDB Use

**Tuning & ID**

Before using the aid:

 * Turn function switch to REC (or ANT) (prevents the needle from moving while tuning).
 * Tune desired frequency.
 * Listen to the identification code and positively ID the station.
 * Turn function to ADF (or Comp.)
 * After the needle has homed, press TEST. Needle should swing away; once deflected 90&deg;, release test
   and verify returns to position.

**Homing to the NDB**

 * In still wind conditions, you home to the beacon by orienting the needle at 000&deg;R ('relative').
   You will eventually fly over the beacon, called **the overhead.**
    * *Recall: relative means relative to the direction of the nose.*
 * After passing over, needle should then point to 180&deg;R.
 * *With wind*, holding the same relative bearing as magnetic heading will result in drift. Can identify
   drift based on the direction the needle starts to point while holding a steady heading, then identify
   and apply correction opposite drift.

Quick reference:

 * When experiencing right (starboard) drift, the aircraft will maintain track when steady deflection
   of the needle is to the right of 000&deg;R by the same number of degrees as the drift.
 * eg. when tracking to an NDB on a track of 360&deg;M to the beacon, if the wind comes from the left
   the aircraft should point into the wind, say 10&deg;.
    * In this case, the new HDG is 350*deg;M.
    * The ADF should now to be to the right of 000&deg; by 10&deg;, ie. *it should read 010&deg;R*.
    * If this is steady, you are maintaining track.
    * If it is increasing, you're applying too much correction. If decreasing you're applying to little.

**Summary**

 * With right (starboard) drift:
    * Increase in &deg;R means you're over-allowing for drift.
    * Decrease in &deg;R means you're under-allowing for drift.
 * With left (port) drift:
    * Increase in &deg;R means you're under-allowing.
    * Decrease in &deg;R means you're over-allowing.

**Tracking Away from the NDB**

Same principle applies, except with the needle on the 180&deg;R position.

 * If drift pushes you to the right, the needle will point to the left of the tail (eg. 190&deg;)
 * If drift pushes you left, needle points right of tail (eg. 170&deg;).
 * As before, correct drift allowance is applied when the needle is steady, equal to the amount of
   wind.
 * When right (starboard) drift is being allowed for, if the number is increasing you need to apply
   more drift. If it's decreasing, apply less. Same for the other side (but the other way around).

**Summary**

 * With right (starboard) drift:
    * Increase in &deg;R means you're under-allowing for drift.
    * Decrease in &deg;R means you're over-allowing for drift.
 * With left (port) drift:
    * Increase in &deg;R means you're over-allowing for drift.
    * Decrease in &deg;R means you're under-allowing for drift.

# Magnetic Bearings - To and From the NDB

Recall from earlier that:

 * **Magnetic Heading + Relative Bearing = Magnetic Bearing**

 * It's often more useful to use Magnetic Bearing From (MBF) than MBT. Obviously if you have one and want
   to find the other, add or subtract 180&deg; as appropriate.

*Example: your heading is 020&deg;M, and ADF shows 040&deg;R, what is the MBT?*

 * MH + RB = MB
 * => 020 + 040 = 060 = MBT.

*What is the magnetic bearing from?*

 * 060 + 180 = 240&deg;M FROM.

Therefore, you are 240&deg;M from the NDB, and you would fly 060&deg;M to track to the NDB.

**Importance of Variation**

 * The above method gives you &deg;M. If you want to use this with a chart it's *crucial to remember to
   apply magnetic variation.*
 * For NZ, if the variation is 20&deg;E, then the result above would be a **true heading** of 060 + 20
   = 080&deg;T TO the NDB. This is what you would use to find yourself on a chart.
