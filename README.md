Small mod that adds various info when you encounter a fleet but before deciding to engage it.
This is an utility mod, it can be added or removed mid-save.
Requires Lunalib and Lazylib (which you need anyways for lunalib and 99% of modern mods) as of v1.1.0

Displays information such as number of ships on each side, DP total, autoresolve strenght (Fleet Power or FP) and the estimated +%EXP bonus due to battle difficulty (using vanilla calcs).
Excludes civilian ships from the number of ships and DP count, as they are not really relevant but it does count the FP they contribute (and will tell you separately how much civvies are contributing which is usually not a lot, mothballed ships are also not counted and they dont add FP so yeah also skips those).

When its just a 1v1 fight its pretty straightforward, if its you fighting multiple fleets, all the enemy fleets will be combined and counted as one.
Also supports allied fleets!, you can bump into one to see how strong are your patrols actually are.
And even supports ongoing combats!, see those gigantic 15 fleet battles in nex of about 7 different factions clashing in your system? Well you can now check out how the battle is going by clicking on the enemy fleet which will show you the stats on your allied doomstack (yourself being excluded) vs the enemy doomstack; letting you know if you actually have go to in and handle it or if you can just let the mess of fleets sort each other out.

At first it was a discord only mod I discovered in USC back in 0.96 release that did pretty much the same thing except also counted civilian ships, didnt separate civvie FP from warship FP and didnt tell you how the %EXP. Sadly I lost the original post was either deleted or is so buried I couldnt find it, however the original author did publish the mod as a "DO WHATEVER YOU WANT" license so I just kept changing things and kept their name in the authors section (as they did 99% of the work).

KNOWN BUGS:
Stations break the +%EXP bonus.
Does not cover all the ways you can encounter a fleet, so for the more complicated encounters it may not show you the numbers.
Does not include fleet commanders in officer count.

TO DO

- Fix bugs
- When you encounter an ongoing battle, inform you if you can autoresolve it if you get involved.
- Display more detailed stats (default will stay as is or minimal changes, because displaying too much will just lead to clutter but may be useful for modders wishing to see some stats, or well people interested in numbers; because really you dont need to know how much FP is the enemy onslaught adding compared to the kite)
