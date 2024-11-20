# ASM2464PD-RE
Reverse Engineering ASM2464PD USB4 to NVME Adaptors

I bought a bunch of these ASM2464PD USB4 to NVME Adaptors from Alibaba to test out for use with ThunderScope. Turns out the design of these are a lot simpler than the ones based on the intel chipset, so I figured I could make one myself. 

The ASM2464PD does not have a public datasheet, but there is one you can find if you are so inclined. You can find more info at [a-little-wifi's repo](https://github.com/a-little-wifi/ASM2464PD-test), where they are designing one of these adaptors as well!

I am avoiding using any leaked or non-public info for this project (see: [cleanroom design](https://en.wikipedia.org/wiki/Clean-room_design)). I'm not sure if it's actually useful legally for this project to exist, but I'll do it anyway since it seems like a fun first foray into reverse engineering!

Oh and this is all hardware (it's me afterall, I love me some PCBs), so for firmware stuff check out [Cyrozap's repo](https://github.com/cyrozap/usb-to-pcie-re). I'll have some flash dumps on here eventually once I put together a setup to do that.

## OSCOO XT6

This is the one I started with, seemed like a good candidate with it's generous decoupling and refrence designators.

TODO: nice write-up. For now check out [this thread](https://fosstodon.org/@aleksorsist/113495151019157816) and [this thread](https://fosstodon.org/@aleksorsist/113505931062014911) for some quick quips and pretty pictures.


## TBT 3 Support

It doesn't? But it should? Wtf is going on

## No more Mr. Nice Guy

Ok, I am no longer cleanroom reverse engineering this thing, I am now on a quest to figure out why this accursed thing doesn't work
