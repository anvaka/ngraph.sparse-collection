# LPnetlib/lp_finnis

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_finnis

 [Netlib LP problem finnis: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 623

 date: 1989

 author: N. Gould

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

 for "has ranges".  The BOUND-TYPE TABLE below shows the bound types          

 present in those problems that have bounds.                                  

                                                                              

 The optimal value is from MINOS version 5.3 (of Sept. 1988)                  

 running on a VAX with default options.                                       

                                                                              

                        PROBLEM SUMMARY TABLE                                 

                                                                              

 Name       Rows   Cols   Nonzeros    Bytes  BR      Optimal Value            

 FINNIS      498    614     2714      23847  B     1.7279096547E+05           

                                                                              

         BOUND-TYPE TABLE                                                     

 FINNIS     UP LO FX                                                          

                                                                              

 When included in Netlib: Extra free rows omitted.                            

                                                                              

 Nick Gould supplied FINNIS from the Harwell collection of LP test problems.  

 Concerning the problems he supplied, Nick Gould says that FINNIS             

 "is from Mike Finnis at Harwell, a model for the selection of                

 alternative fuel types."                                                     

                                                                              

 Added to Netlib on  6 April 1989                                             

                                                                              

![LPnetlib/lp_finnis](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_finnis.gif)
