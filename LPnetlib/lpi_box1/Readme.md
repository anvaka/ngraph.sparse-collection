# LPnetlib/lpi_box1

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lpi_box1

 [Netlib LP problem box1: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 707

 date: 1992

 author: Z. You

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

                                                                             

 BOX1, EX72A, EX73A:  medium problems derived from research on using the     

 infeasibility version of viability analysis [Chinneck 1992] to analyze      

 petri net models.  All three problems are volatile, showing IISs of         

 widely differing size depending on the algorithm applied.  Contributor:     

 Zhengping You, Carleton University.                                         

                                                                             

 Name       Rows   Cols   Nonzeros Bounds      Notes                         

 box1        232    261      912   B            all cols are LO bounded      

                                                                             

 REFERENCES                                                                  

 ----------                                                                  

                                                                             

 J.W.  Chinneck (1992).  "Viability Analysis:  A Formulation Aid for All     

 Classes of Network Models", Naval Research Logistics, Vol.  39, pp.         

 531-543.                                                                    

                                                                             

 Added to Netlib on Sept. 19, 1993                                           

                                                                             

![LPnetlib/lpi_box1](http://www2.research.att.com/~yifanhu/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lpi_box1.gif)