# 3D printable Li-Ion battery pack for MPD, MPA, PLS, and TPX radios
Made by GE/Ericsson, also sold as M/A Comm (now owned by Harris)

The battery is a hybrid primarily designed to support two 18650 cells which perfectly matches the power requirements of this radio series. It is taller than the short packs and shorter than the tall packs. Included is a dual 18650 cell holder that fits inside the pack. You can also see there is a battery eliminator included as well.

![HTML formatted MPD Battery Suite log](/mpd_battery_parts.jpg)

## Designed for 18650 Li-Ion cells

The battery shell snaps together and is designed to be servicable. It accepts a standard on/off switch on the front panel, I *think* the original battery on/off switch will fit if you are borrowing parts from old packs. I've been using one of my prototype batteries for a couple of years now with no issues. 

There are holes on the back side of the pack near the bottom I use for adding recharginig contacts (bare wire threaded through the holes) that connect to a cradle charger. I intend to do more work on the design so the charging contacts are more recessed, but for now it works. I also wanted to add a DC jack to the battery as well for recharging but I haven't had time for that yet. 

![HTML formatted Front and back log](/mpd_battery_front-back.jpg)
![HTML formatted Inside log](/mpd_battery-inside.jpg)


## Charge controller, electronics?
Li-Ion charge control boards are now plentiful from China, you need a "2S 18650 charger" pcb board for 7.2V. I recommend putting it inside the battery pack as there is room, but you can save the expense and put it in the charging cradle instead if you want. This way you only need one charge controller board for all your MPD battery packs.


## Recharging cradle for these Li-Ion packs?
I also designed and released the Gadget Hamper universal charging cradle to support recharging of home-brew Li-Ion battery packs. They can be ganged together if you still want that massive gang charger feel with your old GE radios. I've updated the Gadget Hamper project with an MPD battery socket.

- https://github.com/dosman33/Gadget-Hamper
- http://gadgethamper.org


## Wiring them up and 18650 lengths
See the photos for wiring details. The on-off switch is wired in series with the positive battery lead as the original batteries were. There is another part that just shorts two contacts out on the battery. There is a slot in the bottom of the cell holder that accepts a common nickel battery tab across the bottom as shown. 

Also note that 18650 cells vary in length despite the fact this should not happen. Most 18650 cells have an over-current protection circuit on one end, and some 18650's are naked with no protection (required for vapes). I recommend using 18650 cells with current regulators. Even with these there are variations in length by as a few millimeters. If your cells are too short to make electrical just put something between the nickle battery tabs and the bottom of the cell holder until it makes solid contact with the cell. Here you can see I'm using stripped wire sheathing as a spring of sorts. Works fine to maintains solid contact at all times. The cell holder is designed to flex some at the ends as well.


## "I don't need your new fangled battery technology, give me my NiCD's!!!"
You may also build the battery with 4/5 sub-C NiCD's if you prefer to stick with your original charger. The battery pack base does fit the original charging equipment and I added holes for placement of the original charging tabs if you want to build the battery to work with existing infrastructure. Just disassemble an existing NiCD battery pack and borrow the internal wiring. You will have to use 4/5 cells like the short packs use (or something else that fits the shell).


## Printinig notes
Print the shell parts flat-side down with support. The battey eliminator should be right-side-up with support. On the battery rear half, the retaining clip is pretty weak and can break off or fails to print correctly sometimes, my experience is the fit of the assembled battery pack to the radio is pretty tight and doesn't really need the clip anyway.


## Other notes, errata:
I designed a belt clip too which fits the D-clip retainer slot on the radio, however this is mostly for laughs. The original D-clips were steel and a plastic part that fits the same space is very weak, it can't hold up to much use before breaking. Can be useful if you're just hanging the radio somewhere out of the way though.




TL;DR: This is a 3D printable battery pack 

- The latest version of this project is always available here on GitHub: https://github.com/dosman33/GE-MPD-BatteryPack
- This project is also on Thingiverse: 


This project is licensed under the CC BY-SA 4.0 license: https://creativecommons.org/licenses/by-sa/4.0/
