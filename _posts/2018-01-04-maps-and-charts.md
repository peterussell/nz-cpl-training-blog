---
layout: post
title:  "Aeronautical Maps and Charts"
date:   2018-01-04 07:13:00
categories: nzcpl
---

# Projections

 * It's impossible to represent all the earth's features on one chart,s o we reduce the earth in
   size to what's called the *reduced earth*.
 * Once that's done, a section of the reduced earth is projected on a flat screen or paper, showing
   lines of latitude/longitude, etc.
 * All projections result in some degree of *distortion of shape* (think of flattening an orange
   peel). The objective is to produce charts with the least possible distortion for a specific
   purpose.
 * Mathematical applications to different projection techniques are used to produce satisfactory
   charts.

# Types of Projections

**Conic**

 * Uses a cone intersecting two parallels.
 * Shows parallels of latitude as curved/concave lines, and meridians of longitude as converging
   to a point (eg N or S pole).
 * Angle between all projected meridians and parallels is 90&deg;.
 * Example: Lambert conformal projection, **used for most NZ aeronautical charts.**

**Cylindrical**

 * Uses a cylinder placed tangential to the Equator, with the earth projected as if a light shone
   from the centre of the earth, and the light projected to the inside of the cylinder giving the
   map.
 * Straight lines of longitude and latitude, angle between them is 90&deg;.
 * Example: Mercator projection.

# Orthomorphism

Comes from Greek, meaning correct *form* or *shape* (commonly: 'conformal'). It means:

 * The scale at any point on the chart must be the same in all directions and over short distances.
 * Meridians and parallels must cross at right angles to each other.
 * Angles and bearings between features on the charts should be the same as on the earth's surface.

**Ideal Properties of Aeronautical Charts**

 * Conformal (as above), ie. scale and angular relationships between features are maintained.
 * All surface features portrayed with their true shape.
 * Great circles should be represented by straight lines (little importance to VFR navigation, but
   very important for international flights).
 * Rhumb lines should also be straight lines. However, it's *not possible on one chart to have
   straight lines for both rhumb lines and great circles*. **Rhumb lines are preferred when
   navigation is with reference to the mag. compass or other directional systems.**

**Convex and Concave**

 * For charts, always with reference to a point.
 * Concave: "making a hollow away from" (line curves away from the point).
 * Convex: "bulge towards" the stated reference (line curves toward the point).
 * *eg. would say: "Line A is convex to the North Pole.", "Line B is concave to the Equaator."

# Mercator Projection

 * Uses a cylinder wrapped around the reduced earth, with the axis of the cylinder aligned with the
   earth's axis (ie. it's aligned North-South).
 * A light source is placed in the centre of the reduced earth, and projects long/lat graticule as
   **straight lines** on the surface of the cylinder.
 * The projection is a **rectangle** when the cylinder is unrolled and placed flat.
 * **Notes:**
    * The distance between parallels of latitude *increase* toward the poles.
    * At high latitudes near the poles, the graticule cannot be projected, because the line from the
      earth's centre through the pole is vertical (and doesn't project on to the cylinder).
 * **Because the scale over the entire chart is not constant, and meridians of longitude are parallel
   to each other, the basic Mercator projection *is not orthomorphic.***
 * Some factors can be applied mathematically to make it orthomorphic, which is beyond the scope of
   this text.

**Properties of the Mercator Chart**

 * It is orthomorphic, or conformal (mathematically adjusted); bearings are correct.
 * Poles are not projected.
 * Scale is not constant, it increases away from the equator.
 * Shapes (not areas) are correctly represented.
 * Meridians are straight parallel lines, and equi-distant.
 * Parallels are straight parallel lines, distance between increases away from the equator.
 * Meridians and parallels intersect at 90&deg;.
 * Adjoining sheets of the same scale fit North/South and East/West.
 * **Rhumb lines are straight lines**.
 * **Great circles are curved convex (away from) to the nearer pole.**

**Disadvantages of the Mercator Chart**

 * Distances are difficult to measure accurately (because of scale changes).
 * Great circles (including radio bearings) cannot be plotted, as they're curves.
 * Cannot be used past **70&deg;N or 70&deg;S** because of scale expansion to infinity at each
   pole.

# Lambert Conformal Projection

 * One of the most important properties for navigation charts is **orthomorphism (conformality)**
   so correct representation of bearings is assured. The Lambert conformal conic projection
   satisfies this primary requirement.
 * All conic projections result from projecting the reduced earth onto a cone.
 * The **Lambert projection** cuts the earth's surface at **two standard parallels**. Details of
   the two standard parallels and central meridian are **printed in the Title Panel on charts that
   have been produced from this projection.
    * This is often referred to as the **Parallel of Origin (P of O)**, which is the parallel
      normally halfway between the two Standard Parallels.

**Properties of the Lambert Conformal Conic Projection**

 * Poles are projected.
 * Conformal (or orthomorphic) by construction -- **all angles and bearings between features of
   the earth's surface are correctly represented over the whole chart.**
 * The actual shapes of surface features are correct, but areas not totally so.
 * Meridians are straight lines, radiating from the nearer geographic pole.
 * Parallels are arcs, concentric and evenly spaced, concave to the same pole.
 * Meridians and parallels intersect at 90&deg;.
 * Adjoining sheets using the same standard parallels fit East/West, *but not North/South*.
 * Great circles may be treated as *straight lines* (they're slightly curved, but can be ignored
   for all practical purposes).
 * Rhumb lines are *curved lines* concave to the nearer pole.
 * Scale is considered constant over the whole of an individual chart, *however*:
    * ...there is an inevitable distortion of the **latitude scale**.
    * Specifically, the area *between* the two standard parallels is slightly 'compressed', and
      area outside the standard parallels is slightly 'expanded'.
    * Correction for this distortion is applied mathematically for every point of the chart on
      the *longitude scale*
    * The effects of this distortion are not significant because most charts cover only a small
      range of latitudes.
 * **For practical purposes, scalar distortions are insignificant - *constant scale may be
   assumed.**

**Principal Advantages of the Lambert Chart Projection**

 * Most latitudes can be projected (including polar). However, other charts are often used for
   polar regions for increased accuracy.
 * Useful for representing countries with east/west expanse, eg. USA.
 * Distances can be measured accurately.
 * Great circles can be plotted (as straight lines).

***NB. the text includes a useful summary between the projections (page 6-6).***
