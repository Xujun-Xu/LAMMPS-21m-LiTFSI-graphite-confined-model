### This is the complete workflow for constructing the 21 M LiTFSI confined model.  
The softwares that need to be installed are Packmol and Moltemplate.  
The force field parameters for the aqueous LiTFSI solution are taken from https://pubs.acs.org/doi/10.1021/acs.jpcb.1c02189;   
The AIREBO force field is used for graphite.  
The interaction parameters between carbon and other atoms are derived from https://doi.org/10.1021/jp0268112.  
You need to perform the following two steps:  
1. packmol < packmol.inp  
2. moltemplate.sh -nocheck system.lt -pdb solvation.pdb  
