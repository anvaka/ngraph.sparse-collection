# LPnetlib/lp_pilotnov

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_pilotnov

 [Netlib LP problem pilotnov: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 659

 date: 1989

 author: Stanford

 ed: R. Fourer

 fields: title name A b id aux kind date author ed notes

 aux: c lo hi z0

 kind: linear programming problem

 notes:

 A Netlib LP problem, in lp/data.  For more information                    

 send email to netlib@ornl.gov with the message:                           

                                                                           

 	 send index from lp                                                      

 	 send readme from lp/data                                                

                                                                           

 The following are relevant excerpts from lp/data/readme (by David M. Gay):

                                                                           

 The column and nonzero counts in the PROBLEM SUMMARY TABLE below exclude  

 slack and surplus columns and the right-hand side vector, but include     

 the cost row.  We have omitted other free rows and all but the first      

 right-hand side vector, as noted below.  The byte count is for the        

 MPS compressed file; it includes a newline character at the end of each   

 line.  These files start with a blank initial line intended to prevent    

 mail programs from discarding any of the data.  The BR column indicates   

 whether a problem has bounds or ranges:  B stands for "has bounds", R     

 for "has ranges".  The BOUND-TYPE TABLE below shows the bound types       

 present in those problems that have bounds.                               

                                                                           

 The optimal value is from MINOS version 5.3 (of Sept. 1988)               

 running on a VAX with default options.                                    

                                                                           

                        PROBLEM SUMMARY TABLE                              

                                                                           

 Name       Rows   Cols   Nonzeros    Bytes  BR      Optimal Value         

 PILOTNOV    976   2172    13129      89779  B    -4.4972761882E+03        

                                                                           

         BOUND-TYPE TABLE                                                  

 PILOTNOV   UP    FX                                                       

                                                                           

 Supplied by Bob Fourer.                                                   

 When included in Netlib: Cost coefficients negated.                       

 Prior to 29 April 1987, the lp/data/readme file gave the optimal value    

 from maximizing rather than minimizing PILOTNOV.                          

                                                                           

 Source for PILOT.JA, PILOT.WE, PILOT4, PILOTNOV: Systems Optimization     

 Laboratory, Stanford University.                                          

                                                                           

![LPnetlib/lp_pilotnov](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_pilotnov.gif)
