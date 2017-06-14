---
layout: post
title:  "GS41: Flight Instruments (4)"
date:   2017-06-13 20:23:00
categories: cpl-multi-training
---

# Compass Systems

Earth is a huge magnet, spinning in space, surrounded by a magnetic field
made up of invisible lines of flux, which leave the surface at the magnetic
North Pole, and reenter at the magnetic South Pole.

Lines of magnetic flux have two important properties:

 1. Any magnet free to rotate will align with them.
 2. An electrical current is induced into any conductor that cuts across
    them.

Most direction indicators installed in aircraft make use of one of these
two properties.

# Magnetic Compass

 * One of the basic instruments required by Part 91 for both VFR and IFR.
 * A magnet is a piece of material, usually a metal containing iron,
   **that attracts and holds lines of magnetic flux**.
 * Every magnet has a north and south pole, the same poles of two
   magnets repel each other, the different ones attract each other.

**Aircraft Magnets**

 * Two small magnets attached to a metal float, sealed inside a bowl of
   clear compass fluid similar to kerosene.
 * A 'card' (graduated scale) is wrapped around the float, and viewed
   through a glass window with a lubber line across it.
 * The float/card assembly has a hardened steel pivot in its center that
   rides inside a special, spring-loaded, hard glass jewel cup.
    * The buoyancy of the float takes most of the weight off the pivot,
      and the fluid damps the card and float oscillations.
    * This jewel-and-pivot mounting **allows the float freedom to rotate
      and pivot up to approximately 18 degrees of bank.**
       * At steeper bank angles compass indications are unpredictable.

 * The compass housing is entirely full of fluid. To allow expansion
   and contraction with temperature, the back of the compass housing
   is a sealed with a flexible diaphragm, or metal bellows.

The magnets align with the Earth's magnetic field and the pilot reads
the direction on the scale under the lubber line. Note that the scale
is backward: when the pilot is flying north as indicated by the
compass, east is to the pilot's right, but 330 degrees is to the right
on the compass card.

This is because the **card remains stationary, and the housing and pilot
rotate around it.**

# Magnetic Compass Induced Errors

# Variation

 * Caused because true North is different to magnetic North, which is what
   is pointed to by magnetic compasses, and moves over time.
 * In aviation this is called **variation**, in surveying and land
   navigation it's called **declination**.

**Isogonic Lines**

Isogonic lines identify the number of degrees of variation in their area.

 * The **agonic line** is where the the two poles are aligned, and there
   is no varation (currently passes near Chicago).
    * **East** of this line, the magnetic North Pole **is to the west**
      of the geographic North Pole, and correction must be applied to a
      compass direction to get true direction.

**To convert from True to Magnetic**

 * Subtract east variations
 * Add west variations

eg. in Los Angeles, variation is 14 degrees east. To fly a *true course*
of 180, the pilot would have to fly a *magnetic heading* of 166.

eg 2. in Washington DC, variation is 10 degrees west. To fly a
*true course* of 180, the pilot would have fly a *magnetic heading* of
190.

# Deviation

 * Electric fields affect the compass (the compass aligns with *any*
   electric field).
    * Includes flowing electrical current, magnetized parts, etc.
 * These aircraft magnetic fields create a compass error called
   deviation.
 * Deviation, unlike variation, **depends on the compass heading**.
   Also, unlike variation, the aircraft's geographic location doesn't
   change deviation.

**Swinging the Compass**

This is an operation where the AMT (?) can adjust the amount of
deviation at known headings.

They position the aircraft on a compass rose, which is known to have
minimal magnetic interference. They align it with North (and then at
30 degree increments) as painted on the rose on the ground. They then
adjust the **compensator assembly** located on top or bottom of the
compass.

The compensator has two shafts whose ends have screwdriver slots. Each
shaft rotates one or two small compensating magnets. One is for E-W,
the other is for N-S.

The adjustments minimize the difference between the compass indication
and the actual magnetic heading. **Any remaining error is recorded on
a compass correction card** and placed in a holder near the compass.

**Magnetic variation must be applied *before* deviation when computing
compass headings from true headings.**

# Dip Errors

 * Earth's magnetic field runs parallel to the surface only at the
   Magnetic Equator.
 * As you move away from the equator, the angle created by the vertical
   pull of the magnetic field increases gradually.
    * This is called the **dip angle**. It increases in a downard
      direction as you get closer to the magnetic North Pole, and
      increases in an upward direction as you get closer to the
      magnetic South Pole. (Think of the north end of the compass
      being pulled down when getting close to the south pole, meaning
      the south end is pulled up.)
 * **If the compass needle were mounted so it could pivot freely in
   three dimensions, it would align itself vertically at the north
   and south magnetic poles.**
    * Because the dip angle isn't any use, the compass is mounted to
      only rotate in the horizontal plane.
 * Close to the magnetic poles, the horizontal component of the Earth's
   field is too weak to align the compass, which makes it unuseable
   for navigation.
 * Once tilted out of the horizontal plane, it will be affected by
   the vertical component of the Earth's field, which leads to
   northerly and southerly turning errors.

**Northerly Turning Errors**

 * Important principle: **the center of gravity of the compass card is
   located lower than the pivot point.**
 * When turning in a northerly direction...
 * As the aircraft turns, the force that results from the magnetic dip
   causes the float assembly to swing in the same direction that the
   float turns. The result is a false northerly turn indication.
 * Because of this lead of the compass card:

**A northerly turn should be stopped prior to arrival at the desired
heading.**

 * This error is magnified with proximity to either magnetic pole.
 * **Rule of thumb:** stop the turn 15 degrees, plus half of the
   latitude, prior to the desired heading.

**Southerly Turning Errors**

 * When turning in a southerly direction, forces are such that the
   compass assembly lags rather than leads.

**The compass card should be allowed to pass the desired heading prior
to stopping the turn.**

 * This is also amplified with proximity to the magnetic poles.
 * **Rule of thumb:** same rule of 15 degrees, plus half the
   latitude, applies - but stop after passing the heading instead.

# Acceleration Error

 * Errors are caused when on easterly and westerly headings.
 * Because of the pendulous type mountings, the *aft end* of the
   compass card is tilted upward when accelerating, and downward
   when decelerating.

 * When **accelerating on an easterly or westerly heading, the
   error appears as a turn toward north.**
 * When **decelerating on an easterly or westerly heading, the
   error appears as a turn toward south.**

ANDS: Accelerate indicates North, Decelerating indicates South.

# Oscillation Error

 * A combination of all the above errors, resulting in a fluctuation
   of the compass card.
