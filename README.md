# open-source-scart-switch
Open Source Scart Switch - low cost, high quality media switcher built around cbt3244, k-scartx-024, and lmh1980

Most solutions to switching across multiple scart video sources currently have a few things in common:

1.  They are being using for RGBs video sources.
2.  The switching solutions are either stupidly expensive or inadequate in quality.
3.  Assembly by a novice is largely impractical.

I'm looking to change that in small, incremental doses.  Starting first with a 3 port, manually switched scart box, and then working up to a 12 port auto-switching monstrosity.

The cbt3244 is a well-understood bus-switching solution, so that was a no-brainer.  
https://www.evernote.com/l/AAMOAljebv1OZp_UJRJSk2qwRQ1ttH_liSk

https://www.engadget.com/2007/03/13/how-to-make-a-solid-state-a-v-switcher/


k-scartx-024 is a vertical mount female scart socket that is actually obtainable from mouser - I had to manually create the footprint for this, and I have 15 of them on-hand right now...so here's to hoping.

Finally, the lmh1980 purports to autodetect sync stripping needs, so we will use that to make sure we have pure csync at the destination.  Ideally, we would just pass the sync line from all inputs indescriminiately at this IC, and trust it to spit out a pure csync.
