# Introduction #

To start porting we should develop some kind of plan: what needs to be done first, and what we should probably leave for later. And, obviously, who would implement each part.


# Details #

Existing port of snes9x to Dingoo native OS (named pocketsnes) should be taken into account. It has sort of platform dependent library, providing basic functions like video initialization, input handling, etc.

We could take PSP port as a base, because it already has arm assembly replaced with generic C code.