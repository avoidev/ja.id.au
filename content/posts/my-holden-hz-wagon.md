---
title: "My Holden HZ Wagon"
date: 2022-03-01T21:10:27+10:00
draft: false
---

Sections:

+ [My HZ Wagon](#my-1977-holden-hz-wagon)
+ [Engine Rebuild](#holden-202-red-engine-rebuild)
+ [Custom Arduino gauges](#custom-gauges-fuel-and-temp)

# My 1977 Holden HZ Wagon 

## Specs:
Engine: 202 Red Motor (Matching numbers 😏)
Transmission: Trimatic (Column Shift)
Differential: Fine spline banjo diff.

### Completed Works
+ Seats have been freshly reupholsters
+ Minor body work repairs, vehicle previously was T-boned in the passenger rear quarter.
+ HEI Dizzy has been fitted from Blue/Black 202, with appropriate coil.
+ ["Custom” Temp and Fuel Gauges](/post/custom-gauges)

### Todo:
* Engine has weak compression on 2 cylinders (1 and 2). Another engine is currently being built.
* Rust in lower sills need cutting out and repairing.
* Rust in the roof needs addressing.
* Door cards are “rotting” need to replace those. I want to replace the the door cards and rear cargo panels with stamped aluminium.
* Run new Fuel/Brake lines, custom made full steel pipes. Will have to add distribution block and fuel pressure regulator to accommodate the triple SUs.
* Revisit drivers side passenger footwell panel.
* Stick down carpet better with contact adhesive.
* Fix wiper motor so that it actually has 2 speeds. (Slow and Extra Slow)


-------------------------------------------------------------------


# Holden 202 Red Engine Rebuild

My current engine in my [wagon](/posts/my-holden-hz-wagon) is unfortunately running quite poorly. Oil weeps for most seals (rather common in these engines, especially when they’re 40+ yrs old) and also has low compression on the first two cylinders. I use this vehicle as my daily driver (when it behaves) so ideally I would prefer to keep it on the road while I prep another engine however the car has decided otherwise.

### Current List of Issues with the current motor/trans:

1. Low compression on cylinders 1 & 2. This could either be a few things.
Leaky head gasket. However oil drains fine and isn’t milky
Valves in the head aren’t seating properly preventing compression
Piston rings aren’t doing what they’re sposed to. (This is my guess as C1 gets a bit oiley at times.
2. Starter Motor just isn’t having a great time. I’ve know this has been an issue for a while but the excess amp draw kills my battery rather frequently.
3. Radiator has a mad weep, and the belt driven fan doesn’t cut the mustard when stuck in traffic. Temps easily in the high 90s

### Solution? Build up a new Engine + Trans!
I bought a running donor motor, another red 202 of similar era, and it also came with 2 addition trimatics and a handful of goodies like alternators, dizzies, carbies, oil pumps etc etc. To give you a money reference for this it all up set me back $1500. Which for mid 2021 Brisbane prices wasn’t half bad. This engine was also a bit sad and in need of a reco but that’s exactly what I wanted to do anyway. Engine was 30tho over on the bore and had a “perform cam” a 35666 from crow cams.

I really wanted to pick me up a Yella Terra head, these were performance heads made my Yella Terra by modifying bog stock cast heads off normal motors. Seem to be rather rare these days for I6s. I managed to snag a half decent one but it was out in Blackbutt which was solid 2-3 hour drive each way from where I live. Picked it up for $500 and unfortunately after picking it up realised it was a 161 head from an earlier model. No sweat though, as it’ll still bolt up fine just needed different pushrods to accommodate.

{{< img src="images/202-compression-ratio.png" >}}

When spec’ing this engine up I was concerned that the compression ratio would be too high, which to be honest it definitely is but I should still be able to get away with 98OCT at the bowser, more than likely moving this car from a daily to a weekender.


-------------------------------------------------------------------


# Custom gauges Fuel and Temp

First I scoured the internet to try and find specs for the Fuel and Temp senders
Fuel is 10 – 70ohms (Full – Empty)
Temp is 10 – 70 ohms (High – Low)

I used a multimeter and the engine temperature probe to measure the temp/resistance of water as it cooled.

I setup the fuel gauge as a linear change in resistance, unlike the variable relationship between temp/resistance. This is a pure guess as I haven’t done any exact measurements of the fuel sender, and couldn’t find any online. However I haven’t be stranded without fuel yet so it can’t be too far out.

I originally intended for this to be a temporary board that was just for testing purposes however it has been inside my car running fairly happy without hiccups for close to 6 months now.

{{< img src="images/gauge1.jpg" >}} {{< img src="images/gauge2.jpg" >}}{{< img src="images/gauge3.jpg" >}}{{< img src="images/gauge6.jpg" >}}


[Jump to the top!](#my-1977-holden-hz-wagon)