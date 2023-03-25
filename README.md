# Smell & Paste toolkit

This is a repository for the Smell & Paste low-fidelity prototyping toolkit for olfactory experiences, which was presented at ACM CHI 2023. The device is in fact a 3-channel olfactory interface created by [Jas Brooks](https://jasbrooks.net) and [Pedro Lopes](https://plopes.org) at the University of Chicago's [Human Computer Integration Lab](https://lab.plopes.org/).

[Paper](https://lab.plopes.org/published/2023-CHI-SmellPaste.pdf) | [CHI Talk Video](https://youtu.be/vVBhl13b0PE)

**Original Paper Abstract:** Low-fidelity prototyping is so foundational to Human-Computer Interaction, appearing in most early design phases. So, how do experts prototype olfactory experiences? We interviewed eight experts and found that _they do not_ because _no process supports this_. Thus, we engineered Smell & Paste, a low-fidelity prototyping toolkit. Designers assemble olfactory proofs-of-concept by pasting scratch-and-sniff stickers onto a paper tape. Then, they test the interaction by advancing the tape in our 3D-printed (or cardboard) cassette, which releases the smells via scratching. Our toolkit uses commodity materials; keeps iterations quick, approachable, and cheap; and circumvents electronics, programming, and chemical handling. We evaluated Smell & Paste in two studies. We found that the toolkit was approachable to people of any technical background and that novices and experts appropriated and extended the toolkit, making it personalized. Novices produced prototypes quickly, and experts were excited about the kit's technical affordances and integrating it into their practice.


## Putting together a kit

### 3D Printed version

`3D_Print` contains all the files for the 3D printed version of the cassette. It contains both the parametric Fusion 360 file (`Cassette_3dPrinted_v69.f3d`) as well as all the STL files for printing off the bat (`\STL`). You will have to print two of the rollers (`SaP_Nylon_Roller.stl`) and spools (`SaP_Nylon_Spool.stl`) for one cassette.

| Item                              | Sourcing            | Quantity | Example Source | Unit Cost  | Total Cost | Note                                                                                                     |
|-----------------------------------|---------------------|----------|----------------|------------|------------|----------------------------------------------------------------------------------------------------------|
| [Case (Bottom)](https://github.com/humancomputerintegration/smell-and-paste/blob/main/3D_Print/STL/SaP_Nylon_CaseBottom.stl)                     | 3D Print            | 1        |                | ~          | ~          |                                                                                                          |
| [Case (Top)](https://github.com/humancomputerintegration/smell-and-paste/blob/main/3D_Print/STL/SaP_Nylon_CaseTop.stl)                        | 3D Print            | 1        |                | ~          | ~          |                                                                                                          |
| [Scratch plate](https://github.com/humancomputerintegration/smell-and-paste/blob/main/3D_Print/STL/SaP_Nylon_ScratchPlate.stl)                     | 3D Print            | 1        |                | ~          | ~          |                                                                                                          |
| [Comb](https://github.com/humancomputerintegration/smell-and-paste/blob/main/3D_Print/STL/SaP_Nylon_Comb.stl)                              | 3D Print            | 1        |                | ~          | ~          |                                                                                                          |
| [Driver](https://github.com/humancomputerintegration/smell-and-paste/blob/main/3D_Print/STL/SaP_Nylon_Driver.stl)                            | 3D Print            | 1        |                | ~          | ~          |                                                                                                          |
| [Idle rollers](https://github.com/humancomputerintegration/smell-and-paste/blob/main/3D_Print/STL/SaP_Nylon_Roller.stl)                      | 3D Print            | 2        |                | ~          | ~          |                                                                                                          |
| [Spools](https://github.com/humancomputerintegration/smell-and-paste/blob/main/3D_Print/STL/SaP_Nylon_Spool.stl)                            | 3D Print            | 2        |                | ~          | ~          |                                                                                                          |
| Ream of Printer/Copy Paper (20lb) | At home or Purchase | 1        |                | $10.00     | $10.00     | Any kind of paper at home works!                                                                         |
| Tape (Splicing)                   | At home or Purchase | 1        | [Bari Zaki Studio](https://www.barizaki.com/shop/washi-tape-bookshelf)               | $6.00      | $6.00      | Preferably a flexible tape like painter's tape. We recommend Washi tape for how thin and flexible it is! |
| Tape (Spool)                      | At home or Purchase | 1        | [Home Depot](https://www.homedepot.com/p/Nashua-Tape-1-89-in-x-55-yd-394-General-Purpose-Duct-Tape-in-Silver-Sealer-1529728/100080300)               | $4.88      | $4.88      | Preferably a stickier tape to bind the paper tape to the spools. We recommend cheap duct tape.           |
| Super glue                        | At home or Purchase | 1        | [Home Depot](https://www.homedepot.com/p/Loctite-0-14-fl-oz-Ultra-Gel-Control-Super-Glue-1363589/202020461)               | $5.68      | $5.68      | To glue the hinges for the 3D printed cassette. Alternatively, you can use duct tape as a hinge.         |
| Velcro (hook-and-loop fasteners) with Sticky Backing	| At home or Purchase | 1  | [Home Depot](https://www.homedepot.com/p/VELCRO-Brand-3-1-2-in-x-3-4-in-Sticky-Back-Strips-4-Pack-90075/202261913) | $3.28 | $3.28 | For the comb. |
| Scratch-and-sniff stickers!       | At home or Purchase | ~        | Check out Dataset               | ~          | ~          |                                                                                                          |
|                                   |                     |          |                | **Total Cost** | $29.84     | To get things started!                                                                                   |

Please consider sourcing materials from local stores instead of Amazon, if you can! A lot of these items can be found in your home, hardware stores, general stores, and stationary stores.

All 3D printed parts do not need any support structures except for the spools (and - even then - could probably do fine without).

### Cardboard version

`Cardboard` contains all the files for the cardboard version of the cassette. It contains one version for lasercutters (`\Lasercut`) and one for manual cutting using an Xacto knife (`\Manual`). Please note that if you are lasercutting the cardboard version, you will have to leave the pieces to ventilate so that there is no residual burn odor (you can also adjust the settings to decrease burning as much as possible, and can also put the pieces with an ozone generator to speed up the deodorization). For manual cutting, print out the pages (PDF) and paste them on 2.5 mm cardboard. Then use an exacto knife to follow lines.

| Item                                                 | Sourcing            | Quantity | Example Source | Unit Cost  | Total Cost | Note                                                                                                     |
|------------------------------------------------------|---------------------|----------|----------------|------------|------------|----------------------------------------------------------------------------------------------------------|
| Cardboard (2.75mm)                                      | 3D Print            | 2        |                | ~          | ~          | Amazon packages are typically the perfect thickness for this.                                                                                                          |
| 1.6in Diameter Paper Tube (Spools)                   | 3D Print            | 2        |                | ~          | ~          | Cut the tube to have 2 tubes of length 4cm.                                                              |
| Ream of Printer/Copy Paper (20lb)                    | At home or Purchase | 1        |                | $10.00     | $10.00     | Any kind of paper at home works!                                                                         |
| Tape (Splicing)                   | At home or Purchase | 1        | [Bari Zaki Studio](https://www.barizaki.com/shop/washi-tape-bookshelf)               | $6.00      | $6.00      | Preferably a flexible tape like painter's tape. We recommend Washi tape for how thin and flexible it is! |
| Tape (Spool)                      | At home or Purchase | 1        | [Home Depot](https://www.homedepot.com/p/Nashua-Tape-1-89-in-x-55-yd-394-General-Purpose-Duct-Tape-in-Silver-Sealer-1529728/100080300)               | $4.88      | $4.88      | Preferably a stickier tape to bind the paper tape to the spools. We recommend cheap duct tape.           |
| Glue stick                                           | At home or Purchase | 1        | [Walgreens](https://www.walgreens.com/store/c/elmer's-disappearing-purple-school-glue-sticks/ID=prod17798-product)               | $3.79      | $3.79      | To glue cardboard pieces together. together.                                                                       |
| Velcro (hook-and-loop fasteners) with Sticky Backing | At home or Purchase | 1        | [Home Depot](https://www.homedepot.com/p/VELCRO-Brand-3-1-2-in-x-3-4-in-Sticky-Back-Strips-4-Pack-90075/202261913)               | $3.28      | $3.28      | For comb.                                                                                                |
| Scratch-and-sniff stickers!                          | At home or Purchase | ~        |                | ~          | ~          |                                                                                                          |
|                                                      |                     |          |                | Total Cost | $26.56     | To get things started!                                                                                   |

Please consider sourcing materials from local stores instead of Amazon, if you can! A lot of these items can be found in your home, hardware stores, general stores, and stationary stores.


### Sourcing scratch-and-sniff stickers

For our toolkit to be practical, you'll need scratch-and-sniff stickers. Commercial scratch-and-sniff stickers for children are incredibly accessible and cheap, including good and bad scents. We created a dataset of 800 scratch-and-sniff stickers from 22 brands to facilitate sticker selection. We manually extracted each sticker’s scent, dimensions, and price per cm2. The dataset includes 538 unique scents, depicting a wide variety at costs as low as 0.00035 USD per cm2. [You can find its CSV here!](https://github.com/humancomputerintegration/smell-and-paste/blob/main/CommercialSaS_v00.csv) (Jas recommends Just For Laughs' [Stink Factory stickers](https://www.thestinkfactory.com/) for their variety and price.)


## Licensing & Citing

The cassette and documentation is released under the CC BY 4.0 License (just needs attribution to Jas Brooks and Pedro Lopes). We encourage people to remix this to their heart's content!

When using or building upon this device or dataset **in an academic publication**, please consider citing our paper:

Jas Brooks and Pedro Lopes. 2023. “Smell & Paste: Low-Fidelity Prototyping for Olfactory Experiences.” In Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems (CHI ’23). Association for Computing Machinery, New York, NY, USA. DOI:10.1145/3544548.3580680