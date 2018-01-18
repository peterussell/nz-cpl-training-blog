---
layout: post
title:  "Computations"
date:   2018-01-19 07:45:00
categories: nzcpl
---

# Introduction

 * E6-B is a commonly used flight computer for planning and in-flight navigation. Has a **calculator
   side** and a **wind (slide) side**.

# Calculator Side

**Scales**

 * Two scales: outer (fixed) and inner (rotatable).
 * Use a logarithmic scale - distance between numbers decreases as value increases.
 * Two-digit figures on inner and outer scales **can be used to represent any value of the figure
   you select**:
    * *eg. 11 can represent 0.11, 1.1, 11, 110, etc.*
 * On the inner scale you see figures like 1:40, 1:50, 3:00 etc. These represent hours (hrs) and
   minutes (mins). **Whenever time is part of the calculation, the inner scale must be used.**
    * You can therefore see that 100 minutes (10) is equal to 1:40, 120 minutes is equal to 2:00,
      etc.

**Pressure Altitude/Temperature Window**

 * There are three cutout windows, one for each of:
    * Density Altitude.
    * True Airspeed (TAS).
    * True Altitude (not of practical importance, won't cover it here).
 * The Pressure Altitude (P Alt) and Outside Air Temperature (OAT) directly below the Density Altitude
   window is used to **determine a TAS based on a given IAS.**
    * By rotating the inner disc you can set any P Alt against any OAT, then read the Density Altitude
      from the D Alt window.
    * Recall that a standard lapse rate is 2&deg;/1000'. So standard temp at 4000' is (15-4*2) = 7&deg;C.
    * *eg. P Alt of 7000', OAT +14&deg;C, should show D Alt of near 9000' (actual: 8560').*

# Wind Side

Consists of:

 * Rotatable compass rose, outer scale of 360&deg; graudation scale with 10&deg; spacing, with an
   inner clear plastic plotting disc.
 * Two cured sections (upper and lower), holding the compass rose in place. The upper section has an
   Index at the top and a graudated drift scale left and right.
 * A solid wind slide that can be moved up and down, having concentric speed arcs and radial lines
   used to identify drift.
 * A grommet, also known as a *centre dot* at the centre of the plotting disc.

**Convert CAS to TAS**

Although the difference between CAS and TAS can be practically ignored, we have to use the term CAS
to match the inner scale.

To convert CAS to TAS, use the P Alt/OAT window:

 * Set the P Alt against OAT
 * Against CAS on the inner scale, read TAS on the outer scale.
 * *eg. 1: For CAS of 100kt, OAT +20&deg;C, and P Alt of 3000', you should get a TAS of 107kt.*
 * *eg. 2: For CAS of 150kt, OAT -7&deg;C, and P Alt of 6000', you should get a TAS of 161kt.*
