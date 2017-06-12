---
layout: post
title:  "GS40: Flight Instruments (3)"
date:   2017-06-11 17:15:00
categories: cpl-multi-training
---

# Gyroscopic Instruments

**Gyroscopic Princples**

Any spinning object exhibits gyroscopic properties. A wheel or rotor
designed and mounted to utilize these properties is called a gyroscope.

Two important design characteristics of a gyroscope are:

 1. High density (high weight for its size).
 2. Rotation at high speed with low friction bearings.

There are two general types of mountings, depending on which property
of the gyro is used.

 1. Freely mounted (or universally mounted): free to rotate in any
    direction about its CG.
     * Said to have three planes of freedom.
     * Balanced so that with the gyro at rest, it remains in the
       position it was placed (ie. no part of the mount tends to
       move it toward a particular orientation).
     * Used for **rigidity in space**.
 2. Restricted (or semi-rigidly mounted): one of the planes of
    freedom is held fixed in relation to the base.

There are two fundamental properties of gyroscopic action: rigidity
in space, and precession.

**Rigidity in Space**

 * A gyroscope remains in a fixed position in the plane in which it's
   spinning.
 * An example is a bicycle wheel - as it increases speed it becomes
   more stable and less maneuverable, but unstable and maneuverable
   at low speeds.
 * **By mountin the gyro on a set of gimbal rings**, the gyro is able
   to rotate freely in any direction.
    * Therefore, if the gimbal rings are moved in any direction, **the
      gyro is free to remain in the plane in which it was originally
      spinning.**

**Precession**

 * Precession is the **tilting or turning of a gyro in response to a
   deflective force.**

**The reaction to a force applied to a gyro occurs at a point 90
degrees later in the direction of rotation.**

 * This principle allows the gyro to determine a rate of turn by
   sensing the amount of presure created by a change in direction.
 * The rate at which a gyro precesses is *inversely proportional
   to the speed of the rotor, and directional proportional to the
   amount of deflective force.*

*Using the example of a bicycle, precession acts on the wheels in
order to allow the bike to turn. While riding at normal speed it's
not necessary to turn the handle bars to go around a corner.

By leaning in the direction, since the wheels are rotating clockwise
as viewed from the right, although the force applied is to the top
of the wheel (tilting the wheel sideways, top toward the ground),
the force is felt 90 degrees after the position, ie. at the front
of the wheel.*

Precession can cause a freely spinning gyro to **become displaced
from its intended plane of rotation** through bearing friction,
worn vacuum pump, etc. and require realignment during flight (eg.
heading indicator.).

**Sources of Power**

 * Most aircraft have at least two sources of power to ensure at
   least once source of bank information is available in the case
   one power system fails.
 * The **vacuum or pressure system** spins the gyro by drawing a
   stream of air against the rotor vanes to spin the rotor at
   high speed.
    * The amount of vacuum required varies, but typically between
      4.5 "Hg and 5.5 "Hg.
    * Vacuum is measured in inches of mercury **less than ambient
      pressure).**
 * One source of vcauum for the gyros is an engine-driven vacuum
   pump, which along with a relief valve, air filter, gauge, and
   tubing, make up the vacuum system.
 * It's important to monitor vacuum pressure during flight, the
   vacuum instruments may indicate incorrectly if vacuum pressure
   is low.

# Turn Indicators

Aircraft use two types of turn indicators: **turn-and-slip** and
**turn coordinators**.

Because of the way the gyro is mounted, **turn-and-slip shows
only the rate of turn in degrees per second**.

The **turn coordinator** is mounted at an angle ('canted') **so
it can initially show roll rate - when the turn stabilizes it
indicates rate of turn.**

Both instruments indicate turn direction and quality
(coordination) of turn. Coordination is shown on the inclinometer,
consisting of a liquid-filled curved tube with a ball inside.

**Turn and Slip Indicator**

 * Gyro rotates in the vertical plane, corresponding to the
   aircraft's longitudinal axis.
 * Because of **precession**, a yawing force causes the gyro to
   tilt left or right as viewed from the pilot seat (yaw would
   apply to the front/back of the rotor, meaning precession acts
   on the top/bottom of the rotor and tilts it left or right).
 * The turn-and-slip indicator uses a turn needle to show the
   direction and rate of turn.
 * It's incapable of 'tubling' off its rotational axis because
   of restraining springs.

When extreme forces are applied to a gyro, the gyro is displaced
from its normal plane of rotation, rendering its indications
invalid. Certain instruments have specific pitch and bank
limits which induce a tumble of the gyro.

**Turn Coordinator**

 * Gimbal in a TC is *canted*, its gyro can sense **both rate
   of roll and rate of turn.**
    * When rolling into or out of a turn, the miniature
      aircraft banks in the direction of the roll. A rapid
      roll rate causes the bank to be steeper than a slow
      rate.
 * A **standard rate turn** can be established by aligning
   the wing of the miniature aircraft with the turn index. A
   standard rate of turn is 3 deg/second, 180 deg/minute, or
   360 deg/2 minutes ("two minute turn").

**The turn coordinator displays only the rate and direction
of turn, not the angle of bank.**

**Inclinometer**

 * Depicts aircraft yaw (sideways movement of aircraft nose).
 * Consists of a curved liquid-filled tube with a ball in it,
   and two lines a ball-width apart.
 * If ailerons and rudder are coordinated, the ball remains at
   the bottom of the tube, between the lines.
 * Otherwise, 'step-on-the-ball' -- apply the rudder on the
   side the ball has rolled to in order to re-centre the ball.
 * In a **slip** the ball moves to the **inside** of the turn.
 * In a **skid** the ball moves to the **outside** of the turn.

**Attitude Indicator**

 * Gyro is mounted in a **horizontal plane**, and depends upon
   **rigidity in space** for its operation.
 * The gyro resists deflection, while the aircraft rotates
   around the gyro.
 * Pitch and bank limits depend on make and model. Bank limits
   are usually from 100-110 degrees, pitch limits usually
   60-70 degrees. If either are exceeded the instrument will
   tumble and indicate incorrectly until realigned.
    * A number of modern AIs don't tumble.

**Heading Indicator**

 * Designed to facilitate use of the mag compass, which has a
   number of inherent errors, which the HI isn't affected by.
 * Depends on **rigidity in space**.
 * The rotor turns in a **vertical plane**. Since the rotor
   remains rigid in space, the points on the compass card
   it's connected to hold the same position in space relative
   to the vertical plane of the gyro.
    * **The aircraft rotates around the spinning gyro (not
      the other way around).**
 * Because of precession caused by friction, the HI drifts
   from its set position, with the extent determined by the
   condition of the instrument.
 * **Another reason for gyroscopic precession** is that the
   gyro is oriented in space, and remains fixed while it's
   operating (discounting the precession just mentioned),
   while the Earth rotates in space at a rate of 15 deg/hour.
    * Therefore, the heading indicator may indicate as
      much as 15 degrees error per hour of operation.
 * Some heading indicators are referred to as **Horizontal
   Situtation Indicators (HSIs)** and receieve a magnetic
   north reference from a 'magnetic slaving transmitter'.
   They generally need no adjustment.
    * The magnetic slaving transmitter is called a
      **magnometer**.
