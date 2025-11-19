---
title: Home
---

## Table of contents
1. [About me](#about_me)
2. [Contact and social media](#contact)
3. [Work/Research experience](#research_experience)
4. [Publications](#publications)
5. [Conferences](#conferences)
6. [Teaching](#teaching)
7. [Education](#education)

**Hi, I'm Alex. A plasma physicist. I use computer simulations to model plasma inside of [tokamaks](https://en.wikipedia.org/wiki/Tokamak).** I work for [Tokamak Energy]([https://www.gov.uk/government/organisations/uk-atomic-energy-authority](https://tokamakenergy.com/)) in Oxfordshire, UK. I am currently developing a code called [RT-GSFit](https://github.com/tokamak-energy/rtgsfit) for real-time control in [ST40](https://iopscience.iop.org/article/10.1088/1741-4326/ad6ba7/meta).

My research interests include:
* Tokamak magnetic equillibria.
* GPU programming for HPC.
* Fast particle physics.
* Gyrokinetics.
* Computational MHD.
* Solar physics.

<div class="split">
  <figure>
    <img src="https://aleksyprok.github.io/images/me_next_to_tokamak.jpg" alt="me_next_to_tokamak" width="370" height="462">
    <figcaption>
      <strong>Fig. 1</strong> Picture of me next to a tokamak at the <a href="https://ccfe.ukaea.uk/">UKAEA Culham Campus</a>.
    </figcaption>
  </figure>
  <figure>
    <img src="https://aleksyprok.github.io/images/aleksy_prok.jpg" alt="aleksy_prok" width="329" height="439">
    <figcaption>
      <strong>Fig. 2</strong> Picture of me at the St Andrews pier.
    </figcaption>
  </figure>
</div>

## Contact and social media<a name="contact"></a>

If you have any questions or suggestions, please feel free to email me at <aleksyprok@gmail.com>.
Here are links to my [LinkedIn](https://www.linkedin.com/in/alex-prokopyszyn-phd-25a450b3/), [Stack Exchange](https://stackexchange.com/users/12604491/peanutlex), [GitHub](https://github.com/aleksyprok) and [Google Scholar](https://scholar.google.com/citations?view_op=list_works&hl=en&user=KfrF2q8AAAAJ) accounts.

## Publications (as first author) <a name="publications"></a>

### Papers

* [Prokopyszyn, A. P. K., K. G. McClements, H. J. C. Oliver, M. Fitzgerald, D. A. Ryan, and G. Xia (2025, July). _Confinement of fusion alpha-particles and Alfvén eigenmode stability in STEP._ Nuclear Fusion 65, 086039.](https://iopscience.iop.org/article/10.1088/1741-4326/adf120/meta)
* [Prokopyszyn, A. P. K., A. N. Wright, and A. W. Hood (2021, June). _Line-tied boundary conditions can cause resonant absorption models to generate unphysically large boundary layers._ The Astrophysical Journal 914, 15.](https://doi.org/10.3847/1538-4357/abf65b)
* [Prokopyszyn, A. P. K. and A. W. Hood (2019, December). _Investigating the damping rate of phase-mixed Alfvén waves._ Astronomy & Astrophysics 632, A93.](https://www.aanda.org/articles/aa/abs/2019/12/aa36658-19/aa36658-19.html)
* [Prokopyszyn, A. P. K., A. W. Hood, and I. De Moortel (2019, April). _Phase mixing of nonlinear Alfvén waves_. Astronomy & Astrophysics 624, A90.](https://www.aanda.org/articles/aa/abs/2019/04/aa34939-18/aa34939-18.html)

### Thesis

* [Magnetohydrodynamic waves in the solar corona](https://research-repository.st-andrews.ac.uk/handle/10023/23436)

## Work/Research experience  <a name="research_experience"></a>

### Tokamak Energy, Plasma Physiscist - Equilibrium, Magnetics and MHD
April 2025 - Present

Developing [RT-GSFit](https://github.com/tokamak-energy/rtgsfit), a code which solves the [Grad-Shafranov](https://en.wikipedia.org/wiki/Grad%E2%80%93Shafranov_equation) equation in-real time for [ST40](https://iopscience.iop.org/article/10.1088/1741-4326/ad6ba7/meta).

### UK Atomic Energy Authority/STFC Rutherford Appleton Laboratory (Secondment), Advanced Computing Specialist
April 2024 - March 2025

Contributed fast-particle physics capabilities in the XGC code, a state-of-the-art gyrokinetic particle-in-cell simulation for exascale HPC architectures. XGC is developed at the Princeton Plasma Physics Laboratory and is primarily written in modern C++ with [Kokkos](https://kokkos.org/kokkos-core-wiki/) for performance portability. This work involved close collaboration with the XGC team and significantly deepened my expertise in large-scale fusion plasma simulation.

### UK Atomic Energy Authority, Fast Particle Modeller
September 2021 - March 2024

*	Helping to design a nuclear fusion reactor called [STEP (Spherical Tokamak for Energy Production)](https://ccfe.ukaea.uk/research/step/#:~:text=The%20Spherical%20Tokamak%20for%20Energy%20Production%20%28STEP%29%20is,which%20has%20been%20under%20development%20since%20the%201980s.), where the goal is to build a Nuclear Reactor which puts clean energy onto the national grid by 2040.
*	Using and developing a [CUDA-Fortan](https://developer.nvidia.com/cuda-fortran) monte-carlo code called the [Lorentz Orbit Code for Use in Stellerators and Tokamaks (LOCUST)](https://iopscience.iop.org/article/10.1088/1741-4326/ac108c/meta) to model particles in the reactor.
*	Implementing advanced statistical techniques to improve the accuracy of the code. For example, implementing a [KDE (Kernel Density Estimate)](https://en.wikipedia.org/wiki/Multivariate_kernel_density_estimation#:~:text=Kernel%20density%20estimation%20is%20a%20nonparametric%20technique%20for,introduced%20in%20the%20scientific%20literature%20for%20univariate%20da) method with a [leave-one-out cross-validation bandwidth selector](https://en.wikipedia.org/wiki/Cross-validation_(statistics)#Leave-one-out_cross-validation), to estimate the heat load distribution for the fast particles hitting hte walls of the reactor.


### University of St Andrews, Research fellow
March  2021 – September 2021

I helped develop a Fortran code called [Hexa](https://github.com/aleksyprok/Hexa_apkp) to extrapolate the [solar coronal](https://en.wikipedia.org/wiki/Stellar_corona) magnetic field from [magnetograms](https://en.wikipedia.org/wiki/Solar_magnetogram). I improved the accuracy of the code by allowing it fully utilise more data provided by the magnetograms. I helped improved the efficiency of the code by helping to parallelise it using [MPI](https://en.wikipedia.org/wiki/Message_Passing_Interface).

### University of St Andrews, PhD Mathematics
September 2017 – March 2021 (passed viva 2nd June 2021)

My PhD used computer simulations to model MHD waves in the solar corona, working with Prof Alan Hood, Prof Ineke De Moortel, Dr Andrew Wright and funded by STFC. The areas I worked in were:
*	Developing and exploiting a Fortran 90 code called [LaRe2D](https://github.com/Warwick-Plasma) to model plasma in the solar atmosphere. Researchers have been developing the code across several universities since 2001. I used a supercomputer at the university to run my simulations and analysed the data using python and IDL. The work involved bug fixing and simulating nonlinear waves which led to [my first published paper](https://www.aanda.org/articles/aa/abs/2019/04/aa34939-18/aa34939-18.html).
* Using analytical techniques to rule out a proposed coronal heating mechanism called phase mixing. This work led to my [second published paper](https://www.aanda.org/articles/aa/abs/2019/12/aa36658-19/aa36658-19.html).
*	Creating my own 3D codes to model resonant absorption. [The first code](https://github.com/aleksyprok/leapfrog_code) used a finite-difference technique. To improve the computational efficiency, I developed a [new code](https://github.com/aleksyprok/apkp_thesis/tree/main/Python/Chapter4/spectral_code) that uses a combination of finite-difference, spectral method, and method of line techniques. This work led to my [third paper](https://arxiv.org/abs/2104.10497), which is currently in preparation for publication.

## Conferences and seminars <a name="conferences"></a>

* February 12, 2025 - Fusion Computing Workshop, UKAEA Culham Campus, [Contributed Talk - XGC for Fusion Turbulence](https://aleksyprok.github.io/images/Fusion_Computing_Workshop_Talk_Feb_2025.pdf)
* December, 2024 - Fusion Computing Conference, UKAEA Culham Campus, [Poster - Fast Particle Physics in XGC](https://aleksyprok.github.io/images/Fusion_Computing_Conference_Poster_Dec_2024.pdf)
* September 17, 2024 - Fusion Computing Workshop, Daresbury, [Contributed Talk - XGC for Fusion Turbulence](https://aleksyprok.github.io/images/Fusion_Computing_Workshop_Talk_Sep_2024.pdf)
* October 20, 2023 - IAEA FEC, London, [Poster - Confinement of Fusion α-Particles and Alfvén
Eigenmode Stability in STEP](https://aleksyprok.github.io/images/IAEA_FEC_poster_2023.pdf)
* October/November 31-4, 2022 - ISTW, [Contributed Talk - STEP's steady-state α-particle losses](https://aleksyprok.github.io/images/ISTW_talk_2022.pdf) 
* April 22, 2021 - ESPOS, [virtual seminar](https://espos.stream/2021/04/22/Prokopyszyn/)
* April 7, 2021 - SMTG seminar series, St Andrews, [annual seminar.](https://aleksyprok.github.io/images/smtg_2021_seminar.pdf)
* April 20, 2020 - SMTG seminar series, St Andrews, [annual seminar.](https://aleksyprok.github.io/images/smtg_2020_seminar.pdf)
* June/July 30-4, 2019 - National astronomy meeting, Lancaster, [presented poster.](https://aleksyprok.github.io/images/NAM_poster_2019.pdf)
* June 10-14, 2019 - Coronal Loops Workshop, St Andrews, [contributed talk.](https://aleksyprok.github.io/images/LOOPS_talk_2019.pdf)
* April 14, 2019 - SMTG seminar series, St Andrews, [annual seminar.](https://aleksyprok.github.io/images/smtg_2019_seminar.pdf)
* September 9-14, 2018 - STFC Advanced summer school, Southampton.
* September 3-7, 2018 - BUKS Waves in the solar atmosphere, Tenerife, [contributed talk.](https://aleksyprok.github.io/images/buks_talk_2018.pdf)
* June 11-15, 2018 - Advanced topics in MHD, Udine, Italy.
* June 6, 2018 - SMTG seminar series, St Andrews, [annual seminar.](https://aleksyprok.github.io/images/smtg_seminar_2018.pdf)
* March 26-27, 2018 - UKMHD, St Andrews.
* January 2018 - RAS specialist discussion meeting, London.
* December 11-15, 2017 - Computational MHD workshop, Leeds.
* September 10-15, 2017 - STFC Introductory summer school, Newcastle.
* September 5, 2016 -  SUPA Cormack Astronomy Meeting, Edinburgh, [presented poster.](https://aleksyprok.github.io/images/cormack_meeting_poster_2017.pdf)

## Teaching <a name="teaching"></a>

Each semester of my PhD, I have assisted with the teaching in the maths department at St Andrews. My teaching has mainly involved supervising computer workshops. This is where the students are given computer assignments to work on, e.g. create a program to output the first n Pythagorean triples. My job is to answer questions and deal with any computer-related issues the students have. I have also taught tutorial classes, and this is where we discuss a problem sheet with a class of 10 students.

The classes I have taught are:
* September-December 2017, Computing in mathematics, Fortran 90 computer class
* January-April 2018, Vector calculus, tutorial class
* September-December 2018, Multivariate calculus, Python computer class
* January-April 2019, Mathematics, Maple computer class
* January-April 2019, Mathematical modelling, Python computer class
* September-December 2019, Computing in mathematics, Fortran 90 computer class
* January-April 2020, Pure and applied mathematics, Maple computer class
* September-December 2020, Multivariate calculus, Python computer class

## Education <a name="education"></a>

### Unviversity of St Andrews, BSc Mathematics (First Class)
September 2014 - May 2017
* Awarded First Class with a grade point average (GPA) of 18.5/20 (a minimum of grade 16 is required for a first)
* Honours Modules with grades (out of 20): 
   * Complex Analysis 18.1
   * Computing in Mathematics 17.5 
   * Differential Equations 19.3
   * Linear Mathematics 18.7
   * Dynamical Systems 17.8
   * Fractal Geometry 17.2
   * Solar Theory 19.3
   * Techniques of Applied Mathematics 18.4
   * Advanced Solar Theory 17.2
   * Asymptotic Methods 19.8
   * Linear and Nonlinear Waves 19.6
   * Numerical Analysis 17.8
   * Classical Mechanics 19.0
   * Fluid Dynamics 17.5
   * Theory of Electric and Magnetic Fields 19.3
   * Final year dissertation 19.8 
* Awards:
   * May 2017 – Duncan Prize (Applied Mathematics Senior Honours) for scoring the highest in fourth year applied modules.
   * May 2017 – Duncan Prize and Medal for the best final year Maths BSc dissertation.
   * May 2017 – Fourth level BSc Mathematics medal for the highest-scoring fourth year BSc maths student.
   * May 2016 – Awarded a Cormack scholarship for a summer research project.
   * May 2016 – Third Level BSc Mathematics medal for the highest-scoring third year BSc Maths student.
   * May 2015, 2016 & 2017 – Dean’s List award for students who average above 16.5/20 in all modules across the academic year.
