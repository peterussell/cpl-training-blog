---
layout: post
title:  "GS29: Aircraft Systems (2)
date:   2017-05-29 14:13:00
categories: cpl-multi-training
---

# Fixed-Pitch Propellor

 * "Fixed-pitch" means a propellor with fixed blade angles, it's set
   by the manufacturer and can't be changed.
 * Achieves best efficiency only at a given combination of airspeed and
   RPM, therefore ideal for neither cruise or climb.
 * Used when low weight, simplicity, and low cost are required.
 * Can either be directly mounted in the crankshaft, in which case prop
   RPM = engine RPM, *or* mounted on a shaft geared to the crankshaft, in
   which case the two RPMs are different.
 * With a fixed-pitch prop, the **tachometer** is indicator of engine power,
   measured in 100s of RPMs:
    * **Green arc:** maximum continuous operating RPM.
    * **Red line:** don't exceed RPM
    * May also have other markings, refer to operating manual.
 * RPM is regulated by the throttle which controls fuel and air flow to the
   engine.
 * **When operating altitude increases, the tach may not show correct power
   output of the engine.** eg. 2,300 RPM at 5,000' produces *less* power than
   2,300 RPM at sea leve, because **power output depends on air density.**
    * *As altitude changes, throttle position must be changed to maintain a
      continuous RPM.*

**Types of Fixed-Pitch Propellors**

 * **Climb**
   * *Lower pitch*, therefore less drag.
   * Higher RPM and more horsepower capability.
   * Increased performance during takeoffs and climbs, but decreased
     performance during cruise flight.
 * **Cruise**
   * *Higher pitch*, therefore more drag.
   * Lower RPM and less horsepower capability.
   * Decreased performance during takeoff and climb, but better efficiency
     during climbs.

# Adjustable-Pitch Propellor

 * Forerunner to the constant-speed propellor, it's a propellor with **blades
   whose pitch can be adjust on the ground with the engine not running, but
   cannot be adjusted in flight.**
    * Also referred to as a ground-adjustable propellor.
 * Early models only allowed two pitches, today most are capable of a range of
   pitches.
 * Sometimes used interchangeably to describe a constant-speed propellor.

# Constant-Speed Propellor

 * Aircraft with constant-speed props have two controls:
    * **Throttle:** controls power output from the engine, usually shown on the
      Manifold Absolute Pressure (MAP) gauge.
    * **Propellor Control:** regulates engine RPM, which regulates propellor RPM,
      shown on the tachometer.
 * Once an RPM is selected, a **governor** automatically adjusts the propellor
   blade angle as necessary to maintain that RPM.
    * *eg. after setting desired RPM during cruise, an increase in airspeed or
      decrease in propellor load (eg. less dense air) causes the pitch to
      increase in order to slow the propellor and maintain constant RPM.*

**Constant-Speed Range**

 * Constant-speed props have a range of possible blade angles for the propellor,
   limited by high and low pitch stops.
 * As long as the blade angle is within the range and not against either pitch
   stop, it will automatically be adjusted to maintain a constant RPM.
 * If the blades contact a pitch stop, the engine RPM will increase or decrease
   as appropriate with changes in airspeed and propellor load.
 * In these cases the propellor performs like a fixed-pitch propellor.

**Manifold (Absolute) Pressure Gauge**

 * On constant-speed aircraft, power output is controlled by the throttle and
   indicated by the manifold pressure gauge. This gauge measures the **absolute
   pressure of the fuel-air muxtre *inside the intake manifold*.**
 * At a constant RPM and altitude, the amount of power produced is directly
   related to the fuel-air mixture being delivered to the combustion chamber.
 * *When the engine is not running, MAP indicates ambient air pressure
   (eg. 29.92 "Hg)*
 * When the engine is started, the manifold pressure indication *decreases* to
   a value less than ambient pressure (eg. idle at 12 "Hg).
 * **Engine failure or power loss is indicated on the manifold pressure gauge
   as a decrease in pressure to match the ambient air pressure.**

**Manifold Pressure vs. RPM Considerations**

For any given RPM there's a corresponding manifold pressure that shouldn't
be exceeded, otherwise pressure in the cylinders could be exceeded and place
undue stress on the cylinders. Repeating this could weaken cylinders and
cause premature failure.

Consult manufacturer's recommendations for power settings. In general, follow
these rules:

 * When **decreasing power settings**, decrease the manifold pressure before
   RPM.
 * When **increasing power settings**, increase the propellor RPM before
   increasing manifold pressure.
 * To prevent damage to **radial engines**, minimize operating time at maximum
   RPM and manifold pressure, and avoid operation at *max RPM and low manifold
   pressure*.

# Propellor Overspeed in Piston Engine Aircraft

On March 17 2010, the FAA issued Special Airworthiness Information Bulletin
(SAIB) CE-10-21. It explains a scenario where a single-engine aircraft had a
propellor overspeed at 7,000'. The pilot reported that applying throttle
resulted in overspeed with no appreciable thrust. The pilot established best
glide of 100kts and glided to a nearby airport, but landed short of the airport.

The propellor experienced a failure causing teh blade pitch change to move to
the low pitch stop position (normal failure mode). This caused the propellor
to operate as a fixed-pitch propellor, ie. changes with power and airspeed. Low
pitch gives maximum power at takeoff but can result in overspeed at altitude.

The resulting evaluation determined that an airspeed *lower than best glide*
resulted enough thrust to maintain level flight.

Operators of aircraft with variable pitch propellors should be aware that in
certain instances of propellor overspeed, **the airspeed necessary to maintain
level flight may be below best glide.** This may reduce the ability to get to
an airport for a safe landing, so determining the best airspeed should be done
at altitude.
