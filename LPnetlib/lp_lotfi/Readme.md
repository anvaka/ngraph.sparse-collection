# LPnetlib/lp_lotfi

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_lotfi

 [Netlib LP problem lotfi: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 641

 date: 1989

 author: V. Lofti

 ed: D. Gay

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

 for "has ranges".                                                         

                                                                           

 The optimal value is from MINOS version 5.3 (of Sept. 1988)               

 running on a VAX with default options.                                    

                                                                           

                        PROBLEM SUMMARY TABLE                              

                                                                           

 Name       Rows   Cols   Nonzeros    Bytes  BR      Optimal Value         

 LOTFI       154    308     1086       6718       -2.5264706062E+01        

                                                                           

 From Vahid Lotfi.                                                         

 When included in Netlib: cost coefficients negated.                       

                                                                           

 LOTFI, says Vahid Lotfi, "involves audit staff scheduling.  This problem  

 is semi real world and we have used it in a study, the results of which   

 are to appear in Decision Sciences (Fall 1990).  The detailed             

 description of the problem is also in the paper.  The problem is          

 actually an MOLP with seven objectives, the first is maximization and     

 the other six are minimization.  The version that I am sending has the    

 aggregated objective (i.e., z1-z2-z3-z4-z5-z6-z7)."                       

                                                                           

 Added to Netlib on 27 June 1989                                           

![LPnetlib/lp_lotfi](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_lotfi.gif)
