# SpooBu - A **Spoo**l **Bu**ffer aka Spool Rewinder


What if... we don't need a buffer but... rewind the filament back onto the spool...? This is SpooBu! A gravity-based filament spool rewinder. Imagine you're standing next to your printer and manually spinning the spool back when your MMU changes/unloads the filament. Since that would be very time-consuming, I invented SpooBu!

## How does it work?

It's a very simple mechanism: It's a spool holder with a counterweight that loads up as the spool spins, and then the counterweight spools the spool back up when the filament gets unloaded.

SpooBu is made out of three parts: a spool mount, a little gear on the spool mount, and a counterweight. When the printer feeds the filament, the spool starts to spin, and as the little gear is attached to the spool mount, it also spins. The little gear has contact with the counterweight, so when the spool spins, the little gear spins as well, which then spins the counterweight to move it upwards.
When the printer unloads the filament, the tension on the spool gets released, and the counterweight can move down again (thanks, gravity!). As it does that, it spins the little gear on the spool mount and therefore also the spool. Tadaa, your filament got rewound on the spool.


I did record a quick demonstration video of SpooBu: https://youtu.be/ba3n2fLI1wE

## How can I use it for my printer?

Parametric CAD design! Not much to say here, just measure the length of filament you have to buffer, paste that in the CAD file, print the files, and that's it :D. I made a little instruction video on how you can create your own set of files. Feel free to make a Pull Request with your files so others can use your files in case they have the same buffer length!

## Credits

Thanks to Pavel Hartmann for [his rewinder](https://youtu.be/otfgxMiwivw?si=FOWaNhXBAOYx1tBN) idea!

Thanks to all the people on my Discord for tinkering with me!

Thanks to [PurchenZuPoden](https://www.printables.com/de/model/65651-universal-filament-spool-holder) for the spool mount!
