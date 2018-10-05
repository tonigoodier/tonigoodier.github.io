---
layout: post
title: 3D Printing in the Donnelly lab
---

How useful can 3D printing be in a lab setting? Here's what I've found

# This is very much still a draft. If you're looking at this and I haven't sent you the link, please ignore errors. If I have sent you the link, and this sentence is here, it's becuase I'm asking you to proof it, Toni :)

# 3D Printing?

I first started off with 3D printing (3DP) a few years ago with the Anet A8 (A8). The A8 cheap build-it-yourself type kit, which does the job of 3D printing objects, albeit not at the greatest resolution straight out of the box. 

I have spent numerous hours upgrading, tweaking, fixing and generally tinkering with the A8 and now have it in a condition where is reliable produces prints analogous to the commercially available and professionally calibrated 3D printers, specifically, the Original Prusa i3 MK2 which the A8 is a clone of.

<p align="center">
  <img src="/images/prusa-a8.jpg" alt="prusa-a8"/>
</p>

**Left:** Prusa MK2. **Right:** Anet A8.

The most common question I get when people find out I have a 3D printer is either **how much did it cost?** or **what do you use 3DP for?**

To answer the **how much?** question I'm digging deep to remember, but it was roughly ~£120, and now checking GearBest.com the current price (on 04/10/2018) is £108, so £120 seems about right. 

The **why** question is a bit trickier to directly answer. But generally, I enjoy tinkering with things and building things that I need and 3DP is a great technology for getting very specific, precise and intricate parts for a built project. I had found myself saying **I could 3D print that** long before deciding to buy one. But, the final time was when I was putting my tool wall back together after moving, and deciding that printing dedicated tool holders would extremely useful for organising small parts and hand tools. 

So, after searching for a long time, I decided on the A8 (a printer which I do not recommend buying, for what it's worth), I ordered it, it arrived, I assembled it and began printing. Now, after _many_ hours of print-time, repair-time, upgrading-time,  and finding tiny screws that I dropped onto carpet time, I'm starting to explore more complex areas of 3DP technologies. 

# Printing in the lab

I had seen that some people on [Thingiverse](http://thingiverse.com) had designed custom items for specific needs within their lab, ranging from bespoke Eppendorf tube holders, centrifuge tube adapters, rocker trays, etc. However, I never really thought of suggesting we try and use 3DP in our lab, as I didn't think there was a need for it. That was until one day, [Dr Arjen Van 'T Hof](https://www.lstmed.ac.uk/about/people) mentioned that he had been looking into 3DP as a method for maximising storage space in the BioBank that the Donnelly lab manages. After demo-ing my printer for a week, the Donnelly group ordered it's very own printer.

<p align="center">
  <img src="/images/donnelly-printer.JPG" alt="donnelly-printer"/>
</p>

# Tube Storage

## -80<sup>o</sup>C BioBank Tube Storage
For some context on this, a typical 10x10 storage box for Eppendorf boxes are designed for 1.5ml tubes. This means that when you have 0.5 ml tubes stored in these boxes, they are more difficult to remove and liable to being bounced from their place and could cause tube mix-up. Dr Van 'T Hof had the idea of design custom tube storage boxes that still retained the outer format of the traditional 10x10 boxes, but which had more appropriate dividers to accommodate the smaller tubes. After some tweaking and experimenting, Dr Van 'T Hof had designed the model for the tube box and printing them to fulfil the BioBanks storage needs.

insert pic here

## -20<sup>o</sup>C Pre-PCR Primer Tube Storage

Additionally, aliquots of qPCR primers which need to be stored in separate boxes, quickly fill freezer space in the PCR-prep room. At ony one time, a primer pair has ~15 aliiquots, so we design a set of boxes to efficiently hold those 15 tubes, to maximise the freezer storage space. We also added uniwue labels to both parts of the box to prevent mix up between sample boxes. 

<p align="center">
  <img src="/images/pcr-tube-box.jpg" alt="smaller-tube-boxes"/>
</p>

## Gel Combs

Dr Van 'T Hof also mentioned an idea for printing a gel electrophoresis casting comb that has 1 additional tooth than usual. This is because typical combs have multiples of 8 teeth, meaning that you are unable to do multiple complete rows of 8 (relevant because of PCR tray layout) and have a ladder lane. I initially intended to make my own 3D model for this, but why reinvent the wheel? A quick search on Thingiverse revealed that [Shyam Bhakta](https://www.thingiverse.com/shyambhakta/about) has already designed a parametric version of the electrophoresis gel combs. We customised the design to fit our needs, added a label, and began printing. 

<p align="center">
  <img src="/images/3dp-gel-comb.jpg" alt="3DP-gel-comb"/>
</p>

## Ice Block for SDS-PAGE Tanks

[Dr Lee Haines](https://www.lstmed.ac.uk/about/people/dr-lee-haines) had heard about the 3DP that was going on and asked whether it could solve the problem of replacing parts no longer available from the manufacturer or is available only in limited supply and as a result, unreasonably priced. The SDS-PAGE system in the lab uses an ice block to keep the buffer cool, whilst the experiment is running. The ice block is an irregularly shaped plastic 'bowl' which is filled with water and put in the freezer. The frozen block is then used for an experiment run and then refrozen. By now, Dr Van 'T Hof is quite adept with CAD and pulled together the 3D model for this part and we got began printing it. The first version was a success (with the exception of the colour choice, we later found out)

insert pic here 

## Miscellaneous Items

Hopefully, by now I've convinced you that 3DP has some useful applications in a lab setting when you want to either design a bespoke item or replace parts that are difficult or expensive to acquire. In addition to these, there are also small, more miscellaneous yet still handy items that have been printed around the lab. Below are some pictures.

### Small Parts Storage in a 50ml tube

Design by [Namehere](https://www.thingiverse.com/)

<p align="center">
  <img src="/images/3dp-part-storage-open.jpg" alt="£DP-gel-comb"/>
</p>

### Scalpel Handle

### Micropestle Wash Bucket

## Current 3DP Projects

### Long Print Projects 
At the moment I'm working to complete [AKSHAY_D21's](https://www.thingiverse.com/thing:2948680) 3D printable laboratory rocker. This is more of a personal project so I can play around with the Arduino framework, with the added benefit that the end product actually has a use. 

### Design Projects 
Dr Van 'T hof and I are working to design .STL models of the WHO Insecticide Susceptibility Bioassay tube systems, to help replace broken parts in the insectaries and keep as many tube kits in operation as possible. This is pushing the limits of my CAD skills, but with the help Dr Van 'T Hof, who has recently figured out thread creation, we should be able to complete this project. I intend to write a separate blog post about this in the near future when 
