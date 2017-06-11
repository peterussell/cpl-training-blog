---
layout: post
title:  "GS39: Flight Instruments (2)"
date:   2017-06-11 16:01:00
categories: cpl-multi-training
---

# VSI (Vertical Speed Indicator)

 * A differential pressure instrument, connected only to the pitot tube.
 * The *inside* of the diaphragm is connected directly to the static port.
    * Area *outside* the diaphragm connected to the static port via a
      restricted orifice (calibrated leak).
 * When on the ground or level flight, pressures inside and outside are
   equal. When in climbs or descents, pressure inside the diaphragm
   changes immediately, but pressure outside changes slowly. This
   differential in pressures is displayed on the gauge and indicates
   the rate of climb or descent.
 * VSI shows two pieces of information:
    1. Trend information, an **immediate indication of an increase or
       decrease in the rate of climb or descent.**
    2. Rate information, when established at a stabilized rate of change
       in altitude.

**Lag**

Lag is the time between when the VSI needle starts moving up or down
(the 'trend') and when it stabilizes (indicating the 'rate').

**IVSI (Instantaneous VSI)**

Some aircraft have IVSIs, which incorporate accelerometers to compensate
for the lag in a normal VSI.

# Airpspeed Indicator (ASI)

 * A differential pressure instrument, giving the difference between
   ram air from the pitot tube, and ambient air pressure from the static
   port.
 * Static pressure is in the instrument housing, and ram air pressure is
   inside the diaphragm. As airspeed increases the diaphragm expands,
   which is converted to an indication on the ASI showing an increase
   in speed. The opposite happens with a decrease in speed.

**Types of Airspeeds**

 * **Indicated (IAS):** reading from the ASI, uncorrected for atmospheric
   density, installation error, or instrument error. Used for aircraft
   performance (landing/takeoff/stall speeds are IAS).
 * **Calibrated Airspeed (CAS):** IAS corrected for **installation and
   instrument error.** Manfuacturers try to eliminate errors, but at
   certain airspeeds and flap settings, errors may be several knots.
   Error is usually greatest at lower airspeeds. **Refer to airspeed
   calibration chart (usually in AFM/POH) for corrections.**
 * **True Airspeed (TAS):** CAS corrected for **altitude and
   non-standard temperature.**
    * Because air is less dense at higher altitudes/temps, the aircraft
      has to be flown **faster at higher altitudes/temps to cause the
      same pressure difference** between impact and static pressure.
    * Therefore, for a given CAS, TAS increases as altitude increases,
      or for a given TAS, CAS decreases as altitude increases.
    * Two methods to calculate TAS:
       * Flight computer (E6B or digital onboard, etc.)
       * Rule of thumb (approximate): **add 2% to CAS for each 1,000'**
    * **TAS is used for flight planning.**
 * **Groundspeed (GS):** actual speed of the airplane over the ground.

**ASI Markings**

Aircraft <= 12,500' lbs, manufactured after 1945, and certificated by
the FAA, are required to have ASIs marked in accordance with a standard
color-coded marking system.

 * White arc: flap operating range.
    * Lower limit (V<sub>S0</sub>): stalling speed or minimum steady
      flight speed in the landing configuration (in small
      aircraft, gear and flaps down).
    * Upper limit (V<sub>FE</sub>): max speed with flaps extended.
 * Green arc: normal operating range.
    * Lower limit (V<sub>S1</sub>): stalling speed or min steady flight
      speed in the specified configuration (gear up if retractable,
      flaps up).
    * Upper limit (V<sub>NO</sub>): max structural cruising speed. Do
      not exceed except in smooth air.
 * Yellow arc: caution range, only in smooth air.
 * Red line: (V<sub>NE</sub>): never exceed speed. Operating above this
   is prohibited, may result in damage or structural failure.

**Other Airspeed Limitations**

Not marked on the ASI, but found in the POH/AFM:

 * Design Maneuvering Speed (V<sub>A</sub>): maximum speed at which
   the structural design's limit load can be imposed (either by gusts
   or full deflection of the control surfaces) without causing
   structural damage.
    * Important to consider that it **changes with weight**.
 * Landing Gear Operating Speed (V<sub>LO</sub>): maximum gear
   at which the gear can be lowered or raised.
 * Landing Gear Extended Speed (V<sub>LE</sub>): max speed with the
   gear extended.
 * Best angle-of-climb (V<sub>X</sub>): most altitude gain over a
   given horizontal distance.
 * Best rate-of-climb (V<sub>Y</sub>): most altitude gain over a
   period of time.
 * Single engine best rate-of-climb (V<sub>YSE</sub>): best rate-of-
   climb, or minimum sink speed in a light twin-engine airplane with
   one engine inoperative. **Marked on the ASI as a blue line.**
 * Minimum Control Speed (V<sub>MC</sub>): minimum speed at which
   a light twin-engine airplane can maintain directional control with
   one engine inoperative and the other at takeoff power.

# Blockage of the Pitot-Static System

Errors almost always indicate blockage of the pitot tube, static port(s),
or both. Pitot blockages only affect the ASI, static port blocakge
affects ASI, VSI, and altimeter.

Blockages can be caused by moisture (ice), dirt, or insects.

**Blocked Pitot System**

Pitot tubes have a ram air hole, and a drain hole or holes. If only the
front inlet is blocked, it's a partial blockage. If both are blocked
it's a complete blocakge.

 * Partial:
    * Ram air can no longer enter.
    * Air in the system vents through the drain hole.
    * Remaining pressure drops to ambient air pressure.
    * **ASI drops to 0, there's no pressure difference between static
      port air and ambient air from the drain hole.**
    * Usually happens very quickly.
 * Full:
    * Pressure in the pitot tube is trapped.
    * No change is noted even with an airspeed increase or decrease.
    * If the *static port* is unblocked, then the ASI changes with a
      change in altitude (pressure outside the diaphragm still changes
      with altitude - **the ASI acts as an altimeter.**

**Blocked Static System**

 * If the static system is blocked by the pitot system isn't, then the
   ASI continues to operate but is inaccurate (not corrected for
   ambient pressure).
    * If the static port becomes blocked, then the airplane climbs:
       * Ambient pressure stays the same, but it *should* have decreased.
       * Indicates slower than actual.
    * If the static port blocks, then the airplane descends:
       * Ambient pressure stays the same, but should have increased.
       * Indicates faster than actual.
 * **Alimeter and VSI:**
    * Altimeter will freeze at the altitude the blockage occurred at.
    * VSI will indicate 0 FPM regardless of climbs or descents.

**Alternate Static Source**

Some airplanes are equipped with an alternate static source on the
flight deck, which can be opened if the static port becomes blocked.
**Flight deck static pressure is *lower* than outside static pressure**
 - think of warmer air inside the cockpit (may or may not be the
actual cause). Check the AFM/POH for calibration.

# Electronic Flight Display (EFD)

*NB: There's a section here, but I'll omit it due to training in a
completely analog cockpit. I should revisit it in the future if these
plans change.*
