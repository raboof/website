---
date        : 2020-05-05T00:00:00+01:00
lastmod     : 2020-05-05T00:00:00+01:00
draft       : false
title       : "Blog page rewrite test"
author      : "noor"

# Description overrides the automated summary of marked-up content
#  at the bottom of this file.
description : ""

# Identifying mnemonics, INTERNAL use only. Fill AT LEAST one identifying
# mnemonic, to refer to the project this blog is related to.
projects    : ["Bodgetheme"]

# External reference name (i.e. https://bodge.theme/blog/slug)
slug        : ""

# Identifying tags, searchable/visible to site visitors
tags        : []

# Identifying categories, searchable/visible to site visitors
categories  : []

# Blog icon
# For available icons, see: https://fontawesome.com
icon_name : fa-pencil
icon_pack : fa

# Default image related to this blog
image_src   : ""
image_alt   : ""
thumb_src   : ""
thumb_alt   : ""

# Author about box
about_show   : true
about_inline : true

# Photo gallery
gallery:
- album   : "images"
  exclude : true
  images  :
  - image   : "imagine.jpg"
    caption : "Imagine"
    exclude : false
  - image   : "people.jpg"
    caption : "People"
    exclude : false

# Write the content of this blog page below in markup language.
# An emoji cheat sheet can be found here:
#  https://www.webfx.com/tools/emoji-cheat-sheet/
---

# HackerHotel 2020 badge Sweatshop

Picture thread! We had a massive sweatshop yesterday because we messed up the design and had to rework 350 badges for
[@HotelHacker](https://twitter.com/HotelHacker). A story in a bunch of pictures. All shots by Noor, our newest [Badge Team](http://badge.team) member and proud owner of an actual camera!

{{< img src="images/photo01.jpg" alt="Sweatshop" iwidth="50%">}}

----

## next step

First step was cutting off 350 x 5 mosfets. Since we reversed the LEDs by accident, sinking to GND wouldn't work. We cut the mosfets, as this was doable without training and a lot faster than using hot air. Some traces were damaged (1% of the boards) but those were fixed easily!

{{< img src="images/photo02.jpg" alt="Sweatshop" width="33%">}}
{{< img src="images/photo03.jpg" alt="Sweatshop" width="33%">}}
{{< img src="images/photo04.jpg" alt="Sweatshop" width="33%">}}

----

## next step

A side project was prepping the battery boxes for next week. The leads were long and sharp, so we trimmed them down. People had to wear eye-protection, these pins were really on the attack! 700x 2 pins were cut. Bandaids for the  blisters from the cutting were handed out.

{{< img src="images/photo05.jpg" alt="Sweatshop" width="50%">}}
{{< img src="images/photo06.jpg" alt="Sweatshop" width="50%">}}

----

## next step

After the mosfets 'went', we also removed the diodes in both the boostconverter and the programmer. We used hot air because here the pads absolutely had to survive. Next up was soldering in a diode in the correct orientation.

{{< img src="images/photo07.jpg" alt="Sweatshop" width="50%">}}
{{< img src="images/photo08.jpg" alt="Sweatshop" width="50%">}}

----

## next step

With the programmer and boost circuit complete, we could now test all the boards for basic (minimum viable badge) functionality: CPU, serial comms. So we programmed all badges with a basic test code. This way we could filter out any duds so we wouldnt waste time on them.

{{< img src="images/photo09.jpg" alt="Sweatshop" width="50%">}}
{{< img src="images/photo10.jpg" alt="Sweatshop" width="50%">}}

----

## next step

All badges are now ready for the final modification and testing. But a lot more happened. Stickers were made for our official nickname: [Bodge Team](http://bodge.team). We had great emotional support on site (very important stuff on a stressful project) from BLAHÅJ and SMOLHÅJ!

{{< img src="images/photo12.jpg" alt="Sweatshop" width="33%">}}
{{< img src="images/photo11.jpg" alt="Sweatshop" width="33%">}}
{{< img src="images/photo13.jpg" alt="Sweatshop" width="33%">}}

----

## next step

Our volunteers are incredibly important to us. We always keep everyone hydrated and if needed: fed. This day we had a sponsor for the volunteer drinks and food! Thanks for that! (insert mandatory hackathon Pizza for work joke here, but we had GOOD pizza and a lot of fun!)

{{< img src="images/photo14.jpg" alt="Sweatshop" width="25%">}}
{{< img src="images/photo15.jpg" alt="Sweatshop" width="25%">}}
{{< img src="images/photo16.jpg" alt="Sweatshop" width="25%">}}
{{< img src="images/photo17.jpg" alt="Sweatshop" width="25%">}}

----

## next step

Another bit of prep: we needed 350x 5 2,5cm bits of laquered wire. So a few people made that happen.

{{< img src="images/photo18.jpg" alt="Sweatshop" width="50%">}}
{{< img src="images/photo19.jpg" alt="Sweatshop" width="50%">}}

----

## next step

Finally we were ready for the main event. We had to add in 5 bits of wire to replace the mosfets. Turns out the ATTiny is good enough to go a little bit out of spec and have the LEDs bright enough without a mosfet! On the sheet is the plan marked in the five red lines.

{{< img src="images/photo20.jpg" alt="Sweatshop" width="50%">}}

----

## next step

We first pre-tinned all the pads to make the job of soldering in the wire a lot faster. And then it was 'just' a matter of soldering in 350 x 5 = 1750 wires and cutting them.

{{< img src="images/photo21.jpg" alt="Sweatshop" width="50%">}}
{{< img src="images/photo22.jpg" alt="Sweatshop" width="50%">}}

----

## next step

Those went directly back to our testing station were we powered up at 1 volt (to test the boost circuit) and then we had a lot of happy badges!

{{< img src="images/photo23.jpg" alt="Sweatshop" width="50%">}}
{{< img src="images/photo24.jpg" alt="Sweatshop" width="50%">}}

----

## next step

Those that failed here (or earlier) were removed from the line and were visually inspected to get a diagnosis for what needed to be reworked. Nearly all were simple fixes, some needed more work. We don't have a lot of spares (10%) so we need to get as many working as we can!

{{< img src="images/photo25.jpg" alt="Sweatshop" width="50%">}}
{{< img src="images/photo26.jpg" alt="Sweatshop" width="50%">}}

----

## next step

We take the broken badges out of the process as early as we can to avoid getting sucked into repairing 1 difficult badge while we could easily fix 10 simple problems first. But we had time and energy to repair all but 4 badges.

{{< img src="images/photo27.jpg" alt="Sweatshop" iwidth="50%">}}

----

## next step

This was one of the more difficult ones. During cutting we ripped up the one trace we needed. Luckily scraping the via clean of soldermask provided enough contact surface for the bodge-wire to hold.

{{< img src="images/photo28.jpg" alt="Sweatshop" width="50%">}}
{{< img src="images/photo29.jpg" alt="Sweatshop" width="50%">}}

----

## next step

At the end of the day even the BLAHÅJ was beat. But we had done all badges except for four special cases which proved too difficult to fix now.

{{< img src="images/photo30.jpg" alt="Sweatshop" width="50%">}}
{{< img src="images/photo31.jpg" alt="Sweatshop" width="50%">}}

----

## next step

We ended up with 327 working units here and another 10 are at Tkkrlab for the 'purist edition' which have the LEDs flipped.

{{< img src="images/photo32.jpg" alt="Sweatshop" width="50%">}}
{{< img src="images/photo33.jpg" alt="Sweatshop" width="50%">}}

----

## next step

Key tips for badge sweatshops: make tasks as simple as they can be. One chore, not two or five. If you can break it in smaller steps, it will greatly improve the speed and quality of the work. Thats why we tin pads in one step, and attach wire in another.

Any fixes or steps in the process should be designed to be accomplishable by the greatest amount of team members on your crew. Not everyone does 0201 fixes daily, so design repairability/hackability into your board and design your bodges to be as easy as they can be.

Also take into account the amount of tools you have or can cheaply get. 4 heatguns are no match for 8 simple cutters to get rid of SOT23 mosfets. And heatguns can burn boards or parts, cutters do not, if you're careful. We only damaged 1% of the boards! All those were fixed!

{{< img src="images/photo34.jpg" alt="Sweatshop" iwidth="50%">}}

----

## next step

For this repair we came up with 4 different fixes for our problem. We chose this route because it was the easiest to do with the largest crew. It was not the BEST fix, or the prettiest fix, but the one which had the largest production volume per unit of time.

Another tip is having a LOT of 'fastfood trays'. They are absolutely invaluable to move stuff around, resupply, and to keep stuff tracked in progress.

{{< img src="images/photo35.jpg" alt="Sweatshop" width="33%">}}
{{< img src="images/photo36.jpg" alt="Sweatshop" width="33%">}}
{{< img src="images/photo37.jpg" alt="Sweatshop" width="33%">}}

----

## Closing off

To close off, here's another gratuitous BLAHÅJ picture! Please join us for another [@HotelHacker](https://twitter.com/HotelHacker) sweatshop saturday 8 of february!

{{< img src="images/photo38.jpg" alt="Sweatshop" iwidth="20%">}}
