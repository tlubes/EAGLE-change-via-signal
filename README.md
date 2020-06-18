# EAGLE-change-via-signal

I came across the problem that when I have a bunch of vias on my board that are for example supposed to connect the ground planes on both sides, I had to manually name every single of them. Even if I renamed one and then copied it, the signal name always incremented in some way...so I came up with this short ULP. If anyone knows a different way around this problem, I am very happy to know!
I just got started with Eagle and EDA projects in general so any help is appreciated!

Next I want to take a smarter approach on a ULP that figures out which signals are solely used by a single via, which happens when you just place a via and don't name it, and not any other component or trace and apply the action to these without the need to group them.
