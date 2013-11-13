# LPnetlib/lp_ship08s

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_ship08s

 [Netlib LP problem ship08s: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 687

 date: 

 author: R. Fourer

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

 for "has ranges".                                                         

                                                                           

 The optimal value is from MINOS version 5.3 (of Sept. 1988)               

 running on a VAX with default options.                                    

                                                                           

                        PROBLEM SUMMARY TABLE                              

                                                                           

 Name       Rows   Cols   Nonzeros    Bytes  BR      Optimal Value         

 SHIP08S     779   2387     9501      70093        1.9200982105E+06        

                                                                           

 Supplied by Bob Fourer.                                                   

 When included in Netlib: Extra free rows omitted.                         

 Source: consulting.                                                       

                                                                           

![LPnetlib/lp_ship08s](http://www2.research.att.com/~yifanhu/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_ship08s.gif)