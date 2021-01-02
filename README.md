[Official Discord](https://discord.gg/4sJCBx5) | [Official/Original project ](https://github.com/dekuNukem/duckyPad) | [ Frankenduck Sale ](Sale_pricing.md)

# Frankenduck
This project is a hardware rework of dekuNukem's duckypad project.
I liked the whole promise of the project, but the lack of protection for it in a more EDC style role was a bit off putting.
So because I had to read up into Altium for my job, I made it a goal for myself to redo the pcb.
I'm, in addition of that,  making a 3dprinted body for it to house everything.

## Original project

The original project where I took the schematic from (and probably gonna implement his very all-encompassing software package from):  
[dekuNukems duckypad project](https://github.com/dekuNukem/duckyPad) and
[the schematic in question ](https://github.com/dekuNukem/duckyPad/blob/master/pcb/lul.sch).  
You can view the original schematic easily with Eagle or by importing the file to [a site like this](https://www.altium.com/viewer/).

Also go take a look at the [official duckyPad Discord](https://discord.gg/4sJCBx5). 
The original designer and I are both active there.

## Software

The frankenduck is able to fully run the original software provided on the [original project ](https://github.com/dekuNukem/duckyPad).
But, There are currently some exceptions:
The frankenduck uses 2 extra leds on the 2 buttons on the side for the + and -.
It also has the plus on the bottom and minus on the top. 
For this PiTronica has made a [Different version of the software](https://github.com/PiTronica/FrankenDuck) that provides led support and a switched plus and minus button.

Due to a shortage on the STM32F072C8T6 I'm now using the STM32F078CBT6 it's completly compatible as far as is known.


## Overview

My goal with the hardware redesign is a more rigid and portable design while still being stylish and usable.
By implementing the top and bottom switch plate in acrylic I'm able to keep the pcb and amoled screen visible and protected.
The acrylic also gives a nice effect on the sides where the light can seep through through the side of the body.
And it turned out beautiful

<img src="/resources/frontled.jpg" width=75%>
<img src="/resources/backled.jpg" width=75%>
<img src="/resources/Caselight.jpg" width=75%>

## Pcb design

The schematic is exactly the same, other than the 2 layer selection switches now being actual mechanical switches.
I worked in Altium, so I still need to find a way to export the the project to easier accessible formats for other programs.

## Working product/ Sale

This keyboard now works flawlessly in its V1.1 form and the Visuals work out as I intended.

And with that I'm gonna sell some on them (EU only) to get some of the investment cost out of it.
If you want a complete one or a pcb hit me up on discord `headslash#8967` or ask for me in [official duckyPad discord](https://discord.gg/4sJCBx5).
I'm quite open to custom colors on the case and switch choice.

Pricewise I'm looking at around 60 Euro for a fully assembled and functional board.
Any variant or parts kit can also be aquired, just ask, I'm open to alot of stuff.


