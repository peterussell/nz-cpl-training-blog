---
layout: post
title:  "Compass Direction"
date:   2017-12-19 19:10:00
categories: nzcpl
---

# Compass Deviation

 * Some aircraft components and metals affect compass accuracy, called *deviation*.
 * For a north reading, the resulting indication on the compass is called **compass north**.
 * **Deviation is reduced *via calibration* to 3&deg; or less.**
 * Correction for the remaining deviation (after calibration) is listed on a *compass deviation
   card*.

Corrections between compass and *magnetic* direction can be applied using the following:

 * **Deviation East = Compass Least**
 * **Deviation West = Compass Best**

True -> (variation) -> Magnetic -> (deviation) -> Compass

# Compass Swing

 * A compass swing is the method a maintenance engineer uses to calculate the deviance at
   regular intervals. It involves checking the readings of the compass against a 'master'
   compass.
 * The result is a graph showing deviation through all 360&deg;, and the compass card is filled
   out using this information.

*Examples*

 * *If magnetic direction is 054&deg;M with a deviation of 2&deg;W, you should fly a heading
   of (054 + 2) = **056&deg;C.***
 * *If magnetic direction is 189&deg;M with a deviation of 3&deg;E, you should fly a heading
   of (189 - 3) = **186&deg;C.***

Of course, the opposite applies for the common case of converting a magnetic heading to a
compass heading.

 * *If compass direction is 212&deg;C with deviation 1&deg;E, magnetic direction is 213&deg;M.*
 * *If compass direction is 344&deg;C with deviation 2&deg;W, magnetic direction is 342&deg;M.*

**Keep in mind, *compass best* means the compass reading will be the higher of the two,
*compass least* means the compass reading will be the lower of the two.**

**Deviation (summary**

 * Varies with heading changes.
 * Different for every compass.
 * Change if the same compass is transferred to another aircraft.
 * Must be determined on a regular basis.

# Bearings

**True Bearing**

 * When a line is drawn on a chart, the direction between start and finish is a **True Bearing**.
    * *eg. on a Visual Navigation or Planning chart, the line drawn between Wellington and Taupo has
      a value of 027&deg;T from Wellington. It can be said that Taupo bears 027&deg; True **from**
      Wellington.*
    * *eg2. similarly, Wellington bears 207&deg; True from Taupo. This can also be expressed as
      207&deg; True **to** Wellington.* This is often referred to as a **true back bearing**.

A **true bearing** can be defined as the angular difference from True North of a straight line drawn
between two places. True Bearings are either TO or FROM.

**Magnetic Bearing**

A magnetic bearing is a true bearing **corrected for variation**.

 * *eg. True bearing FROM Christchurch to Hokitika is 305&deg;T with variation of 23&deg;E. Therefore
   the magnetic bearing is (305 - 23) = 282&deg;M. Similarly, the magnetic bearing from Hokitika TO
   Christchurch is 102&degM.*

**Compass Bearing**

A compass bearing is a magnetic bearing **corrected for deviation**.

**Relative Bearing**

The bearing of an object **measured clockwise in degrees from the nose of the aircraft.** These
are used extensively for navigation because they can determine the aircraft position in relation
to a ground or other feature.

 * A simple method is using clock increments of 30&deg;. Eg. 2 o'clock means it's (2 x 30&deg;)
   60&deg; to the right of the nose, etc.
 * This is useful for some cases, but not for aeronautical navigation.

 * Relative bearings are expressed in degrees and the letter R.
    * *eg, an object off your right wing has a bearing of 090&deg;R.*
    * *If you were to turn to face the object (off your nose) it would have a bearing of 000&deg;R.*
 * The term **relative back bearing** is sometimes used to refer to the position of a point
   relative to the tail of the aircraft.

**Converting Relative to Magnetic or True**

**Aircraft Heading + Relative Bearing = Magnetic Bearing**

(If we wanted to plot this line on an aeronautical chart, we would *add* easterly variation, or
*subtract* westerly variation to get a True Bearing).

**Example**

For an aircraft with a *True* heading of 000&deg;, and a point that we want to fly to on a
090&deg; relative bearing (True - ie. drawn on a map), and we want to find a magnetic bearing that
will take us to the object:

 1. To track True North, with a variation of 20&deg;E we must fly (360-20) = 340&deg;M.
 2. The relative bearing is still 090, but from 340&deg;M.
 3. 340&deg;M + 090&deg;R = 430&deg;M = 070&deg;M.

Therefore to fly to the object, we should fly a bearing of 070&deg;M.

If we wanted to plot the relative bearing line on chart, we need the True bearing, therefore:

 4. 070&deg;M + 20&deg variation = 090&degT.

The practical aspects of these calculations are:

 * To steer to the chosen point, we fly a magnetic heading of 070&deg;.
 * To draw a line on the chart to the chosen point (True bearing), we draw a line of 090&deg;T.

*ARM = Aircraft Heading + Relative Bearing = Magnetic Bearing*

**Relative Bearings During Visual Flight**

The ADF (Automatic Direction Finder) will show a relative bearing when tuned. When correctly tuned,
the needle shows a relative bearing.

Therefore, you could add the &deg;R (relative bearing) shown by the needle to your aircraft
heading (&deg;H) which would give you a **magnetic bearing to the beacon.** In nil wind conditions
this would be the same as the magnetic heading to the beacon.

*To find your location on a chart* you could add 20&deg; to the magnetic bearing to get your
true bearing, then draw the reciprocal on a chart. This line would pass through your position
and give you a line to search for landmarks along and help find your position.

There will be more on this in a later chapter.

**Relative Bearings and Drift**

 * In windy conditions where you've correctly adjusted your heading to follow a consistent track,
   your heading and track will be different.
 * This will affect relative bearings - the 090&deg; relative bearing (off your right wing) from
   before will now be ahead or behind the wing depending on drift correction.
 * In this case, the relative bearing will need to be calculated with the drift correction amount.

*Example*

 * Maintaining a track of 090&deg;T, while correcting 10&deg; left (port), the nose points right
   of track.
 * This means the relative bearing is to the left of the nose, on a relative bearing of 350&deg;R.
