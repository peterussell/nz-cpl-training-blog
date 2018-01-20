---
layout: post
title:  "Computations (4) - The Wind Side"
date:   2018-01-20 18:43:00
categories: nzcpl
---

# The Wind (slide) Side

The Wind side is used to determine groundspeed and heading to fly in order to maintain a constant
track at a given TAS under known wind velocity conditions.

The **Triangle of Velocities** is an illustration showing three vector quantities representing:

 * Heading (HDG) and TAS - **one arrow vector**
 * Wind velocity (W/V) - **three arrow vector**
 * Track (TR) and Groundspeed (GS) - **two arrow vector**

 * Recall that a vector has magnitude and direction.
 * If you add a HDG/TAS vector with a W/V vector, you get a resultant vector showing TRK/GS.
 * The procedure of drawing an measuring vector diagrams is complicated, so we use the wind
   computer instead.

**Drift** is the **angular distance between HDG and TR.** An aircraft will always drift from its
heading to its track.

To maintain a constant track, we need to angle into the wind by an amount equal to the drift. This
is called the **Wind Correction Angle (WCA), and is always (of course) in the opposite direction
to drift.

Do not confuse this with the **wind angle**, which is the angle between the track and wind direction.

# Drift

 * Expressed as left (port) or right (starboard).
 * Drift direction is fairly easy to mix up. An easy way to figure it out is that the **same wing
   that is forward to correct for drift, is the same direction the drift is acting in.**
    * *eg. if the right wingtip is forward (facing left), then you are correcting for a right drift.
      If the left wingtip is forward, you're correcting for left drift.*
 * Drift direction is the direction you would move in if you didn't apply any correction.

There are three factors that determine the amount of drift:

 1. Wind angle relative to track. Greater the angle, more drift.
 2. Wind speed (faster wind = greater drift).
 3. TAS - faster you go the *smaller* the drift (there's less time for the wind to have impact).

We calculate **anticipated** drift during pre-flight planning, and experience **actual** drift during
the flight. We may have to amend drift correction if anticipated and actual drift are different.

# Using the Plotting Disc

Most commonly used to determine a heading to fly to maintain a **required track** and maintain a
known **groundspeed**.

There are 6 components, we generally need 4 to determine the other two:

 1. TAS
 2. Heading
 3. Wind direction
 4. Wind speed
 5. Track (required)
 6. Ground speed

Typically you'll know TAS (from the operations manual), wind direction and speed, and track (from planning
on the VPC Or VNC).

Remember that you'll probably be planning in &deg;T, but need to convert to &deg;M before the flight
in order to navigate using the compass in the aeroplane.

*NB. the text works through examples of doing calculations with the E6-B which I'll omit here, given
the instructions are printed on the E6-B.*

*Example: calculate the HDG and GS for: planned track 280&deg;T, wind 320&deg; @ 20kt, TAS 110kt.*

Answer: HDG: 287&deg;T (280&deg;T + 7&deg; WCA right), GS: 94kt.

*Example 2: calculate HDG and GS for: TRK 260&deg;T, wind 140&deg;T @ 30kt, TAS 140 kt.*

Answer: HDG 249&deg; (-11&deg; WCA left), GS: 153 kt.

# Determining X-Wind and Headwind Components

 * You can calculate these using the navigation computer, or a graph - normally supplied in the aircraft
   Flight Manual, and on the reverse side of the E6-B.
 * Be careful with &deg;T vs &deg;M:
    * Wind velocities provided by MetService, eg. **METAR** or **TAF**, are in **&deg;T.**
    * Wind velocities from an **Air Traffic Service** are in **&deg;M.**
 * It's a good idea to work with headwind and crosswind components in &deg;M.

**The Navigation Computer Method**

 * Can be determined by using the plotting disc of the E6-B, or the calculator side of the E6-B using the
   headwind/crosswind component graph.
 * The CRP-1 computer has a square section on the wind slide side which can be used. The method is
   covered in the text but I'll omit it here (because I'm using an E6-B).

**Using the Plotting Disc**

 1. Set up as for a TRK/GS calculation - set wind direction under index an mark wind velocity.
 2. Set RWY heading under the index.
 3. Draw a line as accurately as possible from the mark to the centre line, at right angles to the
    centre line.
 4. Read the headwind component.
 5. Rotate the disc until the drawn line is parallel with a *radial drift line*.
 6. Read the number of crosswind knots across the line.

*Example: determine crosswind and headwind components for: Wind: 290&deg;M @ 30kt, RWY 16/34.*

Answer: headwind component = 20 kt, crosswind component = 23 kt.

**Using the Graph**

 * Consists of radial lines that identify wind direction **relative to the runway.**

*Example: for wind 020&deg;M @ 28 kt, runway 06/24, determine crosswind and headwind components.*

We'll use RWY 06 (020 - 060 = 040&deg; difference, which is the headwind runway vector).

Answer: headwind component = 21 kt, crosswind component = 18 kt.

# Finding Wind Velocity in Flight

 * You can determine wind velocity in flight by using Heading, TAS, Track, Groundspeed, and Drift.
 * Be careful with direction values - if you get a track off a chart it's in &deg;T, but if you're
   comparing to a compass reading you need to convert it to &deg;M first (or vice versa).

There are two methods here, either work and it's a matter of preference:

**1 - Setting HDG and TAS First**

*Example: Given HDG 082&Deg;C, Variation 20&deg;E, deviation on this heading 2&deg;W, CAS 132 kt,
OAT +12&deg;C, Pressure Altitude 4,500', TR 085&deg;T, Groundspeed 25nm covered in 12 mins --

What is the wind velocity in &deg;M?*

Workings: convert all data to &deg;M:

 * Compass = 082 - 2 = HDG 080 &deg; M
 * Track = 105 - 20 = 085 *deg; M
 * Drift is from 080&deg;M to 085&deg;M = 5&deg; right (starboard)
 * CAS of 132 kt converts to a TAS of 143 TAS, GS is 125 kt.

*NB. accuracy of finding wind in flight using the navigation computer is accurate up to +/- 5&deg;
and within +/- 2 kt.*

 1. Set the HDG under the index
 2. Move the grommet to the TAS of 143 kt.
 3. Make a mark where the GS of 125 kt cross the 5&deg; drift *right*.
 4. Rotate the mark to be directly under the grommet.
 5. Read the wind velocity: difference between mark and grommet = 22 kt.
 6. Read the wind direction under the index: 049&deg; M.

Answer: W/V is 049&deg;M at 22 kt.

**2 - Setting Track and GS First**

Will leave this to be covered by the text.

# True Altitude

 * **True Altitude = true height above Mean Sea Level**
 * Will only be true if altimeter is set correctly *and ISA conditions prevail* (hardly ever), pressure
   and temperature lapse rates almost always differ from ISA.
 * Also due to instrument error, which gives Calibrated Altitude.

To determine True Altitude:

 1. Calculate Pressure Altitude.
 2. Correct Pressure Altitude for temperature.

Using the E-6B:

 1. Set Pressure Altitude against temperature at the Indicated Altitude
 2. Read the True Altitude on the outer scale against the Indicated Altitude on the inner scale.

*Example: with a correct QNH of 1030 hPa set, the altimeter reads 7,500'. With OAT +12&deg;C, determine
True Altitude.*

 1. Find the pressure altitude (QNH = 1013.2 hPa):
     * 1030 - 1013 = 17
     * 30' per hPa x 17 hPa = 510' lower (pressure alt.)
     * Therefore, Pressure Altitude is 7,500 - 510' = 6,990' (close enough to use 7000').
 2. Set the Pressure Altitude (7000') against OAT (+12&deg;C).
 3. Find the CAL ALT on the inner scale and read TRUE ALT on the outer scale.

Answer: True Altitude is 7800'.

*NB. while working this out, if I used the RHS scale for temp/PA, the answer was wrong (~8500'), but
if I used the scale on the left it was OK. Need to figure out when to use which one.*
