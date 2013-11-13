# LPnetlib/lpi_forest6

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lpi_forest6

 [Netlib LP problem forest6: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 714

 date: 1993

 author: H. Greenberg

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

                                                                             

 FOREST6, WOODINFE:  very small problems derived from network-based          

 forestry models.  The IIS in FOREST6 includes most of the rows.             

 WOODINFE is the example problem discussed in detail in Greenberg [1993],    

 and has a very small IIS.  Contributor:  H.J.  Greenberg, University of     

 Colorado at Denver.                                                         

                                                                             

 Name       Rows   Cols   Nonzeros Bounds      Notes                         

 forest6      67     95      270   B                                         

                                                                             

                                                                             

 REFERENCES                                                                  

 ----------                                                                  

                                                                             

 H.J.  Greenberg (1993).  "A Computer-Assisted Analysis System for           

 Mathematical Programming Models and Solutions:  A User's Guide for          

 ANALYZE", Kluwer Academic Publishers, Boston.                               

                                                                             

![LPnetlib/lpi_forest6](http://www2.research.att.com/~yifanhu/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lpi_forest6.gif)