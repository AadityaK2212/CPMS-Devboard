# CPMS-Devboard


That Guy
added to the journal
DESIGN
1h logged
28d ago
Finished! :)
Did the finishing touches, and finished everything In JLCPCB

only issue is that I will need to buy some things seperately and hand soder them because JLCPCB does not have them in stock right now



That Guy
added to the journal
DESIGN
4.5h logged
30d ago
Finishing
I followed the tutorial, and finished it. It took a while, but i fixed my 63 errors, and did all the routing.

When I tried to upload to JLCPCB, the tutorial was not very helpful. I tried everything, and eventually got it through the first stsage. the the BOM. I had no idea how to do it, but after an hour, I installed a plugin, and got it. now, JLCPCB is showing me something weird in the viewer. I posted on slack, and will try to fix it tommorrow.



That Guy
added to the journal
DESIGN
1h logged
Mar 27, 2026
Routing
Nothing much, just a lot of routing, but not done with it. I did have to make a lot of things in the second layer tho.


That Guy
added to the journal
DESIGN
2.5h logged
Mar 25, 2026
Started routing the PCB
Today I started routing the PCB. the first bit went pretty smoothly, but then I started running into problems.

Some of the pins wouldn't connect, and I couldn't figure out why. I tried to figure it out on my own for 20 muinites, but couldn't figure it out. eventually, I asked on slack, and after a 15 minute discussion, I was able to fix it. then, I was able to make the rest of the Flash easily.

I then started on the USB-C. it started fine, untill I realized that two of my pins were swapped for some reason, meaning that I would have to cross the traces to rout them, which would result in a short circut. I thought I was cooked, but then I did ANOTHER 20 muinites of reasearch, and I finally figured it out. except now I had to make multiple layers on my PCB. I fixed it, but I had to move a portion of one of the traces to another layer.

All in a day's work.




That Guy
added to the journal
DESIGN
2.5h logged
Mar 24, 2026
PCB layout
I mostly just started the PCB layout. It took a while and I had to watch a few tutorials, but I got it in the end. not completely done yet though.

The memory was too large, so the tutorial swapped it out for a different version. when I tried that, it wanst in the footprint libraries, so I had to go to SnapMagic and download it. afterwards, I realized they only have the footprint, and not the schematic, so I had to create my own after some more tutorials. I finished the schematic and I am currently wiring it up. will continue on the next session.



That Guy
added to the journal
DESIGN
0.75h logged
Mar 22, 2026
Footprints
I did all the footprints today. There weren't any problems, and I got through it surprisingly easily. also changed the crystal schematic a bit.



That Guy
added to the journal
DESIGN
2.5h logged
Mar 21, 2026
Finished PCB wiring
Finished the PCB design, now I need to make the model.

I finished the USB-C with only onw issue. I didn't know how to chage the capacitors, so I posted my question on slack, and someone answered. other than tht, USB-C went fine.

I did the pinout, which was very repetitive. that alone must have taken over 20 muinites. I didn't have any issues with it.

I did the crystal with only one problem. I didn't know, but KiCad updated one of thier schematic designs, so I asked on slack and fnished it.



That Guy
added to the journal
DESIGN
1h logged
Mar 21, 2026
Starting Devboard
Watched a small tutorial, looked through the tutorial, and started the Devboard.

I started making the devboard, but ran into some minor issues because the schematic of the RP2040 is not the asme as the one in the tutorial. It has the same pins, but in a different order. hopefully won't become an issue :)

Also started on the USB-C connecter, and it's going fine so far.

