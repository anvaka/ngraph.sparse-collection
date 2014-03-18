# LPnetlib/lp_woodw

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_woodw

 [Netlib LP problem woodw: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 702

 date: 

 author: J. Tomlin

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

 WOODW      1099   8405    37478     240063        1.3044763331E+00        

                                                                           

 From John Tomlin.                                                         

 On the problems supplied by John Tomlin, MINOS 5.3 reports that about     

 10% to 57% of its steps are degenerate:                                   

      Name     Steps  Degen  Percent                                       

      WOODW     4147   1604   38.68                                        

                                                                           

 Added to Netlib on  27 June 1989                                          

                                                                           

![LPnetlib/lp_woodw](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_woodw.gif)
