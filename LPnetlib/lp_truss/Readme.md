# LPnetlib/lp_truss

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_truss

 [Netlib LP problem truss: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 698

 date: 1990

 author: M. Ferris

 ed: D. Gay

 fields: title name A b id aux kind date author ed notes

 aux: c lo hi z0

 kind: linear programming problem

 notes:

 A Netlib LP problem, from a generator in lp/data.  For more information       

 send email to netlib@ornl.gov with the message:                               

                                                                               

 	 send index from lp                                                          

 	 send readme from lp/data                                                    

                                                                               

 This copy of TRUSS was created by the TRUSS generator program,                

 on an Sun UltraSparc, on May 15, 1997.                                        

                                                                               

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

 TRUSS      1001   8806    36642 (see NOTES)       4.5881584719E+05            

                                                                               

 Source:  At the request of Olvi Mangasarian, Rudy Setiono supplied the        

 generator and description (both written by Michael Ferris) and data for TRUSS.

                                                                               

 Requesting TRUSS will get you a bundle of Fortran source and data for         

 generating an MPS file for TRUSS, a problem of minimizing the weight          

 of a certain structure.  The bundle also includes a description of the        

 problem.                                                                      

                                                                               

 Added to Netlib on  26 Feb. 1990                                              

                                                                               

![LPnetlib/lp_truss](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_truss.gif)
