---
layout: post
title:  "Relative Bearings and Total Correction (CPL Only)"
date:   2018-02-04 20:48:00
categories: nzcpl
---

# Relative Bearings and Total Correction (CPL Only)

Recall from earlier (Chapter 2):

 * **Aircraft heading + relative bearing = bearing from the aircraft to the point.**

*(Recall that 'relative bearing' means the angular difference from the direction of the nose of the
aircraft to a line pointing at an object. Eg. an object off the right wing has a relative bearing of
090&deg;. These can be converted to &deg;T by adding 20&deg; (remember &deg;T -> &deg;M is subtract,
so &deg;M to &deg;T is added).

Also recall that when calculating **track error** there is a point **from** where the track error starts
(where TMG deviated from planned track), and a point **to** which the closing angle applies. These two
angles produce the total correction to regain track at the finishing point.

We can use relative bearings and aircraft headings to calculate both the TE and the CA.

**Bearing FROM the origin after experiencing drift**

Consider that you've left A and are flying to B on a heading of 070&deg;. After a period of time you figure
that you've drifted off the planned track, and A now has *relative* bearing of 170&deg; (it's behind and to
the right).

You can then calculate that the bearing *to* A is 070&deg; + 170&deg; = 240&deg;.

Therefore, the bearing *from* A is the reciprocal of 240&deg; = 060&deg;.

Based on this, we can conclude that 060&deg;**M** has been your TMG.

Since your required track was 070&deg;, but your TMG was 060&deg;, we can calculate you've experienced a
track error of 10&deg; to the left (port). By altering 10&deg; right, you will parallel the track.

**Bearing TO the destination (CA)**

Assume that you get a relative bearing to the destination B of 005&deg;.

By adding your current heading of 070&deg;M to the relative bearing of 005&deg;, you get a magnetic
bearing TO B of 075&deg;M (095&deg;T).

Therefore, we can get the total correction by adding TE to CA:

Track Error = 10&deg;
Closing Angle = 005&deg;

=> Total Correction = 15&deg; right.

Given the original heading was 070, by flying a new heading of 070+15 = 085&deg;, you will fly directly
to B.

**Summary**

**To calculate Total Correction (TC) using relative bearings:**

 1. Take a relative bearing from the point behind.
 2. Calculate the bearing TO the point (aircraft heading + relative bearing).
 3. Take the reciprocal to calculate the bearing FROM.
 4. Compare this to the track required (planned), this is the Track Error (TE).
 5. Take a relative bearing to the place ahead.
 6. Add to the aircraft heading to get a bearing TO the point.
 7. Compare to your current heading, this gives you the Closing Angle (CA).
 8. Add Track Error (TE) to Closing Angle (CA) to get Total Correction (TC).
 9. Combine the TC value with your current heading to find the heading to fly to the point ahead.

**Be careful with &deg;M and &deg;T.**

*Example: the track between A and B is 040&deg;T. You've computed a heading of 026&deg;M, variation is
21&deg;E.

While enroute you establish that A bears 176&deg;R, and B bears 351&deg;R.

What is the new magnetic heading to make good B?*

 * Bearing TO A = 026&deg;M + 176&deg; = 202&deg;M.
 * Bearing FROM A = 202 - 180 = 022&deg;M ... => TMG = 022&deg;M
 * Required track between A and B is 040&deg;T - 21&deg;E variation = 019&deg;M
 * => TE = difference between required track and TMG = 022 and 019 = 3&deg; right (starboard)

 * Bearing TO B = 026&deg;M + 351*deg;R = 017&deg;M
 * CA is the difference between required track (planned) and bearing to B = 019 and 017 = 2&deg;
 * TC = TE + CA = 3&deg; + 2&deg;
 * => TC = 5&deg; left.

Therefore, the new heading is the original computed heading (026&deg;M) minus 5&deg; (for left correction)

New heading to arrive at B = 026 - 005 = 021&deg;M.

*Example 2: Req'd track between A and B is 119&deg;M. Variation is 21&deg;E, deviation is 3&deg;W.
Your heading is 127&deg;C.
While enroute, A bears 168&deg;R and B bears 003&deg;.
What is the required heading to make good B?*

Answer: 139&deg;M (160&deg;T) -- check deviation to obtain &deg;C.

# Calculating Distance Off (with E6-B)

When TE and CA have been determined, you can calculate distance off track with the navigation computer,
as in the 1-in-60 rule.

G/S and times bearings are taken can also be used to first calculate distance gone if unknown.

Recall: **( 60 / Distance Gone ) = ( Track Error / Distance Off )**

Which can be rearranged to get:

**( Distance off / Distance Gone ) = ( Track Error / 60 )**

*Example: TE of 5&deg; right, determined when the aircraft had covered 80 nm.*

 * Place 5&deg; (50) on the outer scale above 60
 * Above the distance gone (80) read the distance off:

Answer: 6.7 nm

*Example 2: Depart at 1250 UTC on 120 nm track. Relative bearing obtained at 1308 UTC, which determines
a closing angle of 9&deg;. G/S is 132 kt.

What is the track error, and what is the new ETA?*

TE = 12 nm left of track.
New ETA = 36 mins (132 kt for 80 nm) + 1308 = 1344 UTC.


