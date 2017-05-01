---
layout: post
title:  "GS24: Aerodynamics of Flight (17)"
date:   2017-04-30 16:51:00
categories: cpl-multi-training
---

# Rate of Turn

*NB. all airspeed used in this discussion is TAS*

 * The ROT is the number of degrees (in degrees/second) of heading change that
   an aircraft makes.
 * The ROT can be determined by taking the constant 1,091, multiplying it by
   the tangent of the bank angle, and dividing it by the airspeed in knots.
 * This relationship shows that if the airspeed is increased, the bank angle
   must also be increased otherwise the ROT will decrease.
 * Likewise, the ROT is increased if the bank angle is increased for a constant
   airspeed.

The practical application is that we can determine how long it takes to make
a heading change of a certain number of degrees. For example, if moving a 120kts
with 30 degree bank, the ROT is 5.25 degrees/second, and it takes 68.6 seconds
(360/5.25 = 68.6) to make a complete circle.

> ROT = 1091 x tan(bank angle) / airspeed in knots

Likewise, if flying at 240kts TAX and a 30 degree bank, the ROT is only about
2.63 degrees/second and it takes about 137 seconds to complete a 360 degree
turn. The main concept is that any increase in airspeed is directly proportional
to the time it takes an aircraft to travel an arc.

This is important because it allows us to determine the **distance required
to make a particular turn**.

# Radius of Turn

The radius of turn is directly related to the rate of turn, which is a
function of bank angle and airspeed.

The radius of turn (R) can be computed by the velocity squared, divided by
11.26 times the tangent of the bank angle:

> R = V<sup>2</sup> / 11.26 x tan(bank angle)

**Note that if the airspeed is doubled, the radius is quadrupled.**

The radius of the turn can also be calculated by converting the TAS to fps,
pi (3.1415) and the ROT.

*Example: for a ROT of 5.25 degrees/second, we determined in a previous
example that it would take 68.6 seconds to make a complete circle. **An
aircraft's speed in knots can be converted to fps by multiplying by a
constant of 1.69***.

*Therefore, an aircraft traveling at 120kts (TAS) travels at 202.8 fps.
202.8 fps multiplied by the time required to complete the circle (68.6
seconds) gives 13,912 feet - or the circumference. To get the radius
we divide by pi = 4,428', and then by 2, giving a radius of 2,214'.*

# Weight and Balance

Aircraft are certified for weight and balance for two reasons:

 1. The effect of weight on the aircraft's primary structure and its
    performance characteristics.
 2. The effect of the *location* of this weight on flight characteristics,
    particularly in stall and spin recovery and stability.

**Effect of Weight on Flight Performance**

The takeoff/climb and landing performance are determined on its maximum allowable
takeoff and landing weights. A heavier gross weight results in a longer takeoff
run, shallower climb, and faster touchdown speed, and longer landing roll.

The detrimental effects also apply to climb and cruise: overheating during
climbs, added wear on engine parts, increased fuel consumption, slower cruising
speeds, and reduced range.

**Effect of Weight on Aircraft Structure**

Airworthiness requirements prescribe that the structure of an aircraft
certificated in the normal category (no acrobatics) must be strong enough
to withstand a load factor of +3.8 Gs, to be able to handle loads imposed
by maneuvering and gusts. **This means the primary structure can handle a
load of 3.8 times the approved gross weight of the aircraft without
structural failure occurring.** This means that if the aircraft were
overloaded by 100lbs, and was operated up to (but within) the limits of
its 3.8 G loading, that's an excess weight of 380lbs on the aircraft
structure.

Structural failures that result from overloading may be dramatic and
catastrophic, but more offten they affect structural components progressively
in a manner that's difficult to detect and expensive to repair. It
may not be easy or possible to detect during preflight, and result
in structural failure during normal operations.

It's also important to pay attention to placards or other restrictions
on weight in a particular compartment or area. For example, a placard
restricting a baggage area to 20lbs. Even though having more than 20lbs
in that baggage area may still be within weight and CG limits, the
supporting structure may not be designed to hold more than the 20lb limit.

**Effect of Weight on Stability and Control**

Overloading also affects stability. An aircraft that's stable and
controllable when loaded normally may have different flight characteristics
when overloaded.

Although *distribution* of weight has the most direct effect on this, an
increase in the aircraft's gross weight may be expected to have an
adverse effect on stability, regardless of location.

**Effect of Load Distribution**

The effect of the position of the CG on the load imposed on the wing is
significant to climb and cruise performance. **An aircraft with forward
loading is "heaver" and consequently, slower than the same aircraft
with the CG further aft.**

 * With forward loading, nose-up trim is required in most aircraft to
   maintain level flight.
 * Nose-up trim means the tail surface is providing a downward force
   on the aft portion of the fuselage.
 * This requires a higher AOA of the wing, which results in more drag,
   and in turn produces a higher stalling speed.

With aft loading and nose-down trim, the tail surfaces exert less down
load, relieving the wing of that much wing loading and lift required
to maintain altitude. The required AOA of the wing is less, so the drag
is less, allowing for a faster cruise speed.

Theoretically, a neutral load on the tail surfaces in cruising flight
would produce the most efficient overall performance and fastest cruise
speed, but it would also result in instability: **modern aircraft are
designed to require a load on the tail for stability and
controllability**. A zero indication on the trim tab is not necessarily
the same as 'neutral rim' because of the force exerted by the downwash
from the wings and fuselage on the tail surfaces.

**Flight Characteristics**

The effects of weight distribution have a significant influence on
flight characterstics, even within CG limits.

 * Generally, an aircraft becomes less controllable, especially at
   lower airspeeds, with a further aft CG. For example, an aircraft
   that recovers cleanly from a spin may become unrecoverable by
   moving the CG a few inches aft.
 * It's common practice for aircraft designers to establish an aft
   CG limit within one inch of the maximum, which allows for normal
   recovery from a one-turn spin.
    * When certificating in the utility category (to permit
      intentional spins), the aft CG limit is usually established
      several inches forward of that permissible certification for
      the normal category.

Another factor affecting controllability, mainly in larger aircraft,
is the effect of long moment arms to the position of heavy equipment
and cargo. The same aircraft may be loaded within CG limits by having
the load near the design CG, or by having fuel in wingtip tanks, and
having cargo forward and aft of the cabin.

Each of the above configurations has different handling characteristics:
the longer moment arms to the positions of heavy fuel and cargo must be
overcome by the control surfaces. **An aircraft with full outboard wing
tanks or tip tanks tends to be sluggish in roll when control situations
are marginal (eg. turbulent air), while one with full nose and aft
cargo bins tends to be less responsive to elevator controls.**

**Stalls, Spins, Flat Spins**

 * Recovery from a stall becomes proressively more difficult as CG moves
   aft.
 * This is particularly important in spin recovery -- there's a point in
   rearward loading of any aircraft at which a 'flat' spin develops.
    * A **flat spin** is one in which centrifugal force, acting through
      a CG located well to the rear, pulls the tail of the aircraft out
      away from the axis of the spin, making it impossible to get the
      nose down and recover.

**Forward CG Limits**

The forward CG limit is determined by a number of considerations. As
a safety measure, **it's required that the trim device, whether tab
or adjustable stablizer, be capable of holding the aircraft in a normal
glide with the power off**.

 * A conventional aircraft must be capable of a full stall, power-off
   landing in order to ensure minimum landing speed in emergencies.
 * A tailwheel aircraft loaded excessively nose-heavy is difficult to
   taxi, particularly in high winds. It can also easily be nosed over,
   and is difficult to land without bouncing since it tends to pitch
   down on the wheels as it's slowed and flared for landing.

**The effects of load distribution are summarized as follows:**

 * The CG position influences the lift and AOA of the wing, the amount
   and direction of force on the tail, and the degree of deflection on
   the stabilizer needed to supply the proper tail force for equilibrium.
   The latter is very important because of its relationship to
   elevator control force.
 * **The aircraft stalls at a higher speed with a forward CG.**
   This is because the stalling AOA is reached at a higher speed due to
   increased wing loading.
 * Higher elevator control forces normally exist with a forward CG
   due to the increased stabilizer deflection required to balance the
   aircraft.
 * The aircraft cruises **faster with an aft CG** because of reduced
   drag. The drag is reduced because a smaller AOA and less downward
   deflection of the stabilizer are required to support the aircraft
   and overcome the nose-down pitching tendency.
 * The aircraft becomes less stable as the CG is moved aft. This
   is because when the CG moves aft, it causes a decrease in the AOA.
   Therefore, the wing contribution to the aircraft's stability is
   now decreased, while the tail contribution is still stabilizing.
   When the point is reached that the wing and tail contributions
   balance, then neutral stability exists. Any CG movement farther
   aft results in an unstable aircraft.
 * A forward CG location increases the need for greater back elevator
   pressure. The elevator may no longer be able to oppose any increase
   in nose-down pitching. Adequate elevator control is needed to
   control the aircraft throughout the speed range, down to stall.

# High Speed Flight

*NB. I'll omit this section in the online notes, but is an interesting
read.*
