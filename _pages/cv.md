---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Here's a PDF version of my <a href="http://sumukhvaidya.github.io/files/231226_SumukhVaidyaResume_Work.pdf">CV</a>.

Education
======
* Ph.D. in Physics, Purdue University, 2025 (expected)
* M.Tech. in Engineering Physics (Specialization: Nanoscience), Indian Institute of Technology Bombay, 2020
* B.Tech. in Engineering Physics, Indian Institute of Technology Bombay, 2020

Skills
======
* Experimental Physics:
  * Laser systems
  * Confocal microscopy systems
  * Ion Implantation
  * Atomic Force Microscopy (AFM)
  * Scanning Electron Microscopy (SEM)
  * Focused Ion Beam (FIB) Microscopes
  * High Vacuum Systems
     
* Programming
  * Machine learning in Python (with TensorFlow and Pytorch)
  * LabView and Python-based instrument automation 
  * Optical system design with Zemax OpticStudio
  * MATLAB
  * COMSOL Multiphysics for physical system simulation
  * KLayout
  * Git
  * Latex

* Nanofabrication (All in the <a href="https://birck.research.purdue.edu/equipment/#nanofabrication">Birck Cleanroom Facility</a>):
  * Heidelberg Maskless Aligner for Photolithography
  * Electron beam metal evaporator for metal deposition
  * Spinner for spin-coating
  
Projects
======
A list of things I've worked on over the years

* While at Purdue
  * PhD Thesis related 
    <!---* Advisor: Prof Tongcang Li, Purdue Physics and Purdue ECE --->
    * Developed methods of sensing magnetic fields, paramagnetic ions in liquids, and performing nanoscale NMR experiments. 
    * Built a Confocal Microscopy system and integrated it with RF electronics to perform quantum sensing experiments.
    * Studied photoemitters in a variety of quantum materials such as Boron Nitride and Diamonds.
    * LabView, Matlab, and Python programming to control various instruments and analyze experimental data
    * Shifted a significant portion of the experimental code from LabView to Python for ease of use and licensing reasons 
    * Performed Comsol Multiphysics simulations for custom-designed waveguides to optimise the $S_{11}$ and $S_{12}$ parameters which were later fabricated in the cleanroom
    * Invented a way to perform simultaneous AFM and magneto scanning of samples using a Boron Nitride Nanotube on an AFM tip

  * Autoencoders for Denoising of Poisson Noise Limited Biological Images (Machine Learning Course Project)
    * Built a model for performing denoising of confocal microscope images which are acquired in the low-photon-number regime
    * Adapted an already existing model and tuned it for the Poisson Noise limit
    * Tested it on a standard dataset of images and showed increasing accuracy along with decreasing loss with training




   
* While at IIT Bombay
  * Master's Thesis related   
    <!---* Advisor: Prof Dinesh Kabra, Dept of Physics, IIT Bombay--->
    * Fabricated Large-Area, carbon-based Perovskite Solar Cells via screen printing methods. Obtained chemical handling training on a wet bench and glove box apparatus
    * Automated data acquisition for Time Delayed Collection Field Experiments using National Instruments VISA automation and control tools
    * Built a setup to perform Fourier plane imaging microscopy on samples of organic and perovskite thin films, to determine the emitter orientation in the films, enabling the engineering of better devices
    * Simulated Fourier plane emission profiles of thin film emitters under laser excitation and successfully determined the emitter orientations in the films
    * Simulated in MATLAB the outcoupling efficiency and delayed emission profiles of LEDs based on molecular semiconductors to improve emission characteristics of devices via interfacial engineering
    * Built the Research Group <a href="http://home.phy.iitb.ac.in/~dkabra/">website</a> using Jekyll. 
      
  * Gesture Recognition with Arduino (Course Project)
    <!---* Prof. Pradeep Sarin, Department of Physics, IIT Bombay --->
    * Built a 3-axis setup to recognize 6 hand gestures and control music playback with a Python backend
    * Used 3 ultrasonic sensors to take input by Arduino Uno Board, recognize 6 hand gestures & send it to python program to pause/play, previous/next, & volume up/down music playback
    * Generated data set of 540 unique hand gestures to enable high recognition accuracy of the gestures
      
  * An n-body simulation on Altera DE0-Nano FPGA (Course Project)
    <!---* Prof. Pradeep Sarin, Department of Physics, IIT Bombay --->
    * Made a functional 8-body simulation on Altera FPGA board with output visualised on a VGA monitor
    * Incorporated inter-particle and boundary-particle collisions to observe the time evolution of the system
    * Constructed the required circuit board to interface the FPGA with VGA and enable communication
      
  * Chaos Based Random Numbers (Course Project)
    <!---* Prof. Amitabha Nandi, Department of Physics, IIT Bombay --->
    * As part of group studied and used properties of non-linear maps and chaotic systems to generate and test for pseudo-random numbers
    * Wrote python programs to implement the random number generators, and used the Dieharder suite of tests to verify randomness in generated sets. The sequences were found to pass Dieharder tests
  
Work experience
======
* Dec '17: Visiting Student Researcher (<a href="https://wiki.kek.jp/pages/viewpage.action?pageId=358613286">Link</a>)
  * Advisor: Prof. Hiroyuki Noumi, RCNP, Osaka University, Japan
  * Title: Noise reduction for Central Drift Chamber.
  * Implemented noise reduction measures in signal acquisition for cosmic ray tracking in drift chamber
  * Used c++ & Root scripts to visualise data & see channel response for detection of incoming particles
  * Characterised chamber response as function of gas flow rate & voltage to find best detection conditions
  * Calculated efficiency of the different detection channel layers in the Drift Chamber
  * Worked on c++ and Root scripts for tracking of individual particles to find real time trajectories

* May '17: Visiting Student Researcher (<a href="https://wiki.kek.jp/pages/viewpage.action?pageId=358613286">Link</a>)
  * Advisor: Prof. Tsutomu Mibe, g-2/EDM Collaboration, KEK, Tsukuba, Japan
  * Title: Test of a muon beam counter
  * Received a letter of recommendation for applying to JPARC Asia Summer Student Program
  * Studied properties, output characteristics, effect of magnetic fields on Photomultiplier Tubes (PMTs)
  * Built a testing circuit testing PMTs as Muon Counters
  * Wrote a report detailing the experiment and findings regarding the effect of magnetic fields on PMTs
  



Publications
======
  Check out my publications in the Publications tab above.
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* May '21 - Apr '22: Webmaster for the <a href="https://www.physics.purdue.edu/pgsa/"> Purdue Physics Graduate Student Association (PGSA)</a>
  * Maintained the PGSA website by adding details of new events and relevant information

* May '19 - Apr '20: Head of the Department Academic Mentor Program, IIT Bombay
  * DAMP assigns an academic mentor to sophomores to assist them with their academic programs and provide information 
  * Led a 3-tiered team of 16 Coordinators and 215 Mentors overseeing 12 UG departments, catering to 1000+ sophomores
  * Instituted DAMP in Departments of Mathematics and Environmental Sc. to cater to 40 sophomores
  * Implemented the revamped Academic Rehab Policy to setup a support ecosystem for 130+ students
  * Organized targeted mentor training by Tata Institute of Social Sciences
  * Organised Technical Education Quality Improvement Program (TEQIP) workshops for 200+ faculty at various universities in India
  * Handpicked 12 mentors from 22 applicants as the acting DAMP head of 3 newly inducted departments
 
* Mar '18 - Mar '19: Institute Student Mentor
  * The <a href="https://smp.gymkhana.iitb.ac.in/"> Institute Student Mentorship Program</a> provides a Senior mentor to freshmen at IIT Bombay, helping them adjust to university life
  * Helped guide 10 freshmen in life at IITB
  * Was selected among 80 mentors from a pool of 300+ applicants
 
Academic Achievements
======
* 2015: All India Rank of 1053 in JEE Advanced
  * Out of 150,000 candidates appeared
* 2015: All India Rank of 1296 in JEE Mains
  * Out of 1.35 million candidates appeared
* 2014: 91.8% in 12th Board Examination
  * Central Board of Secondary Education, New Delhi, India
* 2014: Selected for Level II of the Indian National Chemistry Olympiad (InChO)
  * Among the Top 1% of students appeared
* 2014: 99.3875 Percentile in Problem Solving Assessment Examination
  * Conducted by Central Board of Secondary Education, New Delhi
