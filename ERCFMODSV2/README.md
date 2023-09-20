To probably get everything to make up will probably be the V2 at somepoint requires pulling files from 6 different repositories below.

This is the main ERCF repo which is really dated at this point, the manual is still useful for a first timer. I really suggest getting most of the stl files needed from the sturdy bunny project.
https://github.com/EtteGit/EnragedRabbitProject

Then the sturdy bunny project which replaces the threaded rods with a piece of 2020. If you are going triple decky then do not print any of the blocks, only the parts needed to attach the ERCF to the 2020.
 https://github.com/sneakytreesnake/SturdyBunnyProject

Triple decky this is really a whole redesign of the blocks for loading and unloading filament, version V6.3 is the latest and this allows 3 position servo control over each filament block, really innovate work here from Gneu. This mod really need a good digital servo though like the Savox SH0255MGP, you can use other digital servos just make sure they release when signal removed or they will return to neutral which will not work. You can program most digital servos though with a programmer.
https://github.com/gneu42/Triple-Decky

Then also springy which fixes the issues of various pressure requirements to feed filament on each block. 
https://github.com/moggieuk/ERCF-Springy

Then you have Happy Hare V2 which is the software that makes it all happen. 
https://github.com/moggieuk/Happy-Hare

Also binky is a nice upgrade to the optical encoder for filament encoding. Currently only available for pruchase from a couple of EU vendors, but still ~$30 shipped to your door.
https://github.com/mneuhaus/EnragedRabbitProject/tree/main/usermods/Binky

And last a filament cutter which I think is a must have. This saves all of the hassle with tip forming. 
https://github.com/sorted01/Filametrix




This below from Moggieguk:

Hi!  Happy Hare is (has) growing to support all types of MMU types and configurations.  For best ERCF experience you want, IMHO, a quality homing point at the extruder. If you don't then you can fallback to colliding with the extruder and detecting that through encoder feedback or stallguard.  The toolhead sensor past the gears provides both homing point and good indication of filament in the extruder, but support for a sensor just prior to the gears is ready to roll out.

ERCF v2 is a community project (powered by Happy Hare).  The intent was to fix the major issues with the ERCF design but not change anything fundamental. 

A few of us came up with the idea of community ERCF v2 . Here is the initial list of goals.  We are up to number 11... 🙂

Goals:
Simplify construction (without any significant additional costs)
Aim for out of the gate reliability (i.e. wider tolerance for certain parts)
Quicker set up time / less config
Align with current BOM and design as closely as possible.

Components:
Sturdy backbone (Sturdy Bunny from @sneakytreesnake V2.3804 V2.3804 V2.3804) https://github.com/sneakytreesnake/SturdyBunnyProject
Reliable encoder (Binky from @Marc VT.483 VT.483)
Remove need for top hats with sprung servo (Springy from @moggieuk V0.1503 | V2.4088 V0.1503 | V2.4088) https://github.com/moggieuk/ERCF-Springy
4.Remove snag points on reverse filament flow (for EndlessSpool support)
Improve gate mechanism so filament does not slip back through accidentally (Triple Decky from @gneu V2.5345) https://github.com/gneu42/Triple-Decky
Remove high wear parts / those prone to breakage (the servo arm improvements / bearing)
Formal filament bypass (including position in selector array)
Standardized layout so things like calibrating the selector is mostly automatic
Major Happy Hare update
Magnetically connector cover
Updated manual
Since this project was started the filament cutter has appeared and I think a very good addition -- Happy Hare now supports it too.
