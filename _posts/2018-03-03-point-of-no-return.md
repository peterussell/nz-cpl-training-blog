---
layout: post
title:  "Point of No Return"
date:   2018-03-03 18:28:00
categories: nzcpl
---

# Point of No Return (PNR)

 * Point along a track from the departure aerodrome beyond which there is insufficient fuel remaining
   to return to the aerodrome and arrive with required fuel reserves.
 * An **on-track PNR** is the one described above.
 * An **off-track PNR** is where the PIC may elect to divert to an off-track aerodrome without the
   need to return to the departure aerodrome.

*We will not discuss off-track PNRs here.*

 * PNR is based entirely on the **amount of fuel carried**.
 * We can calculate the **total endurance** (or maximum endurance) which is to **dry tanks**. This is
   usually a bad idea.
 * Alternatively, we can calculate the **safe endurance**, which is total endurance less:
    * Unuseable fuel.
    * Fuel for reserves.
    * Fuel for holding.
    * Fuel for instrument approaches, possible diversions, other contingencies.
 * PNRs are often calculalated for long over-water flights, but are useful in other situations, eg.
   short flights without suitable alternates.
    * For flights over land with lots of alternates, PNRs are not often required.

**Reasons for a PNR**

 * Forecast at destination may be bad, but forecast to clear by the time you arrive. PNR allows you
   to calculate the point to make a continue/don't continue decision.
 * For *pressurised aircraft* there is often significant fuel penalty when force to fly at low altitudes
   (eg. depressurisation, engine shut-down). It may be impossible to return to the departure aerodrome
   in these situations.

# Difference between PNR and ETP

 * ETP is concerned with the *time* to return or continue.
 * PNR is concerned with a point where *fuel* determines whether returning to the departure is an option.

At the ETP, there will always be enough fuel to fly to the departure or destination, meaning *the PNR is
always further from the departure aerodrome than the ETP.*

**Fuel Load and PNR**

 * Since fuel is the main factor for PNR, it follows:
    * Increase in fuel moves the PNR toward the destination, possibly even past it.
    * Shorter distances between departure and destination mean the PNR is closer (or past) the destination.
 * In contrast, the ETP isn't affected by changes in fuel load (assuming there's sufficient fuel to fly
   from A to B).

**Remember: PNR is a fuel consideration. ETP is a time consideration.**

# Location of the PNR

 1. Determine the **safe endurance:** flying time remaining using the current *flight fuel available*, being
    burned at a constant rate.
     * **Flight Fuel:** total fuel - (unusable fuel + regulatory (or greater) reserves).

**Safe endurance = flight fuel available / fuel flow rate (per hour)**

*Example: if we have 265 litres of flight fuel available, and fuel flow is 55 litres per hour, what is the
**safe endurance**?

Safe endurance = 265 / 55 = 4.8 hours = 4 hours 48 minutes

 * In nil-wind conditions, our PNR is the distance we cover in 2h 24m. Then we have 2h 24m fuel remaining
   to return to the departure aerodrome.

 2. Because we almost never fly in nil-wind conditions, we need to derive a formula which takes into
    account GS. As with the ETP, isn't not necessary to know how to derive the formula, just to remember
    it (although we'll derive it here).

Let:

 * D = distance to PNR
 * O = GS *out* to PNR
 * H = GS *home* from PNR
 * T = time *out* to PNR
 * E = aircraft safe endurance (ie. allowing for reserves) in hours.

Since we know that: distance OUT = distance HOME, and that distance = time x speed...

T x O = (E - T) x H
=> OT = HE - HT
=> OT + HT = EH
=> T(O + H) = EH
**=> T (time to PNR) = EH / (O + H)**

To find the *distance* to the PNR, recall that distance = speed x time, where time = EH / O+H, and speed
is the GS out = O

=> D to PNR = (EH / (O+H)) x O
**=> D to PNR = EHO / (O+H)**

*Be careful with units of time, we'll get a **decimal** answer which we **need to convert to time**. To
do this we can use the fact that 1/10th of an hour is 6 minutes (60 / 10), use this to multiply the decimal
part of the answer to get minutes.*

*Example: 0.15hrs = 6 x 1.5 = 9 minutes.*

 * When the same average wind component applies to both outbound and home legs:**
    * O + H = 2 x TAS.
 * *Example: 150 kt TAS, wind component + 35kt outbound.*
     * *O = 150 + 35 = 185 kt GS.*
     * *H = 150 - 35 = 125 kt GS.*
     * O + H = 185 + 125 = **300 kt.**
     * TAS x 2 = 150kt x 2 = **300kt.**

# Using the Navigation Computer to Calculate Distance to PNR

**Method 1** - requires two settings

*Setting 1:*

 * Set safe endurance (E) on the outer scale, and O + H on the inner scale.
 * Opposite O on the inner scale, place a mark (or note the reading) on the outer scale.

*Setting 2:*

 * Rotate the disc until *10* lies under the mark (or reading remembered from before).
 * Against H on the inner scale, read the answer in nm on the outer scale.

**Method 2** - works out the time to PNR using the GSO. Distance can be calculated easily from this answer.

Recall that *time* to PNR is: **EH / O + H** (remember this is decimal time).

 1. Determine E x H and O + H.
 2. Set E x H on the outer scale against O + H on the inner scale.
 3. Opposite *10* on the inner scale, read time (decimal) on the outer scale.
 4. Convert decimal time to hours and minutes.
 5. Set O (GS Out) on the outer scale against 60 on the inner scale (rate), and read distance to
    PNR on the outer scale against time (in hrs/mins) no the inner.

*Example:*

 * *Flight fuel avialable = 360 litres.*
 * *Constant fuel flow of 68 litres/hour.*
 * *Cruise TAS is 160 kt.*
 * *Forecast wind component = +45kt.*

 1. Safety Endurance = 360 litres / 68 litres/hour = 318 minutes = 5.3 hours
 2. E x H = 5.3 x (160kt - 45kt) = 5.3 x 115
 3. O + H = (160 + 45 = 205kt) + (160 - 45 = 115kt) = 320kt (*NB. = 2x TAS = 160 x 2 = 320*).
 4. 5.3 x 115 / 320 = 129.375 = 1.9 hours
 5. 1.9 hours = 1 hour (6 x 9 = 54) 54 minutes: **Answer: 1h 54 minutes**.

Now find distance:

 1. Set rate = 205 kt (GSO).
 2. Read the answer over the inner time of 1h 54m, = 390 nm.

*Example 2:*

*Find the location of the PNR for:*

 * *Available flight fuel = 188 litres.*
 * *Consumption = 48 litres/hour.*
 * Cruise TAS = 180 kt.*
 * Wind: -25 kt.*

Safety endurance = 188 l / 48 l/h = 3.9 (E)

O = 180-25 = 155kt
H = 180+25 = 205kt

O+H = 360 (TAS x 2).

EOH / O+H = 3.9 x 155 x 205 / 360

**=> Distance = 344 nm from the departure aerodrome.**

# Conclusion

 * **PNR is a fuel consideration, ETP is a time consideration.**
 * Distance to the PNR for any flight depends on the flight fuel available. Any change (eg. holds, fuel
   loading etc.) will change the PNR.
 * Calculation to the ETP has nothing to do with the fuel carried.
 * After passing the PNR, a return to the departure or alternate isn't possible (legally or for whatever
   consideration was used). Return after passing the ETP may well be possible, it only means it's *faster*
   to get to the destination.
 * O in the ETP formula os *GS On*, in the PNR formula it is *GS Out*.
 * In nil wind, the ETP will be equidistant between departure and destination. The PNR will be half the
   distance given by the safe endurance of the fuel carried.
 * Any wind component (head *or* tail) will bring the PNR closer to the departure aerodrome. **The stronger
   the wind, the closer to the departure aerodrome.**

