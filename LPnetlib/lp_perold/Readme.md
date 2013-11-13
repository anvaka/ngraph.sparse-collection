# LPnetlib/lp_perold

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_perold

 [Netlib LP problem perold: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 653

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

 PEROLD      626   1376     6026      47486  B    -9.3807580773E+03            

                                                                               

         BOUND-TYPE TABLE                                                      

 PEROLD     UP LO FX FR                                                        

                                                                               

 Nick Gould supplied PEROLD, from the Harwell collection of LP test problems.  

                                                                               

 Bob Bixby reports that the CPLEX solver (running on a Sparc station)          

 finds slightly different optimal values for some of the problems.             

 On a MIPS processor, MINOS version 5.3 (with crash and scaling of             

 December 1989) also finds different optimal values for some of the            

 problems.  The following table shows the values that differ from those        

 shown above.  (Whether CPLEX finds different values on the recently           

 added problems remains to be seen.)                                           

                                                                               

 Problem        CPLEX(Sparc)          MINOS(MIPS)                              

 PEROLD      -9.3807552782E+03    -9.3807553661E+03                            

                                                                               

 Concerning the problems he supplied, Nick Gould says that  PEROLD "is         

 another Pilot model (Pilot1)".                                                

                                                                               

 Added to Netlib on  6 April 1989                                              

                                                                               

![LPnetlib/lp_perold](http://www2.research.att.com/~yifanhu/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_perold.gif)