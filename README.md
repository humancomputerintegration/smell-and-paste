# Smell & Paste toolkit

This is a repository for the Smell & Paste low-fidelity prototyping toolkit for olfactory experiences, which was presented at ACM CHI 2023. The device is in fact a 3-channel olfactory interface created by Jas Brooks and Pedro Lopes at the University of Chicago's [Human Computer Integration Lab](https://lab.plopes.org/).

[Paper](https://lab.plopes.org/published/2023-CHI-SmellPaste.pdf) | [CHI Talk Video](https://youtu.be/vVBhl13b0PE)

**Original Paper Abstract:** Low-fidelity prototyping is so foundational to Human-Computer Interaction, appearing in most early design phases. So, how do experts prototype olfactory experiences? We interviewed eight experts and found that _they do not_ because _no process supports this_. Thus, we engineered Smell & Paste, a low-fidelity prototyping toolkit. Designers assemble olfactory proofs-of-concept by pasting scratch-and-sniff stickers onto a paper tape. Then, they test the interaction by advancing the tape in our 3D-printed (or cardboard) cassette, which releases the smells via scratching. Our toolkit uses commodity materials; keeps iterations quick, approachable, and cheap; and circumvents electronics, programming, and chemical handling. We evaluated Smell & Paste in two studies. We found that the toolkit was approachable to people of any technical background and that novices and experts appropriated and extended the toolkit, making it personalized. Novices produced prototypes quickly, and experts were excited about the kit's technical affordances and integrating it into their practice.


## Repository Structure

* `3D_Print` contains all the files for the 3D printed version of the cassette. It contains both the parametric Fusion 360 file (`Cassette_3dPrinted_v69.f3d`) as well as all the STL files for printing off the bat (`\STL`). You will have to print two of the rollers (`SaP_Nylon_Roller.stl`) and spools (`SaP_Nylon_Spool.stl`) for one cassette.
* `Cardboard` contains all the files for the cardboard version of the cassette. It contains one version for lasercutters (`\Lasercut`) and one for manual cutting using an Xacto knife (`\Manual`). Please note that if you are lasercutting the cardboard version, you will have to leave the pieces to ventilate so that there is no residual burn odor (you can also adjust the settings to decrease burning as much as possible, and can also put the pieces with an ozone generator to speed up the deodorization). For manual cutting, print out the pages (PDF) and paste them on 2.5 mm cardboard. Then use an exacto knife to follow lines.

## Licensing & Citing
The cassette and documentation is released under the CC BY 4.0 License (just needs attribution to Jas Brooks and Pedro Lopes). We encourage people to remix this to their heart's content!

When using or building upon this device or dataset **in an academic publication**, please consider citing our paper:

Jas Brooks and Pedro Lopes. 2023. “Smell & Paste: Low-Fidelity Prototyping for Olfactory Experiences.” In Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems (CHI ’23). Association for Computing Machinery, New York, NY, USA. DOI:10.1145/3544548.3580680