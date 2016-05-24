---
title: Journal for Week 1
date: 2016-23-05 
categories: journal entry
---

###Current plan for the week
1. (Monday/Tuesday) Adam Bashforth methods
  + Shift to open development and clean up code
  + Test with IVPTestSuite.jl
  + Add Documentation 
  + Run by Mauro and Jiaho to get feedback and see how to best fit Julia coding conventions, etc.
2. (Tuesday/Wednesday) Getting comfortable with IVPTestSuite.jl
  + Run with preexisting solvers
  +  Add a new stiff and non-stiff test case
3. (Wednesday/Thursday) Explore JuliaParallel
  +  Look at solvers there implemented
  +  Look at the tests in ts.jl  
4. (Thursday/Friday) Explore BenchmarkTools.jl as side project (if time permits)
  +  Run demos with the package
  +  Write a small summary of the pro's and con's of using it, as I see it, and run it by Mauro
  +  Reach out to @jrevels
5. (Friday/Saturday) Begin implementing Implicit solver RADUA
  +  Read relevant literature
  +  Come up with a overall sketch of the solver
  +  Start coding
6. (Saturday) A Blog post recapping the first week 

###Journal entry: #1
* Skype called with Mauro this morning to talk overall vision, and goals for today
* Worked on using Jiaho's edits to my demo to code Adam Bashforth. Tried to model code after solvers in ODE.jl. Was careful to only use Hairier et al (pg 357-358). (See https://github.com/obiajulu/ODE.jl/src/)
* Spent tonight of the day setting up Juno environment for development, and getting much more comfortable with Git and the Julia Dev Workflow
* Posted a question on slack asking other students and developers about what workflow they used
