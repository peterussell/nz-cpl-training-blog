---
layout: post
title:  "Equi-time Point"
date:   2018-03-01 20:33:00
categories: nzcpl
---

# Equi-time Point (Critical Point)

The ETP or CP (Critical Point) is *the point along track from which it takes the same time to return to
the departure aerodrome as it would to continue to the destination* (ignoring reversal turn time).

 * **Groundspeed Home (GSH)** = *groundspeed* from departure aerodrome to ETP.
 * **Groundspeed On (GSO)** = *groundspeed* from ETP to destination aerodrome.

# Effect of Wind

 * In nil wind conditions, GSO and GSH are equal, and the ETP is halfway between the aerodromes.
 * Normally there will be a wind component:
    * **Headwind:** GSO will be less (slower) than GSH, meaning the ETP moves toward the destination.
    * **Tailwind:** GSO will be greater (faster) than GSH, meaning ETP moves toward the departure.

In general: **the position of the ETP will always move into the wind, away from the mid (or equi-distance)
point.**

# Equi-time Point Formula

*NB. We will cover the derivation, but it's really only necessary to remember the formula and be able to
apply it quickly in practical ETP situations.*

 * We'll consider two aerodromes, A and B, which are a distance D apart.
    * X represents the distance from the departure aerodrome to the ETP.
    * Therefore, D - X is the distance from the ETP to destination.
 * We know that speed = distance / time. We can rearrange for time: time = distance / speed.
 * If we let H be GSH (between the ETP and A), then we have:
    * time = (unknown)
    * distance = X
    * speed = H
    * **New formula:** (time between ETP and A) = X / H.
 * Similarly, if we let O be the GSO (between the ETP and B), then we have:
    * (time between ETP and B) = (D - X) / O
 * Because the time between the ETP and A is equal to the time between ETP and B, we get:
    * X / H = (D - X) / O
 * This can be simplified to:

**Equi-time point formula: (D x H) / (O + H)**

 * D = full distance (A -> B)
 * H = GSH
 * O = GSO

This can be further dividied by H (both sides of the equation) to give a formula that can be used on
the computer:

"D / O + H" is the 'starting datum for all computer solutions for an ETP.'

**Headwind/Tailwind**

 * A headwind component is negative (eg. -30 is a 30 kt headwind). Tailwind components are positive (eg.
   +45 is a 45 kt tailwind).

# Examples

*Example 1: find the ETP between A and B:

 * A and B are 450 nm apart.
 * TAS cruise is 150 kt.
 * Headwind component (A to B) of 20 kt.
    * -> outbound leg is -20 kt, home leg is +20 kt
 * Having found the ETP, calculate flight time from A to ETP.

**Answer:**

 * GSH (H) = 150 + 20 = 170
 * GSO (O) = 150 - 20 = 130
 * D = 450

From the formula **(D x H) / (O + H)** we get:

 * (450 x 170) / (130 + 170) = 76500 / 300
 * = 765 / 3
 * = 255 nm
 * **=> the ETP is 255 nm from A**

**Calculate flight time to the ETP from A:**

 * Set rate as 130 kt, read the answer (on the inner circle) under 255 nm (on the outer circle):
    * **120 minutes = 2 hours.**

*NB. you can sanity check this by ensuring the ETP back to A is the same as ETP on to B:*

 * Set rate as 170 kt, read time against the distance of A -> ETP (255 nm): ~90 minutes.
 * Set rate as 130 kt, read time against the distance of ETP -> B (450-255 = 195): ~90 minutes.

# Two Wind Components

It's possible wind will change, especially over long distances. In CPL exams it's customary to give two
wind components, one for each sector (A -> ETP, ETP -> B). **Be careful to reverse the first sector
wind component when calculating GSH.**

**Example 2: find the ETP between A and B:**

 * A and B are 580 nm apart.
 * Wind from A -> ETP is -40 kt (40kt headwind).
 * Wind from ETP -> B is +20 kt (20kt tailwind).
 * TAS is 210 kt.

 * What is the distance of the ETP from A?
 * What is the elapsed time for the outbound flight from A to ETP?

**i) What is the distance of the ETP from A?**

 * GSH is 210 + 40 = 250 kt.
 * GSO is 210 + 20 = 230 kt.
 * Distance is 580 nm.

=> x = DH / O + H = 580 x 250 / 230 + 250
=> x = 145000 / 480
=> x = 302 nm

**ii) What is the elapsed time for outbound flight from A to ETP?**

 * Be careful: outbound rate is 210 - 40 = 170 kt
 * Set 170 kt over rate, read the time under the distance of 302 nm:
    * **~106 minutes, = 1 hr 46 minutes.**

**Check the answer:**

 * Time from ETP -> A: set rate as 250 kt, read time for 302 nm = ~73 minutes.
 * Time from ETP -> B: set rate as 230 kt, read time for (580 - 302 =) 278 nm = ~73 minutes.
