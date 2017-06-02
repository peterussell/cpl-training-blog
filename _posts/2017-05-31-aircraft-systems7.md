---
layout: post
title:  "GS34: Aircraft Systems (7)"
date:   2017-06-01 21:42:00
categories: cpl-multi-training
---

# Turbine Engines

 * Turbine engines produce thrust by accelerating the air flowing through
   the engine.
 * Consist of an **air inlet, compressor, combustion chamber, turbine section,**
   and **exhaust**.
 * Characterized by smooth operation, and a **high power-to-weight ratio**.

**Very Light Jets (VLJs)**

VLJs are turbine powered aircraft which typically seat 3-7 passengers. Smaller
versions may be called microjets.

# Types of Turbine Engines

Turbine engines are classified according to the type of compressor used:

 1. Centrifugal flow.
     * Compression of air achieved by accelerating air outward, perpendicular
       to the longitudinal axis of the machine.
 2. Axial flow.
     * Compresses air by a series of rotating and stationary airfoils moving
       air parallel to the longitudinal axis.
 3. Centrifugal-axial flow.
     * Uses both of the above compression methods.

The *path* the air takes through the engine and *how power is produced*
determines the type of engine. There are four types: turbojet, turboprop,
turbofan, and turboshaft.

[Excellent StackExchange article.][se]

# Turbojet

 * Consists of four sections: **compressor, combustion chamber, turbine
   section, exhaust.**
    * The compression section passes air at high speed to the combustion
      chamber.
    * Combustion chamber contains fuel inlet valve and igniter for combustion.
    * Expanding air drives a turbine, connected by a shaft to the compressor,
      which is what sustains engine operation.
    * Accelerated gases from the engine provide thrust.
 * Turbojet engines are limited in *range and endurance*, but typically allow
   higher speeds (eg. sustained supersonic).
 * Also slow to respond to throttle applications at slow compressor speeds.

# Turboprop

 * Turbine engine that drives a propellor through a reduction gear.
 * Exhaust gases drive a power turbine connected by a shaft that drives the
   reduction gear, necessary because the prop turns much slower than the
   engine's RPM.
 * Turboprops are a compromise between turbojet engines and reciprocating
   engines (eg. piston engines).
 * **Most efficient between 250-400 mph, altitudes 18,000-30,000'.**
 * They also perform well at slow airspeeds (takeoff/landing), and are fuel
   efficient.

# Turbofan

 * Developed to combine best features of the turbojet and turobprop.
 * Inlet air is divided into two streams of air, one goes through the
   turbine core, and other flows around it but inside the cowling (bypass
   air).
 * The bypass air creates additional thrust, cools the engine, and provides
   exhaust noise suppression.
 * Provides turbojet-type cruise speed and lower fuel consumption.
 * The **bypass ratio** refers to how much air is diverted around the core:
    * Low bypass means most goes to the core (older engines?)
    * High bypass (eg. 787), as much as 4/5s of air goes *around* the core.

# Turboshaft

 * Delivers power to a shaft that drives something *other* than a propellor.
 * The main difference is that most of the energy turns the shaft, rather
   than providing thrust out the back of the engine.
 * Many helicopters use turboshaft gas turbine engines.
 * Also used as aux power units on large aircraft.

# Turbine Engine Instruments

 * Still have oil pressure/temp, engine speed, EGT, fuel flow.
 * Additionally have engine pressure ratio (EPR), turbine discharge pressure,
   and torque.
 * Also have **turbocouples**, temperature sensors in and around the turbine
   section.

**Engine Pressure Ratio (EPR)**

 * Indicates the power output of a turbojet/turbofan engine.
 * It's the **ratio of turbine discharge to compressor inlet pressure**,
   recorded by probes at the inlet and exhaust.
 * EPR system design automatically compensates for effects of airspeed and
   altitude.
 * Changes in ambient temperature require a correction to be applied to
   EPR indications.

**Exhaust Gas Temperature (EGT)**

 * Temperature in the turbine section is a limiting factor of gas turbine
   engines, and must be monitored closely to prevent overheating turbine
   blades and other exhaust section components.
 * An EGT gauge is a common way to monitor the temperature of the turbine
   section.
 * EGT systems have different names based on the location of the sensors:
    * Turbine Inlet Temperature (TIT).
    * Turbine Outlet Temperature (TOT).
    * Interstage turbine temperature (ITT).
    * Turbine Gas Temperature (TGT).

**Torquemeter**

 * Measures engine power output, as the twisting force applied to the
   shaft.
 * Turboprop and turboshaft engines are designed to produce torque for
   driving a shaft.
 * Torquemeters are calibrated in %, foot-pounts, or PSI.

**N<sub>1</sub> Indicator**

 * Rotational speed for the **low pressure compressor**.
 * Indicated as a percentage of design RPM.
 * After start, the speed of the low pressure compressor is governed
   by the N<sub>1</sub> turbine wheel.
    * The N<sub>1</sub> turbine wheel is connected to the low pressure
      compressor through a concentric shaft.

**N<sub>2</sub> Indicator**

 * Rotational speed of the **high pressure compressor**.
 * Same as for N<sub>1</sub>, except the N<sub>2</sub> turbine wheel is
   connected to the high pressure compressor.

# Turbine Engine Operational Considerations

It's impossible to cover here all limitations that apply to all different
types of turbine engines, but the follow apply to all:
 * Engine Temperature Limits.
 * Foreign Object Damage.
 * Hot Start.
 * Compressor Stall.
 * Flameout.

**Engine Temperature Limitations**

The highest temperature in any turbine engine **occurs at the turbine inlet.**
TIT is therefore usually the limiting factor in turbine engine operation.

**Thrust Variations**

 * Turbine engine thrust varies directly with air density, less density=less
   thrust.
 * Because *air density decreases with increase in temperature*, increased
   temps also decrease thrust.
 * However, compared to reciprocating engines, turbine engines experience
   a *negligible loss of thrust in relative high humidity.*

**Foreign Object Damage (FOD)**

 * The possibility of ingestion of debris always exists, which causes significant
   damage, particularly to the compressor and turbine sections.
 * When this occurs, it's called Foreign Object Damage (FOD).
 * Typical FOD is nicks caused by debris from the ground, but bird strikes or
   ice ingestion can result in severe or total damage.
 * Prevention of FOD is a high priority.
    * Some engine inlets have a tendency to form a **vortex between the ground
      and inlet during ground operations**.
    * A **vortex dissipator** may be installed on these engines.
    * Other devices like screens and/or deflectors may be used.
    * Preflight includes inspecting for any sign of FOD.

**Hot/Hung Start**

 * When EGT exceeds the safe limit, it is a 'hot start'.
 * Caused by **too much fuel** in the combustion chamber, or **insufficient RPM**.
 * Any time a hot start occurs, refer to the AFM/POH for inspection requirements.
 * A **hung start** is when the engine fails to accelerate to the proper speed
   after ignition, or doesn't accelerate to idle RPM.
    * Hung starts may be caused by an insufficient starting power source, or
      fuel control malfunction.

**Compressor Stalls**

 * Compressor blades are airfoils, which have an AOA dependent on **inlet air
   velocity** and **rotational velocity**, which combine to form a vector
   that determines the blade's AOA.
 * A **compressor stall** is an imbalance between the two quantities (inlet
   air velocity and rotational velocity).
 * **They occur when the compressor blades' AOA exceeds the critical AOA.**
 * Compressor stalls cause air flowing in the compressor to slow down and
   stagnate, and sometimes reverse direction.
 * They can be small and intermittent, or steady and severe.
 * Indications are usually a backfire as flow reversal takes place.
 * If the stall develops, a **steady, strong vibration and loud roar may
   develop** from the flow reversal.
 * Gauges often don't show an intermittent stall, but do show a developed
   stall as **RPM fluctuations, increase in EGT.**
 * Intermitten stalls aren't harmful and often correct themselves. Developed
   stalls are immediately damaging.
    * **Recovery must be accomplished by quickly reducing power, decreasing
      the aircraft's AOA, and increasing airspeed.**
 * Most models of gas turbine engines have systems that inhibit compressor
   stalls.
    * One system uses a 'variable inlet guide vane' (VIGV) and variable
      stator vanes that direct incoming air into the rotor blades at an
      appropriate angle.

**Flameout**

 * Occurs when the fire in the engine unintentionally goes out.
 * If the rich limit of the fuel-air ratio is exceeded in the combustion chamber,
   the flame will blow out, often referred to as a 'rich flameout'.
 * Common cause is low fuel pressure and low engine speeds, typically associated
   with high-altitude flight. May also occur with engine throttled back during
   a descent.
 * Can be caused by rapid acceleration, injecting too much fuel in the engine.
 * Can also be caused by insufficient airflow to support combustion.
 * Other causes are prolonged unusual attitudes, malfunctioning fuel control
   system, turbulence, icing, or running out of fuel.
 * If the cause of the flameout can be resolved, then an in-air restart can be
   attempted. In any case refer to the AFM/POH emergency procedures.

 [se]: https://aviation.stackexchange.com/questions/4966/what-is-the-difference-between-a-turbofan-and-a-turboprop-engine
