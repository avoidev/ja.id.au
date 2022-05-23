---
title: "My Holden HZ Wagon 🚘"
date: 2022-03-01T21:10:27+10:00
draft: false
description: A thread of all everything I do to my classic Aussie car. 
---

{{< toc >}}

# Specs:
Engine: 202 Red Motor (Matching numbers 😏)
Transmission: Trimatic (Column Shift)
Differential: Fine spline banjo diff.

## Completed Works
+ Seats have been freshly reupholsters
+ Minor body work repairs, vehicle previously was T-boned in the passenger rear quarter.
+ HEI Dizzy has been fitted from Blue/Black 202, with appropriate coil.
+ ["Custom” Temp and Fuel Gauges](/post/custom-gauges)

## To-do
* Engine has weak compression on 2 cylinders (1 and 2). Another engine is currently being built.
* Rust in lower sills need cutting out and repairing.
* Rust in the roof needs addressing.
* Door cards are “rotting” need to replace those. I want to replace the the door cards and rear cargo panels with stamped aluminum ones instead.
* Run new Fuel/Brake lines, custom made full steel pipes. Will have to add distribution block and fuel pressure regulator to accommodate the triple SUs.
* Revisit drivers side passenger footwell panel.
* Stick down carpet better with contact adhesive.
* Fix wiper motor so that it actually has 2 speeds. (Slow and Extra Slow)

<br>

-------------------------------------------------------------------
# Holden 202 Red Engine Rebuild

My current engine in my [wagon](/posts/my-holden-hz-wagon) is unfortunately running quite poorly. Oil weeps for most seals (rather common in these engines, especially when they’re 40+ yrs old) and also has low compression on the first two cylinders. I use this vehicle as my daily driver (when it behaves) so ideally I would prefer to keep it on the road while I prep another engine however the car has decided otherwise.

## Current List of Issues with the current motor/trans:

1. Low compression on cylinders 1 & 2. This could either be a few things.
Leaky head gasket. However oil drains fine and isn’t milky
Valves in the head aren’t seating properly preventing compression
Piston rings aren’t doing what they’re supposed to. (This is my guess as C1 gets a bit oily at times.
2. Starter Motor just isn’t having a great time. I’ve know this has been an issue for a while but the excess amp draw kills my battery rather frequently.
3. Radiator has a mad weep, and the belt driven fan doesn’t cut the mustard when stuck in traffic. Temps easily in the high 90s

## Solution? Build up a new Engine + Trans!
I bought a running donor motor, another red 202 of similar era, and it also came with 2 addition trimatics and a handful of goodies like alternators, dizzies, carbies, oil pumps etc etc. To give you a money reference for this it all up set me back $1500. Which for mid 2021 Brisbane prices wasn’t half bad. This engine was also a bit sad and in need of a reco but that’s exactly what I wanted to do anyway. Engine was 30tho over on the bore and had a “perform cam” a 35666 from crow cams.

I really wanted to pick me up a YellaTerra head, these were performance heads made my YellaTerra by modifying bog stock cast heads off normal motors. Seem to be rather rare these days for I6s. I managed to snag a half decent one but it was out in Blackbutt which was solid 2-3 hour drive each way from where I live. Picked it up for $500 and unfortunately after picking it up realised it was a 161 head from an earlier model. No sweat though, as it’ll still bolt up fine just needed different pushrods to accommodate.

{{< img src="images/202-compression-ratio.png" >}}

When spec'ing this engine up I was concerned that the compression ratio would be too high, which to be honest it definitely is but I should still be able to get away with 98OCT at the bowser, more than likely moving this car from a daily to a weekender.

### Engine Update 10/04/22
So, the engine is finally back together and has been painted. With the help of my mate Liam, my Dad and youngest brother we removed the old engine from the wagon and begun putting the other Trimatic on the new donk, this one apparently has a "stage 2 kit" through it according to the previous owner, and has a slightly higher than factory stall range torque converter. 

I'm actually starting to get pretty keen, but also exceptionally nervous. What if this engine doesn't start after all I'm no expert by any standard and I've never build a motor before. But I'm more of the wait and see kind of guy, so if it nukes it upon first start up then it is what it is.

### Engine Update 23/04/22
After a bit of pain, and tons of concern I've finally, finally got the car running. About a week ago we span the car over for the first time, the car would cough and splutter but no way it would start. We spent the whole weekend diagnosing but really hadn't managed to take any steps forward, we checked ignition timing, spark plugs, leads, and the coil but it wouldn't start and to cut this long story short there were 3 main things that were causing this engine not to start. 

The first being the mechanical fuel pump, the one I fitted was one that came with this motor when I bought it, it was a gorgeous glass bowl fuel pump this thing looked great but sitting in someone's shed for the a decade+ probably ruined all the rubbers (duh). So swapping in my old and not so pretty mechanical pump resolved that.

The second probably was that my cylinder compression was all over the shop. The first cylinder was registering 0 PSI compression 😅 with all the others ranging from 30 to 110 PSI. I had a couple of ideas what would cause this, first was that I put the rings in wrong, second was that the adjustable rockers were set wrong and the third was that head/head gasket weren't sealing correctly.

I dreaded to think that I'd have to pull the head/motor apart again so I went on the assumption that it was the rockers since this is the easiest part for me to fuck up.

### Engine Update 15/05/22
So, she runs.

\<phew>

I can actually worry about the rest of it now. The carby mix is enough for it to idle and move which is totally **AWESOME**. I'm actually stoked, I've noticed that the rear main seal seems to leak which is a bit depressing but this is only a first go.

I went for a lap round the block which I and the car both survived, however there are a few new things to do. Only 2nd gear seems to work, reverse doesn't engage at all and neither does 1st and D. But hey, progress is progress.

<br>

-------------------------------------------------------------------
# Mods
## Custom gauges Fuel and Temp

First I scoured the internet to try and find specs for the Fuel and Temp senders
Fuel is 10 – 70ohms (Full – Empty)
Temp is 10 – 70 ohms (High – Low)

I used a multimeter and the engine temperature sender to measure the temp/resistance of water as it cooled. This was a janky setup for sure, but it seems to be super accurate so I cant really complain to be honest. With that data I also used a spreadsheet that utilised Steinhart equation.

Now credit where credits due a video by [Ovens Garage](https://www.youtube.com/watch?v=qwllQ3LI4qo) on YouTube helped be tons with this and was super helpful. My setup with the sender, multimeter and control temp gauge was all very similar.

I setup the fuel gauge as a linear change in resistance, unlike the variable relationship between temp/resistance. This is a pure guess as I haven’t done any exact measurements of the fuel sender, and couldn’t find any online. However I haven’t be stranded without fuel yet so it can’t be too far out.

I originally intended for this to be a temporary board that was just for testing purposes however it has been inside my car running fairly happy without hiccups for close to 6 months now. In saying that I do intend to further refine this design and continue adding to it, I also want to design and order some PCBs to make this look way more professional. I'm currently mucking around with EasyEDA which allows me to also seamlessly use JLCPCB for ordering once done.

{{< img src="images/gauge1.jpg" >}} {{< img src="images/gauge2.jpg" >}}{{< img src="images/gauge3.jpg" >}}{{< img src="images/gauge6.jpg" >}}

### Gauges Wishlist
    * Oil Temp
    * Clock
    * Add another temp probe
    * Thermo On/Off indicator. 

[Jump to the top!](##Specs:)