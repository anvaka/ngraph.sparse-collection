# LPnetlib/lp_greenbeb

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_greenbeb

 [Netlib LP problem greenbeb: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 631

 date: 1984

 author: K. Palmer

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

 GREENBEB   2393   5405    31499     235739  B    -4.3021476065E+06        

                                                                           

         BOUND-TYPE TABLE                                                  

 GREENBEB   UP LO FX FR                                                    

                                                                           

 Supplied by Bob Fourer.                                                   

 Empty RHS section.                                                        

 When included in Netlib: Extra bound sets omitted,  extra free            

 rows omitted.                                                             

 Problems GREENBEA and GREENBEB differ only in their BOUNDS sections.      

                                                                           

 Bob Bixby reports that the CPLEX solver (running on a Sparc station)      

 finds slightly different optimal values for some of the problems.         

 On a MIPS processor, MINOS version 5.3 (with crash and scaling of         

 December 1989) also finds different optimal values for some of the        

 problems.  The following table shows the values that differ from those    

 shown above.  (Whether CPLEX finds different values on the recently       

 added problems remains to be seen.)                                       

                                                                           

 Problem        CPLEX(Sparc)          MINOS(MIPS)                          

 GREENBEB    -4.3022602612E+06    -4.3021537702E+06                        

                                                                           

 Source:   GREENBEA, GREENBEB: a large refinery model; see the book        

 "A Model-Management Framework for Mathematical Programming" by Kenneth    

 H. Palmer et al. (John Wiley & Sons, New York, 1984).                     

                                                                           

 Added to Netlib on  6 May 1988                                            

![LPnetlib/lp_greenbeb](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_greenbeb.gif)
