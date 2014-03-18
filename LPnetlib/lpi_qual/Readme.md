# LPnetlib/lpi_qual

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lpi_qual

 [Netlib LP problem qual: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 727

 date: 1993

 author: T. Baker

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

                                                                             

 CHEMCOM, QUAL, REFINERY, REACTOR, VOL1:  medium size problems derived       

 from a petrochemical plant model.  Doctored to generate infeasibility       

 due to inability to meet volume or quality restrictions.  With the          

 exception of REACTOR, these are highly volatile problems, yielding IISs     

 of varying sizes when different IIS isolation algorithms are applied.       

 See Chinneck [1993] for further discussion.  Contributor:  Tom Baker,       

 Chesapeake Decision Sciences.                                               

                                                                             

 Name       Rows   Cols   Nonzeros Bounds      Notes                         

 qual        324    464     1714   B    FX                                   

                                                                             

 REFERENCES                                                                  

 ----------                                                                  

                                                                             

 J.W.  Chinneck (1993).  "Finding the Most Useful Subset of Constraints      

 for Analysis in an Infeasible Linear Program", technical report             

 SCE-93-07, Systems and Computer Engineering, Carleton University,           

 Ottawa, Canada.                                                             

                                                                             

![LPnetlib/lpi_qual](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lpi_qual.gif)
