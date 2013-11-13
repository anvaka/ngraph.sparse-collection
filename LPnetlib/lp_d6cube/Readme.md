# LPnetlib/lp_d6cube

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_d6cube

 [Netlib LP problem d6cube: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 616

 date: 1993

 author: R. Hughes

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

 D6CUBE      416   6184    43888     167633  B     3.1549166667E+02        

                                                                           

         BOUND-TYPE TABLE                                                  

 D6CUBE        LO                                                          

                                                                           

 Supplied by Robert Hughes.                                                

                                                                           

 Of D6CUBE, Robert Hughes says, "Mike Anderson and I are working on the    

 problem of finding the minimum cardinality of triangulations of the       

 6-dimensional cube.  The optimal objective value of the problem I sent    

 you provides a lower bound for the cardinalities of all triangulations    

 which contain a certain simplex of volume 8/6! and which contains the     

 centroid of the 6-cube in its interior.  The linear programming           

 problem is not easily described."                                         

                                                                           

 Added to Netlib on 26 March 1993                                          

![LPnetlib/lp_d6cube](http://www2.research.att.com/~yifanhu/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_d6cube.gif)