# LPnetlib/lpi_cplex2

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lpi_cplex2

 [Netlib LP problem cplex2: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 711

 date: 1993

 author: E. Klotz

 ed: J. Chinneck

 fields: title name A b id aux kind date author ed notes

 aux: c lo hi z0

 kind: linear programming problem

 notes:

 An infeasible Netlib LP problem, in lp/infeas.  For more information        

 send email to netlib@ornl.gov with the message:                             

                                                                             

 	send index from lp                                                         

 	send readme from lp/infeas                                                 

                                                                             

 The lp/infeas directory contains infeasible linear programming test problems

 collected by John W. Chinneck, Carleton Univ, Ontario Canada.  The following

 are relevant excerpts from lp/infeas/readme (by John W. Chinneck):          

                                                                             

 In the following, IIS stands for Irreducible Infeasible Subsystem, a set    

 of constraints which is itself infeasible, but becomes feasible when any    

 one member is removed.  Isolating an IIS from within the larger set of      

 constraints defining the model is one analysis approach.                    

                                                                             

 PROBLEM DESCRIPTION                                                         

 -------------------                                                         

                                                                             

 CPLEX1, CPLEX2:  medium and large problems respectively.  CPLEX1            

 referred to as CPLEX problem in Chinneck [1993], and is remarkably          

 non-volatile, showing a single small IIS regardless of the IIS algorithm    

 applied.  CPLEX2 is an almost-feasible problem. Contributor:  Ed Klotz,     

 CPLEX Optimization Inc.                                                     

                                                                             

 Name       Rows   Cols   Nonzeros Bounds      Notes                         

 cplex2      225    221     1059   B                                         

                                                                             

 REFERENCES                                                                  

 ----------                                                                  

                                                                             

 J.W.  Chinneck (1993).  "Finding the Most Useful Subset of Constraints      

 for Analysis in an Infeasible Linear Program", technical report             

 SCE-93-07, Systems and Computer Engineering, Carleton University,           

 Ottawa, Canada.                                                             

                                                                             

![LPnetlib/lpi_cplex2](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lpi_cplex2.gif)
