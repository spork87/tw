`tw` - A command line tweet log
===============================

Work on your social media from command line, perhaps even with no network.

Depends on `bash`, `Gnu utils`, and `ruler`.

The current version is a simple `bash` script, suitable for folks just learning
shell scripts, but it's possible future versions could post to one or more
social networks.

Usage
-----
With no options `tw` will show recent posts, the time and a ruler to guide
message length.

    $ tw
          21-21:51:21 A Plan for the Improvement of English Spelling by Mark Twain
          22-08:31:33 For example, in Year 1 that useless letter "c" would be dropped to be replased either by "k" or "s", and likewise "x" would no longer be part of the alphabet.
          22-13:32:55 The only kase in which "c" would be retained would be the "ch" formation, which will be dealt with later.
          22-13:33:49 Year 2 might reform "w" spelling, so that "which" and "one" would take the same konsonant, wile Year 3 might well abolish "y" replasing it with "i" and Iear 4 might fiks the "g/j" anomali wonse and for all.
          22-13:35:14 Jenerally, then, the improvement would kontinue iear bai iear with Iear 5 doing awai with useless double konsonants, and Iears 6-12 or so modifaiing vowlz and the rimeining voist and unvoist konsonants.
                04:23 Bai Iear 15 or sou, it wud fainali bi posibl tu meik ius ov thi ridandant letez "c", "y" and "x" -- bai now jast a memori in the maindz ov ould doderez -- tu riplais "ch", "sh", and "th" rispektivli.
                05:27 Fainali, xen, aafte sam 20 iers ov orxogrefkl riform, wi wud hev a lojikl, kohirnt speling in ius xrewawt xe Ingliy-spiking werld.
    20141024-19:12:
          ----.----1----.----2----.----3----.----4----.----5----.----6----.----7----.---_8_---.----9----.----a----.----b----.----c----.----d----.----e

The length guide doesn't limit you to long message entries (like the adding a
line from Dickens' "Tale of Two Cities").

    $ tw "In short, the period was so far like the present period, that some of its noisiest authorities insisted on its being received, for good or for evil, in the superlative degree of comparison only."
           21-21:51:21 A Plan for the Improvement of English Spelling by Mark Twain
           22-08:31:33 For example, in Year 1 that useless letter "c" would be dropped to be replased either by "k" or "s", and likewise "x" would no longer be part of the alphabet.
           22-13:32:55 The only kase in which "c" would be retained would be the "ch" formation, which will be dealt with later.
           22-13:33:49 Year 2 might reform "w" spelling, so that "which" and "one" would take the same konsonant, wile Year 3 might well abolish "y" replasing it with "i" and Iear 4 might fiks the "g/j" anomali wonse and for all.
           22-13:35:14 Jenerally, then, the improvement would kontinue iear bai iear with Iear 5 doing awai with useless double konsonants, and Iears 6-12 or so modifaiing vowlz and the rimeining voist and unvoist konsonants.
                 04:23 Bai Iear 15 or sou, it wud fainali bi posibl tu meik ius ov thi ridandant letez "c", "y" and "x" -- bai now jast a memori in the maindz ov ould doderez -- tu riplais "ch", "sh", and "th" rispektivli.
                 05:27 Fainali, xen, aafte sam 20 iers ov orxogrefkl riform, wi wud hev a lojikl, kohirnt speling in ius xrewawt xe Ingliy-spiking werld.
                    43 in short, the period was so far like the present period, that some of its noisiest authorities insisted on its being received, for good or for evil, in the superlative degree of comparison only.
     20141024-19:43:
           ----.----1----.----2----.----3----.----4----.----5----.----6----.----7----.---_8_---.----9----.----a----.----b----.----c----.----d----.----e


