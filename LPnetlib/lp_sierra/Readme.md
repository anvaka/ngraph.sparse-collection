# LPnetlib/lp_sierra

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_sierra

 [Netlib LP problem sierra: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 690

 date: 

 author: R. Helgason, J. Kennington, P. Wong

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

 SIERRA     1228   2036     9252      76627  B     1.5394362184E+07        

                                                                           

         BOUND-TYPE TABLE                                                  

 SIERRA     UP                                                             

                                                                           

 Supplied by Bob Fourer.                                                   

 When included in Netlib: Explicit zeros omitted.                          

                                                                           

 Bob Bixby reports that the CPLEX solver (running on a Sparc station)      

 finds slightly different optimal values for some of the problems.         

 On a MIPS processor, MINOS version 5.3 (with crash and scaling of         

 December 1989) also finds different optimal values for some of the        

 problems.  The following table shows the values that differ from those    

 shown above.  (Whether CPLEX finds different values on the recently       

 added problems remains to be seen.)                                       

                                                                           

 Problem        CPLEX(Sparc)          MINOS(MIPS)                          

 SIERRA                            1.5394364186E+07                        

                                                                           

 Source: GFRD-PNC, SIERRA: R. Helgason, J. Kennington, and P. Wong,        

 "An Application of Network Programming for National Forest Planning",     

 Technical Report OR 81006, Dept. of Operations Research, Southern         

 Methodist University.                                                     

                                                                           

![LPnetlib/lp_sierra](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_sierra.gif)
