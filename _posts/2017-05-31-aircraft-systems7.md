---
layout: post
title:  "GS34: Aircraft Systems (7)
date:   2017-05-31 22:22:00
categories: cpl-multi-training
---

# Oil Systems (continued)

 * The oil **pressure** gauge(s) provide an indication of pressure in pounds
   per square inch (PSI) of oil supplied to the engine. Green indicates
   normal operating range, red indicates min and max operating pressures.
 * The oil **temperature** guage(s) measure oil temperature. Unlike
   pressure, temp changes can occur more slowly, eg. after starting a
   cold engine.
    * Check oil temp periodically, especially operating in high or low
      ambient air temperatures.
    * **High** indications may signal a plugged oil line, low oil, blocked
      oil cooler, or defective gauage.
    * **Low** temperature may indicate improper oil viscosity in cold
      weather operations.

# Engine Cooling Systems

 * Combustion causes high temperatures in the engine. Much is carried
   away by exhaust gases, but the rest must be removed to prevent engine
   overheating.
 * High engine temps can lead to **loss of power, excessive oil consumption,
   detonation, and serious engine damage.**
 * **Oil** plays an important role in cooling, but other methods are
   required to provide additional cooling to the engine's surface.
 * Most small aircraft are air cooled, some are liquid cooled.

**Air Cooling**

 * Achieved by air flow through the front of the cowling, then routed by
   baffles over cooling fins attached to the cylinders, and other engine
   parts.
 * Expulsion takes place through openeings in the lower aft part
   of the cowling.
 * Less effective during ground ops, takeoff, climbs, go-arounds, and other
   high-power and low-airspeed operations.
 * Conversely, high speed descents can shock-cool the engine.
 * Operating the engine at too high a temperature can lead to:
    * Power loss.
    * Excessive oil consumption.
    * Detonation.
    * Engine damage: scorched cylinders, piston/ring damage, warping valves.
 * In normal operations, reduce engine temperature by:
    * Reducing power.
    * Increasing airspeed.
    * Enriching mixture.
    * Opening cowl flaps (if equipped).

**Note on Oil Temperature Gauges vs. CHT Gauages**

Oil temp gauges give an indirect and delayed indication of rising engine
temperature. Most aircraft also have a Cylinder Head Temperature (CHT)
gauge that indicates a direct and immediate cylinder temp change.

# Exhaust Systems

 * Vent combustion gases overboard, provide cabin heat, defrost windscreen.
 * Made up of exhaust piping attached to cylinders, muffler, muffler shroud.

**Heating**

Outside air is drawn into a shroud around the **muffler** (so it's quieter
in the cabin?). Exhaust gases heat the muffler, which in turn heats the
air which is then directed to the cabin.

Exhaust gases contain carbon monoxide, need to be wary of it entering the
cabin if there's a crack in the muffler.

**EGT**

 * Some exhaust systems have an EGT (Exhaust Gas Temperature) probe, which
   measures **temp of gases at the exhaust manifold**.
 * Temperature varies with the fuel-air ratio entering cylinders, and can
   be used to set the mixture very accurately. Refer to manufacturer
   procedure for leaning using EGT.

# Starting System

 * Most small aircraft use a **direct-cranking electric starter**.
 * Consists of an electrical source, wiring, switches, and solenoids to
   operate the starter and starter motor.
 * Most starters automatically engage and disengage. On older aircraft
   this may be done manually with a pilot-activated lever.
 * **The starter engages the flywheel, rotating the engine at a speed
   that allows the engine to start and maintain operation.**
 * Power is usually supplied by an onboard battery, but can also be
   external.
    * When the battery switch is turned on, electricity is supplied to
      the main bus, which the starter is attached to.
    * However, the **starter won't operate until the starting solenoid
      is energized by the starter switch being turned to 'Start'.**
      When the switch is released from 'Start', the solenoid removes
      power from the starter motor.
 * **The starter motor is prevented from being driven by the engine
   through a clutch in the starter drive that allows the engine to
   run faster than the starter motor.**

# Combustion

 * In normal operation, the fuel-air mixture is ignited at the spark plug
   and burns in a controlled fashion, delivering maximum power to the
   piston at precisely the right time in the power stroke.

**Detonation**

 * **Detonation is an uncontrolled, explosive ignition of the mixture
   within the cylinder.**
    * It causes excessive temperatures and pressures, if not corrected
      can lead to failure of piston, cylinder, or valves.
    * In less severe cases can cause engine roughness, overheating, or
      loss of power.
    * Detonation is characterized by high CHT indications, and most likely
      to occur at high power settings.

**Common Causes of Detonation**

 * Use of a lower fuel grade than specified.
 * Operation at high MAP and low RPM.
 * Operation at high power settings with excessively lean mixture.
 * Extended ground operations or steep climbs.

**Preignition**

 * Occurs when fuel-air mixture ignites *prior* to the engine's normal
   ignition event.
 * Usually caused by a residual hot spot in the combustion chamber,
   often caused by:
    * Small carbon deposit on a spark plug.
    * Cracked spark plug insulator.
    * Other damage to the cylinder that causes part of it to heat
      sufficiently to ignite the fuel-air charge.
 * **Preignition causes:**
    * Loss of engine power
    * High operating temperature.
    * Possible severe engine damage - exerts excessive pressure on the
      piston while still on the compression stroke.

Detonation and preignition often occur simultaneously and one may cause
the other. Either causes high engine temp and a decrease in RPM, and
may be difficult to distinguish. Use recommended grade fuel, and
operate engine within limitations while monitoring temp, pressure, and
RPM.

# FADEC (Full Authority Digital Engine Control)

 * A digital computer and components which control an aircraft's
   engine and propellor.
 * In a spark-ignition reciprocating engine, FADEC uses speed,
   temperature, and pressure sensors to monitor the status of
   each cylinder.
    * A computer calculates the ideal pulse for each injector and
      adjusts ignition timing as necessary for optimal performance.
 * In a comrpession-ignition engine, FADEC operates all the same
   functions except for those related to the spark ignition process.
 * FADEC eliminates the need for:
    * Magnetos.
    * Carb heat.
    * Mixture controls.
    * Engine priming.
 * A single throttle lever is characteristic of a FADEC aircraft.
    * The pilot positions the throttle lever to a desired detent,
      such as start, idle, cruise or max power, and the FADEC
      system adjusts the engine and propellor for the desired mode.
 * **During starting**, FADEC primes the cylinders, adjusts the
   mixture, and positions the throttle based on engine temperature
   and ambient pressure.
 * **During cruise, FADEC monitors the engine and constantly adjusts
   fuel flow and ignition timing individually in each cylinder.
    * This often results in decreased fuel consumption and increased
      horsepower.
 * FADEC is considered an **essential system**, and in many aircraft
   uses power from a separate generator connected to the engine.
    * In either case, **there must be a backup electrical source,
      and two separate and identical digital channels, each capable of
      providing all engine and propellor functions.
