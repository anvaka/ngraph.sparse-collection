# LPnetlib/lp_standata

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_standata

 [Netlib LP problem standata: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 692

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

 for "has ranges".  The BOUND-TYPE TABLE below shows the bound types       

 present in those problems that have bounds.                               

                                                                           

 The optimal value is from MINOS version 5.3 (of Sept. 1988)               

 running on a VAX with default options.                                    

                                                                           

                        PROBLEM SUMMARY TABLE                              

                                                                           

 Name       Rows   Cols   Nonzeros    Bytes  BR      Optimal Value         

 STANDATA    360   1075     3038      26135  B     1.2576995000E+03        

                                                                           

         BOUND-TYPE TABLE                                                  

 STANDATA   UP    FX                                                       

                                                                           

 Supplied by Bob Fourer.                                                   

                                                                           

 STANDGUB includes GUB markers; with these lines removed (lines in         

 the expanded MPS file that contain primes, i.e., that mention the rows    

 'EGROUP' and 'ENDX'), STANDGUB becomes the same as problem STANDATA;      

 MINOS does not understand the GUB markers, so we cannot report an         

 optimal value from MINOS for STANDGUB.  STANDMPS amounts to STANDGUB      

 with the GUB constraints as explicit constraints.                         

                                                                           

 Source: consulting.                                                       

                                                                           

![LPnetlib/lp_standata](http://www2.research.att.com/~yifanhu/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_standata.gif)