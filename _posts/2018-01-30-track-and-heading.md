---
layout: post
title:  "Track and Heading"
date:   2018-01-29 07:10:00
categories: nzcpl
---

# Position Lines (P/L)

Defined as a **line an aircraft is known to be on at a particular time.** Can be obtained from:

 * Physical features: (straight) railway, coast, power lines, roads, etc.
 * Two or more features positioned on the TMG, providing a **transit bearing**.
 * Relative bearings from one or two visual features, or from radio navaids.

Position lines are shown on charts as a straight line with an arrowhead at each end, and time in
UTC appended at one end.

On a given position line, another line (or two) are required to obtain a *fix*, otherwise we could
be anywhere on the line. The crossing angle must be as close to 90&deg; as possible.

Accuracy using visual position lines is less accurate than radio navaids.

**Groundspeed Checks**

Position lines can be useful for determining G/S, provided they're reasonably perpendicular to
the TMG (+/-20&deg; is acceptable).

*eg. aircraft crosses a railway line at 2351 UTC, then crosses a *transit bearing* obtained from
a power line pylon and a church at 2359 UTC.*

Both lines are sufficiently close to 90&deg; to track. If the distance between them is 18nm, then
the aircraft travelled 18nm in 8 minutes = GS 135 kt.

DME can be useful for providing ground speed checks.

**Drift Assessment**

Tacking along a visual position line (eg. railroad, coastline) can be useful for determining
drift and correction. Same applies to tracking along a position line obtained from a transit bearing
based on two in-line features ahead of the aircraft.

*(Recall: transit bearing: two or more features positioned **on the TMG**.)*

# Track & Heading Corrections

 * During planning, you determined the **Flight Planned Track (FPT)**, and the HDG (heading to fly)
   to maintain that track. However, drift correction is based on forecast winds, which are likely
   to change.
 * When a change in wind velocity occurs, planned drift correction is no longer applicable and the
   aircraft will deviate from the FPT and follow a different track, called the **Track Made Good (TMG)**.
 * **The angle between *required track* and *TMG* is called the *Track Error (TE)***, specified in
   degrees left or right of required track.

*NB. there is a good diagram in the textbook, pg. 8-28, showing differences between FPT, TMG, and HDG.*

**Flight Planned Drift, Actual Drift, Track Error (summarised)**

 * Flying from Y to Z on a heading based on *flight planned drift*, a change in the forecast wind
   velocity causes the aircraft to deviate from this flight planned track along a different track
   (TMG).
 * The angle between **HDG** and **FPT** is the *flight planned drift*
 * Angle between **HDG** and **TMG** is *actual drift*.
 * Angle between **FPT** and **TMG** is the *track error*

**Getting back to FPT, and Closing Angle (CA)**

 * After realising your TMG has diverged from the FPT, you can calculate the Track Error (TE) and
   apply this correction to your current TMG. This will *parallel* the FPT.
 * Obviously we want to get back to the FPT, which requires an additional correction angle, called
   the **Closing Angle (CA)**.
 * The size of the CA depends on how quickly you want to re-establish on the FPT (large closing
   angle = shorter distance to re-establish, smaller angle = longer distance..).

**Summary / Total Correction**

We can summarise that:

 * A change of heading equal to the **track error (TE)** will parallel the FPT.
 * A further change of heading equal to the **closing angle (CA)** will bring the aircraft back to the
   FPT within a given distance.
 * The **Total Correction (TC)** is the Track Error (TE) + Closing Angle (CA).

**Totol Correction (TC) = Track Error (TE) + Closing Angle (CA)**

This formula is based on a rule of geometry which states that an *external angle of a triangle is
equal to the sum of the two opposite internal angles*. (See diagram in book).

 * Note that the **total correction is approximate**, because it assumes that G/S and wind velocity are
   constant during the correction (which is unlikely to be the case). It only applies to smaller angles.
 * **If either the TE or CA is great than 15&deg;** the approximation will be invalid and have to be
   worked out on a flight computer.

Therefore, if the TE or DA are less than 15&deg; each, the approximation provides a sufficiently valid
heading without having to use a computer.

*(cont'd in next post)*
