---
layout: default
title: Sim Rules
nav_order: 7
---
# CHAOS INDIVISVM 
{: .no_toc }
- Sim Rules

Updated: 07/26/2026 - July 26th, 2026

Authors: Dread Hudson, Hadet Sonnenkern, & Sam Huntsman

The most up to date ruleset will always be available at : 
https://docs.chaos.church/docs/sim-rules/

Don't be stupid, Don't try abusing loopholes. If you're acting like a little kid, You will be treated like a little kid.
If your group declares its intentions to be obnoxious little assholes don't expect any quarter to be given, You are responsible for who you associate with.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# General Rules - TL;DR VERSION
1. The rule of cool applies - If you do something cool that bends one of these rules, but let us know what it does and how it bends a rule, we may allow it.
2. Don't shoot through walls, use wireframe, or any other client side assistance to get an edge over other people. That isn't fun.
3. Don't use mono bullets, Mono bullets cause a ton of script run hiccups.
4. Raycast trails must be visible, glowy lasers are cool and high visibility is a tradeoff against physical prim munitions.
5. Raycast your Explosions, Melees, and Interceptors. If they go through walls don't use them here. No group safe or repair munitions, and no auto melees.
6. Explosives should be interceptable, counter interceptors with chaff.
7. Infantry repair tools only, scale the values based on loadout sacrifice. The tech axe repairs fast because it replaces a main weapon, use that logic with your repair tools accordingly
8. Don't beta test gear without asking the OIC
9. LBA armor systems only
10. No self healing armor unless it's a riot shield not in use or a LBA light vehicle shield that isn't active
11. Don't GPU crash, Steal content, Mass AR or Doxx people.

# Expanded Rules - LONG VERSION 
## I. Don't be an Asshole:
Examples of this include:
1. Intentional Primshooting
2. Using any form of Clientside Assistance. Wireframe, ARC, Collision Skeletons, Hitboxes, etc. If you are discovered to be doing this you're gonna get griefed for pretty much forever.
3. Using anything you specifically ban in your sim. If you think it's bullshit enough to ban it, You shouldn't be using it.
4. Not listening to what the OIC says; If you're being told not to do something then don't do it.
5. Renaming equipment to get around the banned equipment enforcer. If it's on that, it's on it for a good reason, and trying to evade it may get your entire raid party griefed.
    * This **will** get you a week ban right off the bat.
6. Engaging people in non combat areas. The VR room is off limits for combat, as is the armoury and AFK room. If people are in these areas, they are busy doing other shit. If someone is busy in these areas and you are messing with them you will be removed from the sim.
7. Ensure any AO being used does not differ from your hitbox location, if your flippy ninja AO moves your visual away from where you can be hit it is not allowed in our sim.
8. Violating any of the "BIG 4" - Doxxing, GPU crashing, Mass ARing, Content theft

# II. Equipment: (Any device deployed on the field of battle)
    
## ALL EQUIPMENT:
1. You are to use the most up to date versions of your gear at all times.
    * If you are using an outdated piece of equipment in order to gain an advantage over someone, you will be removed from the sim.
    * Don't Alpha-Beta-Tantrum test gear in our sim without asking the OIC. Having a piece of gear wildly change how it works based on how frustrated you get during the fight isn't cool. If you are changing values in the middle of a fight to make something more powerful you will be removed from the sim.
2. The rule of cool applies - If you do something cool that bends one of these rules, but let us know what it does and how it bends a rule, we may allow it.

## Weaponry :

### GUNS:
1. Don't use Mono bullets. We will revoke your ability to rez bullets if you do this shit.
    * We've shown ALL of you why Mono bullets are a bad idea, and it takes literally 10 seconds to swap a script from mono 
2. ALL WEAPONRY MUST HAVE A VISIBLE PROJECTILE! 
    * THIS MEANS - YOUR RAYCAST WEAPONRY MUST HAVE A VISUAL TRAIL, LIKE A LASER, FROM THE POINT OF EMISSION TO POINT OF CONTACT. DO NOT MIX YOUR TRAIL AND KILL PRIM.
    * ALL BULLETS MUST BE VISIBLE, NO INVISIBLE BULLETS! SUPPRESSORS ARE AN EXCEPTION, 150 M/S OR LESS PLEASE! TRACER BELTS ARE FINE BUT AUTISTIC!
3. Shotgun and shotgun hitscan methods must be publicly available on github, this does not mean you must open source your entire gun, just that the damage methodology is publicly available and transparent. Acceptable methods for shotguns include but are not limited to :
- Exclusively Raycast (https://github.com/Krutchen/rc-pellet-shotguns) *Our preferred method, an example is available in the attacker spawn
- Sensor Shotguns with distance & edge falloff (Not a flat damage falloff only cone)
- Traditional Prim (ideally you should use one of the above methods)
Shotguns MUST either have strictly partial damage pellets, or use a damage falloff system like in the rc-pellet-shotguns repo.
- Exclusively Raycast (https://github.com/Krutchen/rc-pellet-shotguns) *Our preferred method, an example is available in the attacker spawn
- Sensor Shotguns with distance & edge falloff (Not a flat damage falloff only cone)
- Traditional Prim (ideally you should use one of the above methods)
Shotguns MUST either have strictly partial damage pellets, or use a damage falloff system like in the rc-pellet-shotguns repo. 
                
### MELEES:
1. All melee weapons must utilize raycast checks to avoid killing avatars through obstructions.
2. Keep melee ranges reasonable, below 5 meters unless it's a two handed melee.
3. Melee weapons should have a cooldown between swings. Unless it's a chainsaw that does partial damage, you shouldn't be swinging as fast as you can mash the button. Automatic firerate for melee is gay.
4. No auto triggering melees. Triggering melee requires user input. Do note, however, that a big robot physically stepping on someone or a tank running them over with its treads is a roadkill and not a melee.
                
### REPAIR TOOLS:
1. Repairs values should take effective range and weapon layer into consideration, a close ranged handheld repair tool or something that replaces a rifle should repair more than a laser beam or some form of sprayer that can repair at range.
2. Repair tools must replace either a main-hand or offhand weapon, please do not make lame repair auras with zero tradeoff to the user

## Movement Enhancers : 

* No one should be Avatar Flying around the sim, and your avatar shouldn't be able to jump and fly from one end of the sim to the other.
1. Dodgerolls must be a standard 10 meters or less, and may not be triggered mid air. 
2. Grappling hooks are considered grappling hooks only IF they are of the reeling variety. Examples of this are the issued Chaos Indivisvm grappling hook and the DECO Hook. Bathooks will be considered jump packs and treated according to their rules! This also applies to actively spacebarring.
3. Jetpacks & Jump packs - Depending on the day and OIC, these may be allowed, however Jump and Jet packs MAY NOT refuel mid air.
    * There will be a display in the spawn informing you if we are limiting jump packs, if we are the scripted system will take care of the details.

## Deployables:

### Interceptors:
1. If you are using an grenade interceptor that is intercepting munitions through objects we will grief it and you. 
2. You must utilize checks to ensure your interceptor does not intercept vehicles, such as planes. Ask, and you shall receive the code snippet.
3. We prefer if Interceptors are Sensor based as opposed to using VolumeDetect, the reason being to cut down on Collision Events. 
            
### Artillery:  
1. Artillery may not auto-target avatars or objects.
2. Artillery may not utilize seeking munitions.
3. Artillery must have an operator within 10 meters, or a remote operator must sacrifice something significant from their loadout in order to use the system. For example, our artillery pack requires the sacrifice of both a pack slot and a 2nd layer offhand slot, and while it can fire remotely, it does not seek targets on its own, nor does it fire on its own. You can just act as your own spotter, so to speak. Chaos OIC has final say on what constitutes a significant sacrifice. Auto targetting artillery is not allowed.
            
### Teleporters:
1. All Teleporters must have a SOLID hitbox of AT LEAST 1m x 1m x 1m
2. Drop Pods are also considered teleporters, and must have a end beacon that adheres to the same size requirement as teleporters.
            
### Auto Turrets:
1. Turrets must have a lockon time of GREATER THAN 1 second, PREFERABLY adjusted to be longer the farther away a target is.
2. Turrets must not actively target through objects. Raycast that shit.
3. Turrets need to use a power grid and should be specialized, ie anti-infantry, anti-tank, anti-air, not anti-everything
            
### Repair capable Deployables
Repair deployables are not allowed.
This includes drones and deployable repair auras, basically any deployable that repairs anything else, regardless if it's armor, other deployables, or anything else you can think of. The only thing doing repairs should be a dedicated repair tool. These always snowball extremely hard and nobody ever makes them as fragile as they 'ought to be.
A deployable that repairs itself will NEVER be allowed in a Chaos Sim.

## Munitions:

### Direct Munitions:
* (Bullets, Rockets, etc, what makes contact and/or deploys radial munitions)

1. Standard damage enabled projectiles (Bullets) must die on collision with solid surfaces.
2. Projectile Rotations should be locked through `llSetStatus(STATUS_ROTATE_X|STATUS_ROTATE_Y|STATUS_ROTATE_Z,0);` on any non arcing munition, excluding seekers. 
    Munitions that arc through the air, ie grenades, mortars, etc, should have X and Z locked regardless. This is to prevent projectiles from wildly ricocheting.
3. Explosive projectiles should be no smaller than 0.06 meters, height and widthwise, non-phantom, and should be able to be countered by all interception systems. The counter to interception systems is Chaff, not making your explosive projectiles the same size as regular bullets. Low yield explosive bullets are the only exception to this rule. (Example, 3m bolter explosions, 1m kill and partial damage to the 3m mark)
4. Projectile Density should be set to 1000 or lower, to prevent bullets from bouncing physical vehicles.
5. Munitions must be fired along a interceptable trajectory. Under no circumstances can something warp from position A to position B with something between it.            
6. Seeking Munitions must adhere to the following:
    * Seeking Munitions must utilize physical movement, and must comply with the explosive munition hitbox regulation.
    * Seeking Munitions must utilize a raycast line-of-sight check for detected targets, and must not lock on if said raycast is obstructed.
    * Seeking Munitions may only proximity detonate on targeted aircraft and airborne avatars, and only within 5 meters of said locked on target.
    * Seeking Munitions may only deliver AT to the object they collide with.
    * Seeking Munitions must use a raycast check for 15 meters FROM or ON a surface to lock on, please do not make your missiles target literally everything without some form of counter balance. Do-everything weapon systems are are lame.
    * Seeking Munitions must have an audible lockon tone to be allowed in Milopolis. Ours have it so you can counter them with manually triggered flares, if you need help with this feel free to ask for the code.
7. Flak Munitions, defined as any proximity detonating non-seeking projectile, must adhere to the following:
    * Flak Munitions must utilize a raycast line-of-sight check for detected avatars, and must not detonate on if said raycast is obstructed.
    * Flak Munitions must utilize a raycast height check, and must not detonate if the target is under 15 meters from a surface
    * Flak Munitions may only proximity detonate within 10 meters of a detected entity.
    * Flak Munitions must scale according to the firing platform, At full auto, 5 AT is plenty for a vehicle, but unreasonable for infantry. You do not want to have a Hydra with 10 AT flak rounds swatting all your aircraft out of the sky.
    * Flak Munitions may not distinguish between friend or foe.
8. EXPLOSIVE OR AT BULLETS - Unless it's coming from a really big vehicle mounted gun, pick one or the other. If it's from Infantry, they should be fired at a low RPM.
    * Don't do dweeby "I wanna win" shit with excessively high AT Miniguns that melt tanks, that is not fun for anyone to fight.
                    
### Radial Munitions:  
* (Explosions, Gas, Smoke, Etc. Anything that isn't a bullet)

1. All munitions, excluding the single instance (sec. 2) described below, must utilize raycast checks to avoid killing avatars through obstructions.
2. High yield explosives, such as those fired from an appropriate artillery platform, at a velocity of under 50 meters a second, and that are fully effected by gravity, may do partial damage (based on distance), through obstructions. That means a siege gun, not a MBT.
3. Under no circumstance may a munition be Group Safe. Scripted objects intended to render someone immune from a particular form of munition (such as gasmasks) count as that munition being group-safe (we cannot control nor trust you on its responsible use).
4. Repair munitions are not allowed.

# III. Armour
 (Anything that tracks HP)
1. Due to inconsistent scripting, people still having their armour and movement functions in the same script, and the fact that it is now a COMMUNITY STANDARD with nearly
every ACTIVE group having adopted it, LBA Systems Sourced from the **MASTER** branch on the official LBA GitHub Repository are the only accepted armor systems in this Sim. If you are testing an update to one of these systems, please notify the OIC ahead of time. 
    * Future forks of the LBA project are either still in development or not open-sourced well enough and are not allowed at this time. Unmerged Pull Requests are not officially supported.
    * Non-Directional LBA Systems must not reduce any damage put into it, except for when the anti-grief system, USING STOCK VALUES, is triggered.
    * Directional LBA must provide verbose hit reports. This means it has to regionsay to the attacker how damage is being modified.
2. LBA Light Systems must accept all collisions over 10 meters a second.
3. Vehicle Hitboxes must accurately represent the visual model.
4. No HP tracking object may be Volume Detect. If any portion of a deployable is utilizing volume detect, a seperate HP tracking SOLID hitbox must accompany it. This hitbox must be AT LEAST 1x1x1m in size.
5. Keep your Armour script & Movement scripts in your vehicles seperate for the best possible responsiveness when taking damage. This is mandatory.
6. Armour may not self-repair. This includes passengers inside a vehicle repairing ANY vehicle with otherwise legal tools.
    * The exception to this are riot shields, and terminator-esque shields
    * Riot shields may heal over time when they are either destroyed or not in use. Riot shields 'Respawning' after being broken may heal at a faster rate. 'Respawning' riot shields must be inactive until FULLY recovered.
    * Terminator style shields may only heal when dropped, be it manually or when the shield is destroyed, not when it is actively protecting a vehicle.
    * Shields may repair to full (respawn) upon avatar death.
        
## Vehicle Balance: 
Because people are getting fucking retarded about it, Here's a refresher course in "why is my gunship being thrown off sim?" or "why are all of my prims being returned?".

1. Armour Values should reflect the size, speed, and firepower of the vehicle being used.
   * If your tank has an excess of 500 HP and several powerful weapon systems, It should naturally be moving at a snails pace.
2. Exposed operator vehicles of any kind should never exceed 25 HP, This goes for motorcycles, hoverbikes, hoverboards, riding lawnmowers, and whatever else people come up with.
3. Gunships may not exceed 175 HP.
    * What is a Gunship? An armoured flying vehicle with the main function of engaging ground targets. These are generally operated by one or two people.
4. Dropships may have up to 250 HP. 
    * What is a Dropship you may ask? A flying vehicle with the main function of transporting combatants to an area. They are generally lightly armed, or have crewed weapons, rather than being a one man killing machine.
5. Automatic interception systems on vehicles are ONLY allowed for fleetships. This is due to fleetships presenting an extremely large, obvious target, that utilize little to no cover, with limited mobility. They are naval vessels, not agile jet fighters. Triggered flares are allowed on non fleet aircraft. We have a lockon tone in our launchers that offers a fair warning for aircraft, you should as well.
            
# IV. Notes

## Rule Violations & Bans: 
1. There is now a three strike policy in place regarding violating the rules.
    * On your first offense, you will get a warning, then you will get locked in placed and/or glassed to make you pay attention, and then administrative action will be taken.
    * Afterwards, No warning will be given. 
    * Ban lengths - Offenses will be considered consecutive within the timespan of a week after expiration, If you're being an obnoxious little jackass about it, it will be a month.
    * This means if you get banned for 72 hours, and then come back six days later to act like a shithead again, your next ban will be for a week.
    * The first offense will be met with a 24 hour ban.
    * The second offense will be 72.
    * The third offense will be for a week.
    * Any offenses after this will be considered third offense.
    * You will not be PERMANENTLY banned for anything other than Doxxing, Sim Crashing, Graphics Crashing, Abuse Reporting, Intentionally disrupting sim performance (ie turning off rezzing or physics).
    * If you were banned for any reason a thread will have been made to log the ban. If a ban report cannot be found, the ban will be lifted after a period of 24 hours, to allow for any banning admin to explain it and provide said thread. They will be made fun of for not having done this beforehand.
    * Doxxing includes doing stupid shit with people's IRL information, not just releasing it. If you're acting maliciously with any of that we don't care to what extent, you're not welcome here.
    * If you feel you have been unjustly banned, and aren't just being a little smartass about it, Contact Hadet Sonnenkern, Dread Hudson, or Tyro Gutter. Punishment will be issued to the appropriate parties. This includes you.
    
## Administrative Staff:

* OIC
* Command Staff
* Land Group Moderators.

* While we may not ban you if you're doing something exceptionally stupid we may remove your ability to rez objects for some time and/or lock you in place until you have cooled down.

## HOW TO LBA
[GitHub](https://github.com/Krutchen/SLMCLBA)
