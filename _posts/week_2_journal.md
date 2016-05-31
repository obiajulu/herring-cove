---
title: Journal for Week 2
categories: journal entry
---

###Current plan for the week
1. (Monday) Cleaning up IVPTestSuite/adding new non stiff test
  + Add the PLEI test case from Hairer
  + Tidy up IVPTestSuite/src/ODE
  + Decide on which implicit solver to work on for JuliaCon
  + Blog post recapping the first week
2. (Tuesday) Run `pwl`'s PR on IVPTestSuite
  + Compare performance of solvers as represented in `pwl/ODE.jl` and `JuliaLang/ODE.jl`
  + Produce performance comparison graphs
3. (Tuesday/Wednesday-Saturday) Singly focus on implementing implicit and adaptive Adam Bashforth. 
  + Main Goal: A functional or near-functional version of the solver by week's close
  + If time permits, run through IVPTestSuite
4. (Saturday) A Blog post recapping the second week 

###Journal entry: #6
* Unforunately, a good portion of the day adn late night were spent debugging code I wrote
* I spent a far amount of time today trying to clean up ODE.jl in IVPTestSuite. I first tried scraping the metaprograming, however, I found that the metaprogramming was necessary in order to achieve the desired functionality of being able to `use IVPTestSuite`, and call a ODE solver instance with, for example, Solvers.ode23s. It seems removing the mesy metaprogramming may be repectifully sizable. 
* Another focus today was adding a new test case to IVPTestSuite. I choose the PLEI problem, described on pg 245 of Hairer. The problem is almost completely ready, I was have been going through the testing and debugging stage.
* I also attempted to run pwl's PR locally. I was not able to get the Winston package working properly to render graphs. I think I would like to see I can tomorrow.
* I ultimately decided to work on the adaptive and implicit Adam Bashforth solver, and will plan to present this one during JuliaCon. I figured it would be nice to finish with all things Adam Bashforth, having already code the fixed step explicit and implement methods. Also, I am confident I can get a near production ready version of AB out by JuliaCon, but I think it is best not to rush the RADAUIIA methods.
