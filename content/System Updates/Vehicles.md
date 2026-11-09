---
title: "Vehicles"
---

Modern vehicles such as motorcycles and cars are commonplace in the cyberpunk world. Using the 5e ruleset, vehicles are objects that can serve as **mounts**, and so the rules involving vehicles are written with the mounted combat rules as a basis.

Vehicles can be **uncovered** (e.g. motorcycles) or **covered** (e.g. cars and vans), and additional rules apply for **covered** vehicles. Also, each vehicle has a **cargo capacity**, which is the amount of weight it can carry apart from riders, unless the DM decides the rider is particularly heavy.

## Entering a Vehicle

Once during your move, you can enter a vehicle that is within 5 feet of you, or exit a vehicle. Doing so costs an amount of movement equal to half your speed. For example, if your speed is 30 feet, you must spend 15 feet of movement to enter a vehicle. Therefore, you can't enter it if you don't have 15 feet of movement left or if your speed is 0. Some vehicles, such as boats with decks and buses, can be boarded by simply moving onto them, but sitting in a seat will require half your movement speed.

A creature must be at most one size smaller than the vehicle to enter it if it is a covered vehicle, or at most the same size if it is an uncovered vehicle. Every vehicle has a **seat capacity**, which is the maximum number of Small or Medium creatures that can comfortably fit into the vehicle. 2 Tiny creatures can fit into one seat, and a Large creature takes 2 seats. Huge and Gargantuan creatures are generally unable to sit in a vehicle, unless it is built to hold them as cargo. A vehicle can additionally seat up to half its seat capacity (rounded up) more than its normal capacity, however, all creatures in the vehicle are considered **squeezing** if it is beyond the seat capacity of the vehicle.

### Locked Vehicles

Covered vehicles may be locked from the outside before they can be entered. If the vehicle is locked, you must unlock it before entering. If you have the key to the vehicle, you can unlock it with an object interaction or a Use Object action. If you have Thieves' Tools, you may also use an action to try to unlock the vehicle with a Dexterity (Thieves' Tools) check. More secure vehicles will require a higher DC to unlock.

## Controlling a Vehicle

In order for a vehicle to be controlled, it must be **started**. If you have a key to the vehicle, you may start the vehicle with an object interaction or a Use Object action.  You may also use an action to make an Intelligence check to hotwire the car and start it. If you have proficiency with Tinker's Tools or Mechanic's Tools, you can add your proficiency bonus to the check. More secure vehicles will require a higher DC to start.

When the vehicle is started, one creature in the vehicle must be the **driver**, while the rest are **passengers.** Every creature seated in the vehicle is considered **mounted** on the vehicle, and mounted combat rules apply, with the **driver** controlling the vehicle. The vehicle does not act independently.

The driver must have at least one free hand to control the vehicle. If the driver removes both hands from the vehicle controls, or takes an action that requires both hands, they cannot control the vehicle until their next turn. If the driver is incapacitated or cannot take actions, the vehicle cannot be controlled until the driver can take actions again or if one of the passengers uses their action to become the driver, at which point the previous driver becomes a passenger.

### Vehicle Proficiency

Proficiency with vehicles is a tool proficiency, split into three types: **vehicles (land)**, **vehicles (water)**, and **vehicles (air)**. Any adult humanoid can drive most land and water vehicles, but only those specially trained with a vehicle type are proficient with it. While you drive a vehicle you are not proficient with, the vehicle has disadvantage on ability checks and saving throws. You can't drive an air vehicle unless you are proficient with vehicles (air).

You can gain vehicle proficiencies from the following sources:

- **Backgrounds.** The [[Cop]], [[Military]], [[Nomad]], [[Street Punk]], and [[Technician]] [[System Updates/Backgrounds/index|backgrounds]] grant proficiency with one or more vehicle types.
- **Feats.** The [[Feats#Vehicle Ace|Vehicle Ace]] feat grants proficiency with all vehicles. Any feat that grants a tool proficiency, such as Skilled or Prodigy, can be used to gain a vehicle proficiency.
- **Training.** During downtime, you can learn one vehicle proficiency from an instructor, such as a driving school, a flight school, or a willing mentor. Training takes 10 workweeks, reduced by a number of workweeks equal to your Intelligence modifier (an Intelligence penalty doesn't increase the time), and costs 2,500 cp per workweek.

### Skills

Depending on the situation, the DM may call for the vehicle to make ability checks to overcome a challenge. These skill checks are made using the vehicle's ability modifiers. By default, the vehicle is not proficient with any skills.

If the driver is proficient with the vehicle, they may add their proficiency modifier to the check. Additionally, if the driver can double their proficiency with the skill (such as through Expertise), they may instead add double their proficiency modifier with the check (they must still be proficient with the vehicle to add this).

The following are examples of vehicular skills in use:

* **Strength (Athletics):** Cross a barrier or uneven section of road.  
* **Dexterity (Acrobatics)**: Weaving through traffic at high speeds, drifting around a turn, or performing aerial tricks.  
* **Dexterity (Stealth)**: Moving quietly down an alley, stealthily floating up a canal, avoiding being spotted against cloud cover.

## Vehicular Combat

As with mounted combat, the vehicle shares initiative with the driver, and the vehicle can act even on the turn it is started. A vehicle only has three action options: Dash, Disengage, and Dodge. If the vehicle was just started, it cannot take the Dash action, as it needs to accelerate first.

### Armor Class and Hit Points

Each vehicle has an Armor Class and Hit Points, just like all creatures, and can be targeted by attacks. However, the construction of a vehicle gives it some durability against damage, represented by a **damage threshold** (see the [[Vehicle List#Vehicles Table|Vehicles Table]]). A vehicle is immune to damage from a single attack or effect unless that damage equals or exceeds its damage threshold, in which case it takes the full damage as normal. Resistance and vulnerability are applied before comparing the damage to the threshold. Furthermore, all vehicles are immune to poison and psychic damage, and have resistance to piercing and slashing damage.

When a vehicle's hit points reach 0, it explodes. When the vehicle explodes, all creatures within 10 ft of the vehicle must make a Dexterity Saving throw against the vehicle's **Crash DC**, taking the vehicle's **explosion damage** on a failure, or half on success. These numbers can be found in the [[Vehicle List#Vehicles Table|Vehicles Table]]. The vehicle can no longer be used if it has 0 hit points until it is repaired at a shop.

### Damage to Riders

All riders in a vehicle can be targeted by attacks. Riders in a **covered** vehicle have half-cover against attacks from outside the vehicle. If a rider is Small or smaller, they instead have three-quarters cover against attacks from outside the vehicle.

In addition, covered vehicles provide protection to its riders against spells from outside as long as the vehicle still has hit points. Vehicle riders have advantage on all saving throws from spells that originate outside the covered vehicle. In addition, they take half damage from any spells that originate outside the covered vehicle.

### Crashing

A **crash** occurs when a vehicle attempts to move into a space already inhabited by another object, vehicle, or creature. The damage done to both the vehicle and the target it crashes into depends on the vehicle's speed and size. A vehicle can attempt to crash into a specific target no more than once per turn.

When a vehicle crashes into a target, roll 1d6 for every 10 feet the vehicle moves in a straight line before the crash. This is the **crashing damage**. If the vehicle and its target are equal in size, apply the crashing damage as bludgeoning damage to both the vehicle and the target. When a vehicle collides with a target in a different size category, the larger of the two takes half the crashing damage (rounded down), or zero damage if it is two size categories larger. The smaller target takes the total damage rolled. If the target is a creature or vehicle being driven by a creature, the target may make a Strength or Dexterity saving throw (creature or driver's choice) against the vehicle's **Crash DC.** On a successful save, all crashing damage is halved. If the target is a vehicle and the driver has proficiency with the vehicle, they may add their proficiency bonus to a saving throw.

Riders inside a vehicle involved with a crash take half the crashing damage taken by the vehicle as bludgeoning damage if the vehicle is the same size or smaller than the target. Damage from falling is treated in a similar manner, with riders taking half the damage from the fall.

If the vehicle crashes into a target whose size is equal to or larger than the vehicle, the vehicle stops, otherwise the vehicle can move freely through the target's space, and the target is pushed to the nearest empty space outside the vehicle's path at the end of the current turn. For crashes into walls, buildings, and other immobile objects, the DM may choose the relative size of the target, and whether the vehicle stops or the target is destroyed.

#### Seat Belts

All vehicles have seat belts installed for each seat. As a bonus action, a creature sitting in a vehicle can equip or remove a seat belt on themselves or another creature sitting inside the vehicle. A creature wearing a seatbelt has resistance to damage caused by crashing, can't move, and cannot be pushed or pulled by any effect. Dealing 5 hit points of slashing damage to the seat belt (AC 10) destroys the seat belt.

### High-Speed Chases

Vehicle speeds and statistics given are for combat in smaller spaces, and so vehicles won't be able to accelerate to their full speed. However, there are times when all vehicles have accelerated to a similar average speed in the same direction, resulting in a **high-speed chase**. Special rules apply to high-speed chase combats.

1. Vehicles cannot take the Dash action unless the driver uses their action to let it do so. If the vehicle is Dashing, all targets that the vehicle attempts to crash into on its turn have disadvantage on their saving throws to avoid crashing, but the vehicle has disadvantage on Dexterity saving throws against [[#Road Hazards|road hazards]] until the start of the driver's next turn.  
2. A spell or effect that is anchored to a point, such as Entangle, Spike Growth, or Wall of Force, remains in place until the start of its creator's next turn, and is then left behind as the chase continues. If the effect requires concentration, the concentration ends when it is left behind. An effect that is centered on a creature or vehicle, such as Spirit Guardians, moves with it as normal. An effect that its creator can move, such as Spiritual Weapon or Flaming Sphere, keeps pace with the chase as long as its creator moves it on each of their turns; otherwise, it is left behind at the start of its creator's next turn.  
3. When a vehicle would enter, collide with, or be enclosed by a spell or effect that is anchored to a point and was created during the chase, such as Wall of Force, Wall of Stone, or Forcecage, the vehicle makes a DC 13 Dexterity saving throw. On a success, the driver swerves around the effect, and the vehicle can move past it as if it weren't there. On a failure, the effect applies to the vehicle and its riders normally.  
4. All vehicles have advantage on ability checks and saving throws against effects that would restrain them.  
5. If you fall out of a vehicle during a chase, you automatically take 1d4 bludgeoning damage for every 10ft of the vehicle's speed and are knocked prone. You are also removed from combat, as the chase has immediately left you behind.

#### Chase Grid

Vehicles cover a lot of ground in a high-speed chase, so chases are played on a grid of **10-foot squares** instead of 5-foot squares. If some combatants aren't in vehicles, use the normal 5-foot grid instead. The following rules apply on a chase grid:

- **Space.** A Large or smaller vehicle occupies one square, and a Huge or Gargantuan vehicle occupies a 2-by-2 area of squares. Only one vehicle can occupy a square.
- **Rounding.** Any distance that isn't a multiple of 10 feet, such as a weapon's reach, a spell's area of effect, or the distance a creature is pushed, rounds up to the next multiple of 10 feet. When a vehicle's speed is halved, it rounds down to the nearest multiple of 10 feet instead.
- **Melee Attacks.** Any creature can make melee attacks against creatures and vehicles in adjacent squares, regardless of its weapon's reach.
- **Reach Weapons.** When you make a melee attack with a weapon that has the reach property, the target's cover from a vehicle is reduced by one degree: three-quarters cover becomes half cover, and half cover becomes no cover.

#### Road Hazards

During a high-speed chase, the road itself can be as dangerous as anyone chasing you. The DM may call for a vehicle to make an ability check or saving throw (see [[#Skills]]) to deal with a **road hazard**. A vehicle that fails might take bludgeoning damage, slow down, spin out, or crash, and its riders take half the damage the vehicle takes, as with [[#Crashing|crashing]]. Some examples of road hazards and the checks they might call for:

- **Debris, potholes, or an oil slick:** a Dexterity saving throw to keep control.
- **A hairpin turn, a construction zone, a narrow alley, or a crowded sidewalk:** a Dexterity (Acrobatics) check to maneuver through.
- **Cross traffic or a tram crossing:** a Dexterity saving throw to avoid a crash.
- **A flooded street, a gap in the road, or a barricade:** a Strength (Athletics) check to power through or jump it.
- **Blinding neon glare:** a Constitution saving throw made by the driver.

## Modding a Vehicle

Customizing a vehicle makes for a very personal ride, and it's commonly seen throughout the cyberpunk world. From the purely cosmetic to full-on mechanical upgrades, a lancer's ride can be an extension of themselves and their crew. The rules here cover mechanical upgrades. Someone who modifies a vehicle is called a **modder**, and a mechanical upgrade to a vehicle is called a **mod**.

### Installing Mods

Vehicles can only be modded and repaired in facilities with the right equipment: land vehicles require a garage, water vehicles require a marina, and air vehicles require a hangar.

A modder must have proficiency with Mechanic's Tools to add a mod to a vehicle. To begin, the modder makes a Mechanic's Tools check. On a result of 8 or higher, they can add **one mod** over the course of a day. On a result of 18 or higher, they can instead add **two mods**. Multiple modders can work on the same vehicle together.

The maximum number of mods a vehicle can have depends on its size.

| Vehicle Size | Maximum Mods |
| :---- | :---- |
| Medium | 2 |
| Large | 3 |
| Huge | 4 |
| Gargantuan | 5 |

### List of Mods

Almost every vehicle encountered in the cyberpunk world is a vehicle from the [[Vehicle List#Vehicles Table|Vehicles Table]] with some variety of mods. Unless a mod says otherwise, a vehicle can't have more than one of the same mod.

The prices below are for Medium and Large vehicles. Prices are doubled for Huge vehicles and quadrupled for Gargantuan vehicles.

| Mod | Price (cp) |
| :---- | :---- |
| [[#Armor Plating\|Armor Plating]] | 12,000 |
| [[#Improved Suspension\|Improved Suspension]] | 8,000 |
| [[#Nitro Boost\|Nitro Boost]] | 4,000 |
| [[#Reinforced Chassis\|Reinforced Chassis]] | 6,000 |
| [[#Turbocharger\|Turbocharger]] | 10,000 |
| [[#Weapon Mount\|Weapon Mount]] | 5,000 |

#### Armor Plating

Thick composite plates are bolted over the body panels and the windows are swapped for ballistic glass, turning the vehicle into a rolling bunker at the cost of a lot of extra weight.

The vehicle's AC becomes 19 if it was lower, and its damage threshold increases by 10. It also gains resistance to acid, bludgeoning, cold, fire, lightning, and thunder damage. All of the vehicle's speeds are reduced by 10 feet.

#### Improved Suspension

Stiffer springs, adjustable shocks, and sway bars keep the vehicle planted through hard turns and rough roads.

While the vehicle is controlled by a driver, it has advantage on Dexterity checks. This mod can only be installed on land vehicles.

#### Nitro Boost

A bottle of nitrous oxide plumbed into the engine. One push of a button, and the vehicle leaps forward.

A Nitro Boost has one charge. As a bonus action, the driver can expend the charge to increase the vehicle's speed by 30 feet until the start of the driver's next turn, and the vehicle doesn't provoke opportunity attacks until then. A vehicle can have up to 3 Nitro Boosts, each counting as a separate mod. An expended Nitro Boost can be refilled at a garage, marina, or hangar for 1,000 cp.

#### Reinforced Chassis

The frame is welded with extra cross-bracing and high-strength steel, letting the vehicle take a beating that would fold a stock model in half.

The vehicle's hit point maximum increases by half.

#### Turbocharger

A turbine driven by the exhaust forces extra air into the engine for more power and a higher top speed.

All of the vehicle's speeds increase by 20 feet.

#### Weapon Mount

A reinforced bracket, swivel, or roof turret bolted to the vehicle's frame, built to steady a heavy weapon that would be impossible to aim by hand.

A Weapon Mount holds one weapon with the [[Weapons#Firearm Properties|Mounted]] property or one firearm with the heavy property; the weapon is purchased separately. A vehicle can have more than one Weapon Mount, each counting as a separate mod. When the mod is installed, choose one of the following types:

- **Fixed Mount.** The weapon faces the direction the vehicle is facing, and can only target creatures and objects in front of the vehicle. The driver can attack with it while keeping one hand on the controls.
- **Turret.** The weapon can fire in any direction. A passenger can attack with it as the gunner, but the driver can't. A gunner operating a turret on a covered vehicle has only half cover from the vehicle, regardless of their size. A Turret can only be attached to a vehicle that is Large or larger.

Attacks with a mounted weapon use the attacker's normal attack bonus, and the weapon is reloaded as normal.
