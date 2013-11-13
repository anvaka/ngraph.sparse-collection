# LPnetlib/lp_pds_02

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_pds_02

 [Netlib LP problem pds_02: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 649

 date: 1990

 author: J. Kennington

 ed: I. Lustig

 fields: title name A b id aux kind date author ed notes

 aux: c lo hi z0

 kind: linear programming problem

 notes:

 A Netlib LP problem, in lp/data/kennington.  For more information             

 send email to netlib@ornl.gov with the message:                               

                                                                               

 	 send index from lp                                                          

 	 send readme from lp/data                                                    

 	 send readme from lp/data/kennington                                         

                                                                               

 The following are relevant excerpts from lp/data/kennington/readme:           

                                                                               

 The "Kennington" problems: sixteen problems described in "An Empirical        

 Evaluation of the KORBX Algorithms for Military Airlift Applications"         

 by W. J. Carolan, J. E. Hill, J. L. Kennington, S. Niemi, S. J.               

 Wichmann (Operations Research vol. 38, no. 2 (1990), pp. 240-248).            

                                                                               

 The following table gives some statistics for the "Kennington"                

 problems.  The number of columns excludes slacks and surpluses.               

 The bounds column tells how many entries appear in the BOUNDS                 

 section of the MPS file.  The mpc column shows the bytes in                   

 the problem after "uncompress" and before "emps"; MPS shows                   

 the bytes after "emps".  The optimal values were computed by                  

 Vanderbei's ALPO, running on an SGI computer (with binary IEEE                

 arithmetic).                                                                  

                                                                               

 Name       rows  columns  nonzeros  bounds      mpc      MPS     optimal value

 PDS-02     2954    7535     21252     2134    197821    801690   2.8857862e+10

                                                                               

 Submitted to Netlib by Irv Lustig.                                            

                                                                               

![LPnetlib/lp_pds_02](http://www2.research.att.com/~yifanhu/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_pds_02.gif)