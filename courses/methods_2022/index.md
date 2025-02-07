---
title: Macro Methods
layout: default
group: courses
---

# Biophysics 204B: Methods in Macromolecular Structure #


## Winter 2023 Syllabus ##

<img class="img-fluid mx-auto d-block" src="/static/img/courses/aeronab.jpg" style="height: 300px" alt="What is the next experiment?">

**Course Title:** Methods in Macromolecular Structure

**Course Format:** 6 hours of lecture/group work per week in class, substantial group work outside of class

**Location and Date/Hours:** Monday, Tuesday, Wednesday - 9AM-11AM in either Genentech Hall 227 or The Zoom where it happens!

[**Zoom Links**](https://ucsf.box.com/s/lr7d98dfy3hnopo0yszq82bgye09gj8x)

**Prerequisites:** All incoming first year BP and CCB graduate students are required to enroll in this course.

**Grading:** Letter grade

**Textbook:** None. Lab protocols and course materials will be available in class or online

**Instructors:** [John Gross](mailto:jdgross@cgl.ucsf.edu), [Aashish Manglik](mailto:Aashish.Manglik@ucsf.edu), [James Fraser](mailto:jfraser@fraserlab.com), KLIM!

**NMR guru:** [Alexandra Born](mailto:Alexandra.Born@ucsf.edu) (Manglik/Gross labs)


**TAs:**
- 

**Lecturers/Facilitators:**

James Fraser, Yifan Cheng, Aashish Manglik, Robert Stroud, John Gross, Alexandra Born, Tom Goddard, Cynthia Wolberger (JHU), Tanja Kortemme, Michael Grabe, James Lincoff


**Background:**

Fluency in multiple biophysical methods is often critical for answering mechanistic questions. Traditionally, students are exposed to the fundamentals of multiple techniques through lectures that cover the theory prior to exposure, for some, in analysis or data collection during lab rotations. However, this structure means that only students that rotate in specific labs gain hands-on-exposure, which could limit adventurous experiments in future years. To train the next generation of biophysicists at UCSF, we have decided to alter this traditional structure by creating  “Macromolecular Methods”, a class that places emphasis on playing with data. Based on our experiences designing the project-based class [Physical Underpinnings of Biological Systems, aka PUBS!](/courses/pubs/), which used deep sequencing to assay the function of a comprehensive set of point mutants to introduce principles of [high-throughput interrogation of biological functions](http://cdn.fraserlab.com/publications/2016_mavor.pdf), we have designed Macromolecular Methods to be a team-based class where students develop their own analysis of real data that, in non-pandemic years, they have collected.

**Course Description:**

This is a team-based class where students work in small groups develop their own analysis of real data. Statistical aspects of rigor and reproducibility in structural biology will be emphasized throughout lectures, journal club presentations, and hands-on activities. The website for the [2017](/methods_2017/),  [2018](/methods_2018/), [2019](/courses/methods_2019), and [2020](/courses/methods_2020) editions are available online.

*Ethics*: This course is more than a training experience; it is an active research project whose results will be published to the broader scientific community. The community must be able to understand our work, replicate it, and have confidence in its findings. We must therefore ensure the integrity of the information we disseminate. To do so, it is essential that students perform and document their experiments and analyses as faithfully as possible. Mistakes and oversights are normal and to be expected, but they must not be ignored, concealed, or disguised. In addition, to merit authorship, students must contribute to three aspects of the project: intellectual conception or interpretation of the methods or data, technical execution of the experiments and/or analyses, and documentation or dissemination of the results. We fully expect that by actively participating in the course and working toward the course objectives, all students will merit authorship.

*Respect*: This course is built around an open research project performed in teams. Successful completion of the course objectives will require that students work together effectively, so please respect the time and effort of your classmates and instructors. Moreover, as part of the research process, we will consider and debate a variety of ideas and approaches; however, we must not allow our position on a particular idea or argument to compromise our respect for its author. We therefore expect course participants to give all instructors and students, regardless of academic or personal background, their complete professional respect; anything less will not be tolerated.

*Accommodations for students with disabilities*: The Graduate Division embraces all students, including students with documented disabilities. UCSF is committed to providing all students equal access to all of its programs, services, and activities. Student Disability Services (SDS) is the campus office that works with students who have disabilities to determine and coordinate reasonable accommodations. Students who have, or think they may have, a disability are invited to contact SDS (StudentDisability@ucsf.edu); or 415-476-6595) for a confidential discussion and to review the process for requesting accommodations in classroom and clinical settings. More information is available online at http://sds.ucsf.edu. Accommodations are never retroactive; therefore students are encouraged to register with Student Disability Services (http://sds.ucsf.edu/) as soon as they begin their programs. UCSF encourages students to engage in support seeking behavior via all of the resources available through Student Life, for consistent support and access to their programs.

*Commitment to Diversity, Equity and Inclusion*: The course instructors and teaching assistants value the contributions, ideas and perspective of all students. It is our intent that students from diverse backgrounds be well-served by this course, that students' learning needs be addressed both in and out of class, and that the diversity that the students bring to this class be viewed as a resource, strength and benefit. It is our intent to present materials and activities that are respectful of diversity: gender identity, sexuality, disability, age, socioeconomic status, ethnicity, race, nationality, religion, and culture. However, we also acknowledge that many of the literature examples used in this course were authored in an environment that marginalized many groups. Integrating a diverse set of experiences is important for a more comprehensive understanding of science and we strive towards that goal. Although the instructors are committed to continuous improvement of our practices and our learning environment, we value input from students and your suggestions are encouraged and appreciated. Please let the course director or program leadership know ways to improve the effectiveness of the course for you personally, or for other students or student groups. (modeled after CCB and [Brown University's Diversity & Inclusion Syllabus Statements](https://www.brown.edu/sheridan/teaching-learning-resources/inclusive-teaching/statements))

## 2022 schedule

- TEAM ASSIGNMENTS

# Jan 9-11 - Class intro

## Monday January 9
- Welcome: structure of the class, zoom norms, teams and work-together recommendations, relationship to Macro mini-quals, final presentations for this class (AM)
- Why structural biology/Intro to Pchem (JG)
	- [Forces contributing to the conformational stability of proteins](https://faseb.onlinelibrary.wiley.com/doi/pdfdirect/10.1096/fasebj.10.1.8566551)
- [FFT 101](https://docs.google.com/presentation/d/13-tG0L3H70MA232TBcsvv3pkHsm3K2sVot4vDs9Xl5E/edit#slide=id.g10a62644d57_1_0) (JF)
	- Waves: amplitude/intensity, phase, frequency/wavelength (and in multiple dimensions: direction/index)
	- How to sum sine waves together: weights/amplitude - can make any periodic function!
	- Intuitively decomposing a complex function into sine waves (Fourier transform!)
	- [Resolution](https://bl831.als.lbl.gov/~jamesh/movies/resolution.mpeg): start thinking about 3D objects like an X-ray or EM map, building intuition of more waves measured giving higher resolution
	- Building up the MTZ (index = frequency and direction, amplitude/intensity, phase) and the concept of Nyquist frequency (why pixel size, changing values across pixels, and maximum resolution are related in EM)
	- [interactive website used in class for demo](http://www.jezzamon.com/fourier/) 
	- [sin wave grapher](https://www.desmos.com/calculator/w9jrdpvsmk)	
- [Aeronabs](https://science.sciencemag.org/content/early/2020/11/04/science.abe3255.long) and [What Aashish's miniquals might look like](http://cdn.fraserlab.com/courses/methods/20210215_MacroMethods.pdf) (AM)
	- Review: [Dynamic personalities of proteins](https://www.nature.com/articles/nature06522)


## Tuesday January 10
- Equity in structural biology - who is in the room, who has access to instrumentation, and who gets credit. (JF)
	- Before class, watch the first 14 minutes of [this video](https://www.mskcc.org/videos/kravis-wise-life-and-legacy-dr-rosalind-franklin-november-23-2020) for the history of Rosalind Franklin (stop when Cynthia Wolberger starts her lecture!)
	- Guest lecture on Rosalind Franklin's Scientific Legacy by [Prof. Cynthia Wolberger of Johns Hopkins](http://wolberger.med.jhmi.edu/)
- [Software instructions](https://docs.google.com/document/d/1bPXQNT0DGwznYD4zoPZnher61cUIHpD-bOYME-P0A2w/edit?usp=sharing)


## Wednesday January 11
- [ChimeraX tutorial by Tom Goddard](https://www.rbvi.ucsf.edu/chimerax/data/nanobody-feb2021/nanobody.html)



# Jan 17-24 - CryoEM - Lectures Yifan Cheng, Tutorials James Fraser

## Monday January 16
MLK DAY - HOLIDAY


## Tuesday January 17
### [Lecture 1 from Yifan Cheng](http://cdn.fraserlab.com/methods/yc2021_1.pdf)

## Wednesday January 18
### [Lecture 2 from Yifan Cheng](http://cdn.fraserlab.com/methods/yc2021_2.pdf)
### Tutorial 1:
 - Connecting to AWS - Thanks to Amazon Web Services Educate for computing credits
 - [cisTEM](https://cistem.org/) GUI and importing images (300kV, 2.7mm, 0.834 A/pix)
 - CTF (fit res better than 4A)
 - particle picking (150, 120, 2)
 - Symmetry (C1 vs. C3)
 - 2D classifications (box size 512)

## Monday January 23 
### Tutorial 2:
- Examining 2D classes
- Ab initio vs. starting 3D references (low pass filtered from [7KKK](https://www.rcsb.org/structure/7KKK))
- 3D map refinement

## Tuesday January 24
### [Lecture 3 from Yifan Cheng](http://cdn.fraserlab.com/methods/yc2021_3.pdf)
### Tutorial 3:
- Moving files off of AWS with scp
- 3D map classification
- [map sharpening](https://www.phenix-online.org/documentation/reference/auto_sharpen.html)
- [model refinement](https://www.phenix-online.org/documentation/reference/real_space_refine.html)
- Expectations for presentations: decision tree, summary of results, comparisons within decisions/to published, conformational analysis of Nb and confidence in that assessment.

## Reading on rigor and reproducibility in EM:
- [cisTEM paper](http://cdn.fraserlab.com/courses/methods/2018_grant.pdf)
- [FSC](https://en.wikipedia.org/wiki/Fourier_shell_correlation) and [early example in EM](http://cdn.fraserlab.com/courses/methods/1982_saxton.pdf)
- [half maps](http://cdn.fraserlab.com/courses/methods/2012_scheres.pdf) and [Optimal Determination of Particle Orientation, Absolute Hand, and Contrast Loss in Single-particle Electron Cryomicroscopy](http://cdn.fraserlab.com/courses/methods/2003_rosenthal.pdf)
- Other Model and Map validation tools (a lot of overlap with X-ray tools but a few examples that don't: [phenix.mtriage](https://www.phenix-online.org/documentation/reference/mtriage.html), [EMRinger](http://cdn.fraserlab.com/publications/2015_barad.pdf))

# Jan 25-Feb 6 - X-ray Crystallography - Lectures Bob Stroud, Tutorials Aashish Manglik

## Wednesday January 25
### [Lecture 1 from Bob Stroud](http://cdn.fraserlab.com/courses/2022_5dayclass_methods-2-1.pdf)
### [Tutorial 1 : What's the deal with the spots](https://docs.google.com/document/d/1nr4IIDVqjRautGy_CnyPHrNbdGwbgTnKjGznl6ZQPII/edit?usp=sharing)
- Examine diffraction data in adxv
- Use xia2 to process diffraction data
- Understand various metrics for data reduction
- What do we have at the end?

## Monday January 30
### Lecture 2 from Bob Stroud
### [Tutorial 2: Molecular Replacement](https://docs.google.com/document/d/1nr4IIDVqjRautGy_CnyPHrNbdGwbgTnKjGznl6ZQPII/edit#)
- Prepare a model from a different nanobody for phasing by molecular replacement
- Run Phaser, analyze output in Coot
- Use the mNb6 itself to solve the structure

## Tuesday January 31
### [Lecture 3 from Bob Stroud](http://cdn.fraserlab.com/courses/2022_5dayclass_methods-2-2.pdf)
### [Tutorial 3: Model refinement](https://docs.google.com/document/d/1nr4IIDVqjRautGy_CnyPHrNbdGwbgTnKjGznl6ZQPII/edit?usp=sharing)
- Manual model building in Coot
- Reciprocal space refinement in Phenix
- Rfree and what that means
- Molprobity to assess structure
- B factors and what they might mean
- Ensemble refinement
- [Coot tutorial video](https://www.youtube.com/watch?v=6RxvOFNu_rA)

## Wednesday Feb 1
### Lecture 4 from Bob Stroud

## Monday Feb 6
### Lecture 5 from Bob Stroud

## Reading on rigor and reproducibility in Crystallography:
- [R-free](http://cdn.fraserlab.com/courses/methods/1992_brunger.pdf)
- [MolProbity](http://cdn.fraserlab.com/courses/methods/2010_chen.pdf)
- [Data Challenges and synthetic data](http://cdn.fraserlab.com/courses/methods/2019_holton.pdf)
- [Protein crystallography for non‐crystallographers, or how to get the best (but not more) from published macromolecular structures](https://febs.onlinelibrary.wiley.com/doi/full/10.1111/j.1742-4658.2007.06178.x)

# Feb 7-15 - NMR - Lectures John Gross, Tutorials Alexandra Born

## Tuesday February 7
### [Lecture 1 from John Gross, Introduction to Multidimensional NMR](http://cdn.fraserlab.com/courses/Methods-NMR-2022-LECTURE1.pdf)
- demonstration of NMR data processing, John Gross
- [from FID to 2D](http://cdn.fraserlab.com/courses/2022_2DNMR_Processing_Tutorial.pdf) (Allie Born and John Gross)
- Supplemental reading: [How does an HSQC work?](http://cdn.fraserlab.com/courses/methods/HSQC-Guided-tour.pdf)

## Wednesday February 8
### [Lecture 2 from John Gross, Detecting Ligand and Protein Interactions by NMR](http://cdn.fraserlab.com/courses/Methods-NMR-2022-LECTURE2.pdf)
- process 15N HSQC and 13C HSQC data with teams (Allie Born and John Gross)


## Monday February 13
### [Lecture 3 from John Gross, Dynamic NMR -Hydrogen Deuterium Exchange (HDX) and intro to ms-usec dynamics](http://cdn.fraserlab.com/courses/Methods-NMR-2022-LECTURE3.pdf)
-  Overlay Nb6:Spike RBD complexes with Nb6 in CcpNMR, demo by Allie Born (Allie Born and John Gross)
-  [CcpNMR tutorial](http://cdn.fraserlab.com/courses/ccpNMR_Tutorial.pdf)
-  As an alternative to CcpNMR, you may  use [Sparky tutorial](http://cdn.fraserlab.com/courses/2022_Sparky_tutorial.pdf)
-  Supplemental reading: [CSP mapping by NMR when resonance asignments of the bound state are unknown](http://cdn.fraserlab.com/courses/methods/1996_farmer.pdf)

## Tuesday February 14
### [Lecture 4 from John Gross, Methods to quantify slow dynamics, ZZ-exchange and CPMG](http://cdn.fraserlab.com/courses/Methods-NMR-2022-LECTURE4.pdf)
- chemical shift perturbation plot versus primary sequence; mapping onto structure, [CSPs from Sparky Lists](http://cdn.fraserlab.com/courses/methods/Sparky_CSP.py)
- Overlay Nb6 with mNb6 15N and 13C HSQC data
- Cross-peak bookkeeping with teams (Allie Born and John Gross)

## Wednesday February 15
### Lecture 5 from John Gross, Measuring ns-ps dynamics in proteins
- process mNb6:RBD 15N and 13C HSQC spectra, overlay with mNb6. Cross-peak bookkeeping with teams (Allie Born and John Gross)

## Reading on rigor and reproducibility in NMR:
- [Tools for validating NMR structures](http://cdn.fraserlab.com/courses/methods/2014_vuister.pdf)
- [Q-scores](http://cdn.fraserlab.com/courses/methods/2004_clore.pdf)
- [Integrative modeling](http://cdn.fraserlab.com/courses/methods/2019_rout.pdf)



# Feb 21-22 - Computational approaches - Lectures Tanja Kortemme, James Lincoff, Michael Grabe

## Tuesday February 20 - PRESIDENTS DAY

## Tuesday February 21
### Lecture from James Lincoff and Michael Grabe, Molecular Dynamics simulations
- James Lincoff (Grabe lab) on simulations of AeroNabs
	- [Trajectory data](https://ucsf.box.com/s/xtx3jm8esx2c15zyz1z97jy0mlbbgswe)
	- [Pymol install instructions](https://pymolwiki.org/index.php/MAC_Install)

## Wednesday February 22
### Lecture from Tanja Kortemme, AlphaFold and RosettaFold
### Material from Tom Goddard
- [ChimeraX tutorial part II and Q/A by Tom Goddard](https://www.rbvi.ucsf.edu/chimerax/data/nanobody-feb2021/nanobody.html)
	- [Color by Chemical Shift Perturbations](https://www.rbvi.ucsf.edu/chimerax/data/nanobody-feb2021/chemshift.html)
	- [How to View Nanobody Molecular Dynamics in ChimeraX](https://www.rbvi.ucsf.edu/chimerax/data/nanobody-feb2021/nanobody_md.html)

# Final presentations - Feb 27
## Presenting as a team, in 15 minutes (we will stop you at 15 minutes sharp!) tell us about the scientist your team is named after, what you did, what you learned, and what is one more experiment you'd like to do! Followed by 5 minutes of questions. 

### Email your slides to Aashish Manglik by 8:30AM that morning!

### Presentation times [use individual zoom rooms](https://ucsf.box.com/s/lr7d98dfy3hnopo0yszq82bgye09gj8x)

* TEAMS:

# Supplemental material and tutorial videos

- [Getting started in CryoEM - Grant Jensen lectures](https://www.youtube.com/playlist?list=PL8_xPU5epJdctoHdQjpfHmd_z9WvGxK8-)
- [LMB EM Course](https://www2.mrc-lmb.cam.ac.uk/research/scientific-training/electron-microscopy/)
- [LMB X-ray Course](http://www2.mrc-lmb.cam.ac.uk/research/scientific-training/crystallography-course-2013/)
- [Thorn lab crystallography](https://www.youtube.com/channel/UCsEfbyZZD49WxUP5iJn6BkQ)
- [X-ray crystallography lecture - George Phillips](https://www.youtube.com/watch?v=OeOzLTNHWoM)
- [Crystallographic Symmetry - Eddie Snell](https://www.youtube.com/watch?v=sIgWFErZ3XU)
- [X-ray Diffraction Physics - Bob Blessing](https://www.youtube.com/watch?v=UJZF5yPNhIE)
- [X-ray diffraction resources](https://www.ccdc.cam.ac.uk/Community/educationalresources/database-of-educational-crystallographic-online-resources/resources-by-type/)
- [Protein Dynamics by NMR- Dorothee Kern](https://www.youtube.com/watch?v=fzM5V0bbybM)
- [Ligand binding and drug design-Dorothee Kern](https://www.youtube.com/watch?v=7MuBsYNrypg&t=659s)
- [NMR Theory Course , James Keeler](https://www.youtube.com/watch?v=nM7jQFhrvR0&index=1&list=PLE20foNk9J6L1dh9X27RaPiaul8_7wrAY)

