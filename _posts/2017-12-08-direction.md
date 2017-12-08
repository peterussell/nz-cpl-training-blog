---
layout: post
title:  "Direction"
date:   2017-12-08 20:41:00
categories: nzcpl
---

# Direction

 * Direction for navigation is one of 360 degrees, relative to a fixed datum.
 * Often, **cardinal** and **intercardinal** (quadrantal) points are used, eg. north, southwest,
   east, northeast. For aviation navigation we usually need to be more specific.

# Types of Direction

**True Direction**

 * Measured with reference to the **north geographic pole**, one of the points that all meridians
   pass through.
 * Determined by the angle at which a given track crosses the local meridian.
 * Lines such as tracks on **aeronautical charts for VFR operations represent *true* direction.**
   IFR charts are magnetic. We'll concentrate on VFR.
 * Tracks can be measured by protractor. Use the meridian *nearest the half-way point of the track*
   as a reference.

**Magnetic Direction**

 * The earth is essentially a large magnet with a field of magnetic force around it, also referred
   to as a *field of magnetic flux.*
 * A freely suspended compass will align itself with the flux lines and usually provide a stable
   direction with reference to the magnetic poles.
 * Magnetic and geographic poles aren't coincident. The magnetic poles complete a trip around the
   geographic poles about every 900 years.
 * A **magnetic needle** has a north-seeking end (the **red pole**) and south-seeking end (the
   **blue pole**).
 * In the aircraft, we need to convert between the magnetic north and true north by accounting
   for magnetic variation.

# Variation

 * Variation is the correction to a true direction to determine the required magnetic direction.
 * **Defined as** the angular difference between true and magnetic north at a given location.
 * It's important to note variation is different at different places, and the amount of variation
   changes over time (as the magnetic poles move).

**Isogonals**

 * Isogonals are lines joining places with the same variation.
 * They're depicted on VFR charts with the amount of variation, printed at 1&deg; intervals.

**The annual change of Variation is printed in the Legend of all aeronautical charts.**

**Agonic Line**

 * The Agonic Line is the isogonal of no (0&deg;) variation.

# Corrections

If you have true direction (eg. from plotting on a chart) and you need to get the magnetic
heading (for navigation), add or subtract according to:

 * **East is Least**
    * Subtract Variation from the true heading to get the magnetic heading.
 * **West is Best**
    * Add Variation to the true heading to get the magnetic heading.

Reverse these to convert a magnetic direction to a true direction.

The main concept is *what magnetic heading do I need to fly in order to track along a
true direction?*

**Variation in New Zealand**

 * A round figure of 20&deg;E is commonly used in New Zealand *as an average*.
   * True -> Magnetic, subtract 20&deg;
   * Magnetic -> True, add 20&deg;
 * When greater accuracy is required, use the variation from the VFR chart **to the nearest
   whole degree.**
 * When calculating variation for a track which crosses or nears multiple isogonals, use the
   variation for the *main part* (ie. the majority) of the track.
