# LPnetlib/lp_maros

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_maros

 [Netlib LP problem maros: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 642

 date: 1990

 author: I. Maros

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

 MAROS       847   1443    10006      65906  B    -5.8063743701E+04        

                                                                           

 From Istvan Maros.                                                        

 When included in Netlib: extra free rows omitted;                         

 cost coefficients negated.                                                

                                                                           

 Concerning the problems he submitted, Istvan Maros says that MAROS is     

 an industrial production/allocation model about which "the customer does  

 not want to reveal the exact meaning".                                    

                                                                           

 Added to Netlib on  15 June 1990                                          

![LPnetlib/lp_maros](http://www2.research.att.com/~yifanhu/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_maros.gif)