# LPnetlib/lp_blend

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_blend

 [Netlib LP problem blend: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 603

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

 for "has ranges".                                                           

                                                                             

 The optimal value is from MINOS version 5.3 (of Sept. 1988)                 

 running on a VAX with default options.                                      

                                                                             

                        PROBLEM SUMMARY TABLE                                

                                                                             

 Name       Rows   Cols   Nonzeros    Bytes  BR      Optimal Value           

 BLEND        75     83      521       3227       -3.0812149846E+01          

                                                                             

 Nick Gould supplied BLEND from the Harwell collection of LP test problems.  

                                                                             

 Concerning the problems he supplied, Nick Gould says that BLEND "is         

 a variant of the [oil refinery] problem in Murtagh's book (the              

 coefficients are different) which I understand John Reid obtained           

 from the people at NPL (Gill and Murray?); they were also the original      

 sources for the SC problems"                                                

                                                                             

 Added to Netlib on 6 April 1989                                             

                                                                             

![LPnetlib/lp_blend](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_blend.gif)
