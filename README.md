# Configuration for my OpenBuilds CNC
This is the configuration file for my [OpenBuilds C-Beam Machine](https://openbuildspartstore.com/openbuilds-c-beam-machine/) CNC.

A git repo may not strictly be necessary, but i can, and i helps me documenting the changes i make on my machine.
Don't expect a super tidy repo here, if i have stuff to put here, i'll just do. Hope you find something usefull to you!

## The machine

It is equiped with a [Smoothieware](http://smoothieware.org/) [Smoothieboard 5X](http://robotseed.com/index.php?id_product=12&controller=product&id_lang=1), 3 nema23 motors, and a meanwell 24V PSU (motors and PSU came from OpenBuilds).
The spindle is a [makita RT0700C](https://www.makita-online.com/fr/affleureur-fraiseur/245/83/fresadora-multifunci%C3%B3n/affleureuse-d%C3%A9fonceuse-multifonctions-710-w-%C3%B8-8-mm-makita-rt0700c-detail) palm router.
I replaced the original spindle clam with an [65 mm aluminium one from aliexpress](https://aliexpress.com/item/32963412367.html) (the original one would not work for the makita router without an additional part).

### Limit switches
I installed 4 [endstops](http://smoothieware.org/endstops) : 
 * X-min
 * X-max
 * Y-min
 * Y-max

All are microswitches based, in normally closed configuration (safer : if the cable breaks, it activates an alarm)
As of now, i have nothing yet for Z. I will at least add a Z-max soon.


## Configuration
On the repo is the current configuration file i am using on the machine in CNC router mode. When i install and use the laser, i'll have another config file here(or another repo?)
### Axis direction
There was some tinkering to set the axis directions, the min an max, and now all is fine.
