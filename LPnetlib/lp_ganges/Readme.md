# LPnetlib/lp_ganges

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_ganges

 [Netlib LP problem ganges: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 628

 date: 

 author: L. Schrage

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

 GANGES     1310   1681     7021      60191  B    -1.0958636356E+05        

                                                                           

         BOUND-TYPE TABLE                                                  

 GANGES     UP LO                                                          

                                                                           

 Submitted by Linus Schrage.                                               

 When included in Netlib: Extra free rows omitted;                         

 Cost coefficients negated.                                                

                                                                           

 Bob Bixby reports that the CPLEX solver (running on a Sparc station)      

 finds slightly different optimal values for some of the problems.         

 On a MIPS processor, MINOS version 5.3 (with crash and scaling of         

 December 1989) also finds different optimal values for some of the        

 problems.  The following table shows the values that differ from those    

 shown above.  (Whether CPLEX finds different values on the recently       

 added problems remains to be seen.)                                       

                                                                           

 Problem        CPLEX(Sparc)          MINOS(MIPS)                          

 GANGES      -1.0958573613E+05    -1.0958577038E+05                        

![LPnetlib/lp_ganges](http://www2.research.att.com/~yifanhu/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_ganges.gif)