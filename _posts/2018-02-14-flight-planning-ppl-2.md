---
layout: post
title:  "Flight Planning (PPL) (2)"
date:   2018-02-08 07:32:00
categories: nzcpl
---

*(continued from previous post)*

# Sector Times and ETAs

We can calculate sector times and fuel burn for each sector now we have GS and track length.

Leg 1:

 * GS of 86 kt, length of 44 nm.
 * On the E6-B place Rate under 86, and read the value under 44 nm: 31 minutes.

Leg 2:

 * GS 87 kt, length 42 nm
 * Rate = 87, read under 42: 29 minutes.

Leg 3:

 * GS 112 kt, length 51 nm
 * Rate = 112, read under 51: 27 minutes.

*NB: for rough estimate calculations (eg. in the air), leg 1 and leg 2 have a speed close enough
to 90 kt that we can use 1 minute = 1 1/2 nm. Leg 3 has a GS close enough to 120 kt that we
can use 1 minute = 2 nm.*

Having **EET** for each leg, we can now calculate **ETA** at each turning point:

Assuming ETD is 0100 UTC:

 * ETA Collingwood = 0100 + 31 = 0131 UTC
 * ETA Karamea = 0131 + 29 = 0200 UTC
 * ETA Nelson = 0200 + 27 = 0227 UTC

**Important:** total elapsed time = 31 + 29 + 27 = 1h 27m. ETA + 1:27 = 0227 UTC.
Verify this is the same ETA that was calculated in the ETA column.

Fuel Cruise Performance Charts

 * Most flight plan forms have a column for fuel consumption *rate* and fuel *used* per segment.
 * Remember: **day reserves = 30 minutes** (20 mins helicopters).
    * Many flight schools and other organisations require **45 minutes** reserve.
 * Use the AFM (Aircraft Flight Manual) Cruise Performance Chart to determine consumption rates.
    * You need to know AUW (AUW), TAS, and cruise altitude. You may have to interpolate between
      columns.

*NB. I'll omit the workings due to not being able to show the consumption rate table, check the
text for this exercise.*
