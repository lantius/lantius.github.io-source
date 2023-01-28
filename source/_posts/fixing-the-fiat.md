title: Fixing the Fiat
date: 2023-01-28
tags:
---

### Fixing the Fiat

Back in December Caroline heard a 'pop' while sitting in the Fiat and got a ":warning: Service Electric System" warning on the dashboard.

The Fiat 500 forums were remarkably helpful, with lots of good reference information:

* [Fiat 500e BEV Student Guide](https://drive.google.com/file/d/1c_UQK1h5d8TZ7HwLqCGTvJXqxhPFjEy3/view)

Of course, to confirm that, I needed to find the existing fuse and test it - which would also confirm that I could work on the car without electrocuting myself.

On the latter point, the video of the [LoudFiat](https://www.youtube.com/watch?v=MC5gI_1gUQE) project to install a 104,000 Watt amplifier in a 500e was inspiring because it had much more of a #yolo attitude than I when it came to dealing with a 400V system:
<iframe width="560" height="315" src="https://www.youtube.com/embed/MC5gI_1gUQE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

I was able to narrow down a guess to it being [this fuse](https://www.mymoparpart.com/p/fiat__500E/FUSE-ASSEMBLY-Electric-Vehicle-Double-Ganged-Fuse-Inside-PDC-Module/61627546/68213308AA.html) in the PDC module connecting the heater to the HV system:
![(Source: https://www.fiat500owners.com/threads/main-375v-battery-tap.149308/post-1299427)](images/pdc.jpg)

After a bit of debugging and reading service manuals folks uploaded to the internet I was able to order the replacement fuse, safely disconnect the high voltage system and put in the new fuse without dying. Getting the car working again after that was complicated by the 12V battery voltage getting low, which triggered faults in the high-voltage interlock system.

Finally got the battery swapped out and used an OBD2 app to clear all the codes and bam says the lady she's drivin' again!
