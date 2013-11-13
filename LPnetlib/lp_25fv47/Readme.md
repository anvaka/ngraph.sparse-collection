# LPnetlib/lp_25fv47

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_25fv47

 [Netlib LP problem 25fv47: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 594

 date: 1978

 author: J. Reid

 ed: D. Gay

 fields: title name A b id aux kind date author ed notes

 aux: c lo hi z0

 kind: linear programming problem

 notes:

 A Netlib LP problem, in lp/data.  For more information                        

 send email to netlib@ornl.gov with the message:                               

                                                                               

 	 send index from lp                                                          

 	 send readme from lp/data                                                    

                                                                               

 ------------------------------------------------------------------------------

 This LP problem is the source of nine sparse matrices in the Harwell/Boeing   

 sparse matrix collection: BP_0, BP_200, BP_400, BP_600, BP_800, BP_1000,      

 BP_1200, BP_1400, and BP_1600.  Those nine matrices are square, nonsingular   

 basis matrices that occured during the solution of 25FV47 (also called BP     

 or BP1).                                                                      

 ------------------------------------------------------------------------------

                                                                               

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

 25FV47      822   1571    11127      70477        5.5018458883E+03            

                                                                               

 From John Reid.  Problem 25FV47 is sometimes called BP or BP1.                

                                                                               

 Bob Bixby reports that the CPLEX solver (running on a Sparc station)          

 finds slightly different optimal values for some of the problems.             

 On a MIPS processor, MINOS version 5.3 (with crash and scaling of             

 December 1989) also finds different optimal values for some of the            

 problems.  The following table shows the values that differ from those        

 shown above.  (Whether CPLEX finds different values on the recently           

 added problems remains to be seen.)                                           

                                                                               

 Problem        CPLEX(Sparc)          MINOS(MIPS)                              

 25FV47                            5.5018467791E+03                            

                                                                               

![LPnetlib/lp_25fv47](http://www2.research.att.com/~yifanhu/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_25fv47.gif)