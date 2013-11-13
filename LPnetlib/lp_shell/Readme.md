# LPnetlib/lp_shell

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_shell

 [Netlib LP problem shell: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 683

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

 This LP problem is the source of three sparse matrices in the Harwell/Boeing  

 sparse matrix collection: SHL_0, SHL_200, and SHL_400.  Those three matrices  

 are square, nonsingular basis matrices that occured during the solution of    

 SHELL.                                                                        

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

 for "has ranges".  The BOUND-TYPE TABLE below shows the bound types           

 present in those problems that have bounds.                                   

                                                                               

 The optimal value is from MINOS version 5.3 (of Sept. 1988)                   

 running on a VAX with default options.                                        

                                                                               

                        PROBLEM SUMMARY TABLE                                  

                                                                               

 Name       Rows   Cols   Nonzeros    Bytes  BR      Optimal Value             

 SHELL       537   1775     4900      38049  B     1.2088253460E+09            

                                                                               

         BOUND-TYPE TABLE                                                      

 SHELL      UP LO FX                                                           

                                                                               

 From John Reid.                                                               

                                                                               

![LPnetlib/lp_shell](http://www2.research.att.com/~yifanhu/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_shell.gif)