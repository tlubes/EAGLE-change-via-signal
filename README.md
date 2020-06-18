# EAGLE-change-via-signal

I came across the problem that I have a bunch of vias on my board and when I want to change their signal to connect them to the ground planes on either side of my board I had to manually name them. Even if I renamed one and then copied it, the signal name always incremented in some way...so I came up with this short ULP. If anyone knows a different way around this porblem, I am very happy to know!
I just got started with Eagle and EDA projects in general so any help is appreciated!

Next I want to go for a smarter approachfor a ULP that figures out which signals are solely used by a single via and not any other component/trace and apply the action to these without the need to group.
