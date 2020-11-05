Hello there!  I'm Jed Gorman.
======

### Hi there 👋
\usepackage{amsmath}
Prequel memes aside, welcome to my Github.  This is the README for the Repository itself.  *whoa dude, that's so meta...* (__Do not encourage this behavior_)

  Skill wise, I have had an interesting journey, with many bends and unexpected *discontinuities* due to life circumstances.
I will share some of my story with you, what skills I have learned, and possible code.  Mind you, I started Uni in 2003, so
this meta-project *whoa, dude* will be as much forensic software archaeology through old HDDs and random sites on the web.

I will say this, I started out absolutely hating coding because of a horrible experiment on us in HS.  I still refuse to do, or even refer, to anything in JS.  I specifically thought I wouldn't have to do any coding.

__Cue sinister laughter__

Turns out AEs do a _SHIT TON_ of programming, especially with CFD.  I thus ended up taking a basic C Programming course to prepare myself for a class that I was taking over the summer.  It was called  "Modelling Methods in MMAE".  By this time, I'd picked up the dual Mech E degree because the programs were so similar...and AEs don't get PEs.

There, I learned the excellent habits that have continued to serve me for a decade and a half of programming in anything from Assembly on the 'LC-3', over Verilog, to Python and BASH scripting.  The C Programming class had an excellent teacher that taught us how to use Putty to log into the server.  There, we would type in a series of commands to compile our program.  This was my first experience with TLS/SSL, SSH, and the CLI.  The best thingI got out of that class were actually 2 things.

* I learned how to think through a programming problem.
  * I learned to first write out what I was supposed to do
  * I learned to take what idea, and break it into small, logical, manageable chunks.
  * I was then able to "translate" it into simple logical sentences: functions became paragraphs of statements
  * If I wanted clarity, I would go in one more layer and actually write out the code
  * Finally, came the typing.  And then the hair tearing of debugging.
  
  I also had an experience that taught me something profound.  We had both done a project where values had to continually be shuffled between different functions to be processed.  My code and hers, at first sight, seemed the same.  Same kinds of functions, same kinds of values being passed.  However, her entire code was pass by value.  Very safe, and very forgiving of mistakes.
  Mine, on the other hand, was ALL pass by reference.  There were NO values being exchanged, just pointers.  Very dangerous, but it was interesting.  Her code followed her own personality, in keeping everything safe and reversible.  Mine was _*Do it directly, do it well, and don't be afraid to take the path less taken*_ 

Most of the techniques taught were of two types: Matrix and Linear Algebra, and the linearization of Differential Equations into Difference Equations.

  I became proficient in techniques to turn matrices into easily solvable equations, such as SVD, Upper and Lower Triangular, etc...
As well, we learned how to approximate the differential equations.  Trapezoidal, Mid, Left, and Right values for Integrals, splines.
Runge-Kutta was an eye-opener.  It worked so well that we couldn't even see the error at the limits of accuracy.

  Later, I took a Statistics for Scientists and Engineers.  Our teacher made sure we understood what was going on, and the assumptions that were made, as well as the reasons for using different statistical tests and distributions.

  UCF is, in my opinion, amazing because they put a two course sequence into the track, with the first being the general principles of conducting experiments, calculating error, the use of basic instruments, soldering, welding *(with an arc welder!)*, Manometers.

  The second sequence of the course had one class for AE and one for ME. I took both, and I am amazingly grateful that I did.  I learned how to ask the kind of questions scientists asks.  I learned about the limits of measurements, but also statistical methods that took that data and told a story of what was happening.  I worked on the regular air tunnel for the AE class, with the basics of CFD used to make predictions, and at the end, the capstone project was running an entire experiment of our own, from question to report.

  The ME class in this sequence gave me the opportunity to work on a supersonic wind tunnel and setting up the imaging using Schlieren photogragphy.  That was a blast.  Literally.  For the two sequence HVAC classes I again had to use Matrices and Difference Equations to model Heat flow, solar heating, radiation, convection, and heat transfer using the resister model.

  Finally, I took a course that changed my life: Feedback Control.  The first part was just Matlab, Simulink, and Transfer Functions.  The second half applied that knowledge using Lego Mindstorms.  The final project was a PID controller, two lego train cars, the back one with the motor, and the front one with the sensor, connected with just two springs.  We had to program, build, and derive the parameters such that the front car's journey was smooth.

  Let me tell you, watching the back train spaz out and go back and forth, while watching the front car move so smoothly it looked like an amazing sine curve, was one for the records.  That's when I learned that I wanted to do Robotics and Mechatronics.

Cue several years of unmentionable experiences

  I start the Mechatronics program.  I skip the Mechanical tracks because I aced them at UCF, but I had to take the Circuits classes, Signal Analysis (combined with analog filters like bandpass, notch, low pass, high pass, order of the filter adding accuracy, but forcing more components into the circuit and increasing the order of the Diff EQ).  We also had a short section on digital signals and filters.  Naturally, we were programming ALL of this.  I took another Controls class, and our major project was a single DoF machine attached to a bar that we had to build, design, and derive a PID controller to track.  The TA even mentioned that we were the closest and smoothest project.

  For Junior design, we had to do a competition of two parts, with several caveats that made it much more difficult.  First, we were programming in LabView.  We'd never encountered this before, and we weren't being taught by our teachers.  Second was that the competition was two parts.  The first part was completely autonomous, and the machine had to balance on a see-saw mechanism until it was flat.  The second part was programming a video game controller to control the robots.  And yes, I will be posting those videos.

  Lastly, our Senior Design project was both ambitious, and humbling.  We chose Machine Learning: and paid the price for our hubris.  We tried the Coursera course and it made no sense.  Only two group members even got halfway, me and another.  Then we tried to look at simpler methods.  We chose Reinforcement Learning (Q-Learning specifically).
  In the second half of the course, we pivoted to fill out the project.  The final product was a kit to build, assemble, purchase electronics, and 3-D print the parts require to build a copy of our machine.  We posted it on Instructables under [Q_Crawler](https://www.instructables.com/Q-Learning-Crawler-Bot/), and the programs and software are in a repository by linked in my profile.
  
  After graduating, I decided to do the OMSCS program offered by Georgia Tech.  It is a full Masters in Computer Science, but the entire focus is on different kinds of Machine Learning.  They even had a track called "Computational Perception and Robotics."  I applied, got in, took a semester, and learned about Network Security and the problems of incomplete information and the basics of Location Awareness.  I was in an internship with McGill Associates, and was learning to use/program in AutoDesk REVIT and AutoCAD.  Unfortunately, my brother died, so I had to massively pivot.  Picked up a girlfriend, moved to Nashville, got a job as an automation technician.  THen I got another job as a Network Infrastructure Technician for the new Virgin Hotel.
  
  That didn't work out **(surprise, surprise!)** and I moved back to Asheville.  I set up what is essentially a combination of a keyboard, connected to a 5.1 surround sound system, with the data being sent to the computer for analyzation and conversion to sheet music, as well as a primitive waveform generation program (Mind you, I understand fully how the Fourier transform is a special case of the Laplace Transform, and am intimately familiar with things like Impulse Response with the Dirac Delta function, the Ramp Function, the Heaviside step functions, and their combinations, as well as the resulting waveforms).
  
  So I got a 32GB computer with an NVidia RTX 2080 TI graphics card for when school starts.
  
  - ⚡ Fun fact: ... I didn't use it for gaming for two months after building it.
  
  I found a book called "Grokking Deep Learning", and I cannot understate the effect that book has had on my understanding of deep learning, neural networks, and different architectures in general.  I set up Conda and Jupyter, wrestled with CUDA and CUdnn until they behaved, and went through the book.  I'm still confused by quite a bit of the material, but that's to be expected from an introductory book.  One single "sentence" of symbols crystallized my understanding of what I was building, and improved my ability to learn by leaps and bounds. That sentence was just the Neural Network, but in Mathematical Notation: 
Input times the first set of weights  $$\mathit(I{0})\mathbf(W{0})$$
The resulting hidden layer times the next weight matrix $$\mathif(I{1})\mathbf(W{0})$$
The three equations that really got me were: \[\mathif(I{1}) = \mathif(relu(I{0}\mathbf(W{0})))\]
\[\mathif(I{2} = I{1}\mathbf(W{1}))\]
### The End Result
\[\mathif(I{2} = relu(I{0}\mathbf(W{0}))\mathbf(W{1})

It hit me like years of education understood in an instant.  I knew how to do this.  I knew how this worked.  I knew why we had to introduce nonlinear activation functions, and why we used functions like sigmoid, (leaky)relu and tanh.

The rest of the repository involves the experienced TensorFlow tutorials (the beginner ones were too simple), and I hope to mess around with Magenta and music composition, DeepDream, and maybe trying to recreate the holographic interference/speckle pattern of those images.  I'm starting to learn PyTorch, but mostly I have been filling the gaps in my knowledge of Python with the book "Automate the Boring Things."  Sometimes I feel like skipping sections becaue it feels like a speak and spell, but I've taken many a class that involved coding and programming, and understand the value of making extra changes in line with the base concept to make these tutorials my own and show competence.

### Languages
* C
* Assembly (Concepts, Abstract, and LC-3 with a bit of x86)
* C++
* Python
* HTML (I know its not a programming language.  Oh well.)
* CSS
* PHP
* MySQL/MariaDB
* Swift
* LabView
* MATLAB
* Simulink
* SystemVerilog
* BASH scripting and automation
### Projects
* TensorFlow Examples
* Parallel Programming with C++
* Magenta
* Waveform Generator using models of RLC Circuits, Transfer Functions, and Root Locus/Pole Manipulation and Design
* Use of multiple VMs running various OSes (Three VirtualBox VMs, one running Debian 10, one running CentOS 7, and one running MacOS Catalina)
* Use of Docker Images, Containers, and Clusters to create my own website and portable ML system
* Using MicroPython and introducing ML to Edge cases such as the ESP32
* Attention in NLP
* Semantic translation and representation in word embeddings (maybe with fMRI scanns showing the human equivalent)
#### END GOAL

**The integration of edge and central ML units to build a unified picture of the surroundings.  Weather, soil, temperature, wind, traffic, particulate matter, gas levels, pressure, etc**

**Use these systems in the Habitat construction boom coming in two decades**
<!--
**jgorman3691/jgorman3691** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
