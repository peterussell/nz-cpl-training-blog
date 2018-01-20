---
layout: post
title:  "Computations (2)"
date:   2018-01-20 14:39:00
categories: nzcpl
---

# Calucator Side (cont'd)

**Arithmetic on the Computer**

 * Calculator side can be used for solving arithmetic problems.
 * Due to the scale, accuracy is limited to about three digits.

**Multiplication**

Multiplication and division are based on setting **10** and then reading the answer on the
corresponding scale. Examples below:

*eg. 6.8 x 13.5*

 1. Set **10** on the inner scale under the first number (on the outer scale), ie. set 10 under
    6.8.
 2. On the inner scale, go to the second number (13.5).
 3. Read the answer off the outer scale: 92.

*NB. the correct answer is 91.8, but 92 is the closest approximation we can get with these scales.*

**Division**

*eg. Divide 120 by 8.*

 1. Set 12 (representing 120) on the outer scale, against 80 (representing 8) on the inner scale.
 2. Go to 10 on the inner scale and read the answer on the outer scale: 15.

**Ratios/Proportions**

 * The navigation computer can be used to calculate ratios or proportions.
 * **Whenever time is involved** it is always set **on the inner scale.**
    * It's often easier to convert hours and minutes to just minutes, eg. 1:10 = 70 minutes. The
      inner scale shows this for you, eg. 1:30 is against 90 (minutes), 1:50 is against 11 (110 minutes).

*Example: You used 45L of fuel in 1:10. How much fuel would be used in the next 11 minutes?*

 1. Set 45 on the outer scale against 70 on the inner scale.
 2. Find 11 on the inner scale, and read the answer off the outer scale: 71.
 3. 71 litres doesn't make sense (we used 45L in 1:10), so the answer must be 7.1L.

*Example 2: You've covered 35 NM in 15 minutes. How far will you travel in the next 9 minutes?*

 1. Set 35 on the outer scale against 15 on the inner.
 2. Find 9 (90) on the inner scale, and read the answer on the outer scale: 21 NM.

# Speed, Distance, Time

Recall that Speed = distance / time. There's a *direct* relationship between speed and distance, and an
*inverse* relationship between speed and time.

 * We said before that **time is always on the inner scale**, we can now add that **distance is always
   on the outer scale.**
 * The number 60 on the inner scale (ie. 1 hour) is important. When set against any number on the
   outside scale, that outer number becomes the **reference speed**.
    * eg. if you set 60 against 11, then that's 110 NM/hour. You can then see how far you'd travel for
      any division of time (eg. 15 minutes, 90 minutes) at that speed.
    * This works the other way around too, after setting a reference speed you can see how long it
      would take to travel a given distance at that referenced speed.
    * Finally, if you know the distance travelled and the time taken, you can set the time under the
      distance and **read the speed above the 60 arrowhead**.
    * *eg. if you travel 38 minutes to travel 70nm, what is your speed? (110kts).*

*Example: your groundspeed is 135kt, how far will you travel in 11 minutes?*

 1. Set 60 under 135 (reference speed).
 2. Find 11 on the inner scale and read the distance off the outer scale: 25nm.
 3. Does 25nm make sense? We travel approx 67nm in half an hour, and 33nm in 15 minutes, so 25nm is a
    sensible answer.

*Example 2: chart measurement shows you've travelled 65 nm in 35 minutes. What's your groundspeed?*

 1. Set 35 on the inner scale under 65 on the outer.
 2. Find the rate index (60) on the inner scale, and read the speed off the outer scale: 11.2.
 3. Does 11.1kts make sense? No - in 70 minutes we'd travel 130nm, so multiply 11.1 to get the
    answer: 111kts.

**Determining ETA**

This is exactly the same as the 'how long will it take me to travel Xnm?' question above, except use
the distance remaining to your destination on the outer scale. Set the rate to your groundspeed, and
then read the **Estimated Elapsed Time (EET)** off the inner scale. Add that to your current time and
you'll get your EET.

# Fuel Calculations

There are a number of challenges with fuel calculations:

 * Most US-built light aircraft have consumption figures in US gal, but refuelling is done in litres,
   and fuel gauges are shown in US gal.
 * Many refer to the Imperial gallon, which is slightly *larger* than the US gallon.
 * There is the problem with specific gravity of fuel, which can vary (discussed shortly).

Fuel calculations are similar to the speed/distance/time calculations. When two of three factors of
fuel used, time, and rate are known, we can determine the third using the same computer technique.

**Time is on the inner scale, fuel in litres or gallons is on the outer scale.**

**Because fuel consumption is expressed in litres or gal per hour, the 60 mark points to the hourly
consumption rate** (same as groundspeed/time/distance).

*Example: fuel consumption rate is 42L/hour. How many litres will be consumed in 40 minutes?*

 1. Set 60 against 42 on the outer scale.
 2. Find 40 on the inner scale and read the fuel consumed on the outer scale: 28.
 3. Does 28L make sense? if we use 42L per hour, then 28L makes sense for 40 minutes, answer is good.

Similarly, you can used a known amount consumed over a known time to calculate your fuel consumption
rate:

*Example: if you've used 7L in 10 minutes, what is your fuel consumption rate?*

 1. Set 7L on the outer scale against 10 minutes on the inner scale.
 2. Read the consumption rate against 60: (just over) 42L/hour.

Importantly, if you know the fuel remaining and consumption rate, you can calculate time to fuel
exhaustion.
