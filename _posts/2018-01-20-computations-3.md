---
layout: post
title:  "Computations (3)"
date:   2018-01-20 15:50:00
categories: nzcpl
---

# Conversions

**Distances**

**Nautical Mile, to Statute Mile, to Kilometre**

 * 1nm = 1.15sm = 1.852km = 1852m

To do a conversion using the computer:

 1. Identify the quantity of the known unit on the inner scale, then turn the inner scale until the
    quantity is aligned with the unit index written on the outer scale.
 2. Locate the index of the required unit on the ouer scale and read the answer against it on the
    inner scale.

*Example: Convert 35nm to SM and KM.*

 1. Find 35 on the inner scale and align it with the outer scale NM index.
 2. Find statute miles (STAT) on the outer scale, and read the value on the inner scale below it.
 3. Repeat for KM

Answers: 35nm = 40 1/2 SM = 65 km.

**Feet to Metres, and Metres to Feet**

 * 1 metre = 3.28' (rounded to 3.3')
 * 1' = 0.304m

 1. Set the index for FT against the index for METERS
 2. Read feet on the outer scale against metres on the inner scale.

*Example: Convert 4 metres to feet:* Answer = 13.2'.
*Example: Convert 50 metres to feet:* Answer = 164.2'.
*Example: Convert 23' to metres:* Answer = 7 metres.

**Weights**

**Pound to KG, KG to Pound**

KG is the internationally accepted unit, although LBs are still used.

 * 1kg = 2.205 lb, 1 lb = 0.453 kg

These are commonly rounded to 2.2 and 0.45.

Conversions on the E6-B work similarly to feet and metres:

 1. Find KG on the inner scale and LBS on the outer scale.
 2. Align the indices for the two values, and read conversions off the respective scales.

*Example: convert 525kg to lbs*

 1. Align KGS and LBS indices
 2. Find 525 on the inner (KGS) scale (52.5)
 3. Read the corresponding value in lbs from the outer scale: 11.55
 4. Convert to a reasonable value: 1,155.0 lb (1,160 lb).

NB. electronic calculator gives 1157.6 lb, highlighting the limitations of accuracy with the E6-B.

**Volumes**

We're concerned with the **US Gallon**, **Imperial Gallon**, and **Litre**.

These conversions are **incredibly important when dealing with fuel etc.**, should commit these to
memory:

 * 1 Imperial Gallon = 4.546 litre = 1.201 US gal
 * 1 US gal = 3.785 litre = 0.832 Imp gal

As *approximations for determining decimal points*, you can use 1 US/Imp gal ~ 4 litres, and US and
Imperial gallons are roughly equivalent.

The three units are shown on the outside scale of the E6-B.

To convert US gal to Imp gal or Litres:

 1. Place the volume you want to convert under the US GAL index.
 2. Read the number of Imperial gal under the IMP GAL index, or the number of litres under the LITERS
    index.

The technique is the same for the other conversions.

*Example: convert 12 US gal to Imperial gal and Litres*

 1. Set 12 under the US GAL index.
 2. Read off the value under IMP GAL: 10 Imp gal.
 3. Read off the value under LITERS: 45.7 l.

*Example 2: convert 245 Imp gals to US gals and Litres*

 1. Set 245 (24.5) under IMP GAL.
 2. Read off the value under US GAL: 29.5 US gal
 3. Read off the value under LITERS: 11.4 litres
 4. Check the answers, 29.5 US gal should be 295 US gal, and 11.4 litres should be 1,140 litres (approx
    4x the value for imperial gallons).

**Converting Volume to Weight**

Since fuel plays a big part in all-up weight (AUW), it's important to convert gallons or litres to
pounds or kilograms correctly.

 * In New Zealand the standard unit of volume is the **litre**, but could be any combination from
   aircraft manufacturers, etc.
 * Fuel gauges are usually calibrated in US gallons (sometimes imperial gallons).
 * Further complicating things, Imperial gallons are measured in pounds, but litres in KG. It's important
   to make sure your units are consistent when doing calculations.

**Specific Gravity**

The weight of a fluid, eg. aviation fuel, is determined by its **specific gravity (sg)**, which is linked
to the weight of water:

**Specific Gravity (sg) = weight of a particular fluid / weight of the same volume of water.**

Meaning water has a sg of 1, fluids lighter than water have a sg of less than one, and fluids heaver
than water have an sg of greater than one.

Further complications come from the fact that weight of fuel per volume, and therefore its sg, is not
constant - it can be affected by temperature and component mix.

However, we commonly accept that the **sg of AVGAS is 0.72**. This means, (because a litre of water
weighs 1kg), that:

 * **A litre of AVGAS weights 0.72kg.**

Some computers us 0.72kg, some use 0.71kg, and some provide a range you can choose from. Therefore the
weights from different computers may be different.

The following table gives exact equivalents of volumes of AVGAS (sg = 0.72) to weights in pounds
and kilograms.

 * 1 Imp gal = 7.2 lb = 3.27 kg
 * 1 US gal = 5.99 lb = 2.72 kg
 * 1 litre = 1.58 lb = 0.72 kg

Using the E6-B, you can convert US gals, Imp Gals, and litres directly **pounds fuel**. You cannot
read off kg fuel, but you can go **directly to litres, then multiply by 0.72 which gives kg**.

**Note that FUEL LBS on the outer scale is *not the same as* LBS.**

To assist with approximating decimal points in conversions, you can use the following (approximate)
values:

 * 1 kg = ~2 lb
 * 1 US gal = ~6 lb
 * 1 Imp gal ~7 lb
 * 1 Litre = ~1.5 lb

 * 1 lb = ~0.5 kg
 * 1 US gal = ~2.5 kg
 * 1 Imp gal = ~3.0 kg
 * 1 Litre = ~0.7 kg

To convert volume of fuel to pounds:

 1. Set the volume amount on the inner scale against the applicable unit on the outer scale.
 2. Read the weight in pounds under FUEL LBS.
 3. Convert the value to whatever units are required.

*Example: Convert 65 US gal of AVGAS (sg .72) to kg and lb.*

 1. Set 65 on the inner scale against the US GAL index on the outer scale.
 2. Read the weight under FUEL LBS: 39.
 3. Make a commonsense check: 1 US gal = ~ 6 lb, therefore it must be 390 lb.
 4. Convert 390 lb to kg: put KG on the inner scale against lb on the outer.
 5. Read the value on the inner scale against 39 on the outer scale: 17.7.
 6. Make a commonsense check: 1 lb = ~ 0.5 kg, therefore the value must be 177 kg.

Answer: 65 US gal of AVGAS is roughly 390 lb, or 177 kg.

*Example: your fuel gauge shows 6 US gal in the tank. When you have finished refuelling it shows
22 US gal. How many *litres* of fuel have you taken on, and what is the weight in lb and kg?*

 1. You've taken on (22 - 6) = 16 US gal.
 2. Set 16 on the inner scale under US gal, and read the value under LITER on the outer scale: 60.5 litres.
 3. Commonsense check, 1 US gal = ~4 litres, and 60.5 litres is about 4x 16, so looks good.
 4. Under FUEL LBS read 96 lb
 5. Set KG under LBS.
 6. Under 96 lb on the outer scale, read the value for KG on the inner scale: 43.5 kg

Answer: you have uplifted 60.5 litres of fuel, weighing 96 lb, or 43.5 kg.

**Converting &deg;C to &deg;F**

There is a conversion scale near the bottom of the calculation side. Just read the corresponding value
off the conversion scale.
