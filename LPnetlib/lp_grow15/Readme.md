# LPnetlib/lp_grow15

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_grow15

 [Netlib LP problem grow15: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 632

 date: 1983

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

 GROW15      301    645     5665      35041  B    -1.0687094129E+08        

                                                                           

         BOUND-TYPE TABLE                                                  

 GROW15     UP                                                             

                                                                           

 Supplied by Bob Fourer.                                                   

 When included in Netlib: Extra bound sets omitted; explicit zeros         

 omitted; Cost coefficients negated.                                       

                                                                           

 Source:   GROW15, GROW22, GROW7: R. Fourer, "Solving Staircase Linear     

 Programs by the Simplex Method, 2: Pricing", Math. Prog. 25 (1983),       

 pp. 251-292.                                                              

                                                                           

![LPnetlib/lp_grow15](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_grow15.gif)
