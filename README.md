# RC1Computer
8-Bit Relay Computer inspired by Harry Porter and DipDot
# General Information
This Computer, inspired Harry H Porter III, Ph.D, Paul Law, and Youtuber DipDot, is (almost) completly made out of relays, 607 of them to be exact.

# Specifications
- 32 kb RAM
- It has ~11~ 15 8 Bit Registers. Some of them can also funtcion as 16 Bit Registers.
- A clock rate Between 3 and 8 Hertz
- 8 Bit Data and Instruction Bus, as well as an 16* Bit Adress Bus
<sub>*only 15 bits are actually used, but the 16th Bit is still usable for other Peripherals/More Memeory</sub>

# Changes in V0.2
- Changed how I managed the Bus on the RC-1. The Bus Board now encompasses all Register Signals and otherwise, except for the Timing pulses, which is only used by the Controller.
- Caught most the Routing mistakes I made in the first Version. The second run really helped spotting obvious and not so obvious mistakes.
- Added a board for the front panel functions. The switches are not mounted on the Board however, and so are the LEDs.
- I also started experimenting with Capacitor Storage. I included my initial design in this version.
- The memory board had an overhaul, with more isolation and better logic.
- The ALU has been split into two boards. I was able to do this because of the new backplane.

# Future features
- ~I want to make some sort Storage medium. A Tape interface, similar to DipDot's design, would be nice, although for a computer like that kind of lame in my opinion. I am thinking more like a paper based interface, like the one Usagi electric build for the [UE1](https://www.youtube.com/playlist?list=PLnw98JPyObn0v-98gRV9PfzAQONTKxql3). One Slight Problem thogh: _Reading_ may be somewhat easy, the _writing_ on the other hand may be a little challenge... We'll burn that bridge when we get there.~
- Tape Loader has been added, function not Tested however.
- The Second thing i want to make for this project is some sort of Serial/ Terminal output. That itself is not that hard all things considered, it's nearly a chip solution. The real problem is that the Computer most likely lacks any sort of speed for that kind of outpu. So i either have to buffer the output, make it _exceptionaly_ slow, or find some other way of sending a serial signal of of the Computer.

# Links
[Paul Law´s Youtube channel](https://www.youtube.com/@paul80nd), and his [personal Blog](https://www.relaycomputer.co.uk/).
[Harry Porter´s Webiste](https://web.cecs.pdx.edu/~harry/Relay/index.html), specifically, [this PDF](https://web.cecs.pdx.edu/~harry/Relay/RelayPaper.pdf).
Lastly, [DipDot´s Youtube channel](https://www.youtube.com/@dipdoting). He was the main inspiration for this project and his videos are well made.
