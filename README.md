# EAGLE-change-via-signal

I came across the problem that when I have a bunch of vias on my board that are for example supposed to connect the ground planes on both sides, I had to manually name every single of them. Even if I renamed one and then copied it, the signal name always incremented in some way...so I came up with this short ULP. If anyone knows a different way around this problem, I am very happy to know!
I just got started with Eagle and EDA projects in general so any help is appreciated!

The smart approach does not require one to group the vias wanted to be changed. It rather assumes that the vias that do not have any polygon, trace or part on the same signal are just newly places and supposed to be changed to the requested signal. I am still testing this though.
