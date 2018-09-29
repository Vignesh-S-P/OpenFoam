***commands to run***


blockMesh

mergeMeshes . ../object -overwrite

topoSet

setFields


overInterDyMFoam


decomposePar

 
mpirun -np 4 overInterDyMFoam -case $HOME/Desktop/overset/testInter/domain -parallel > log.out | tail -f log.out



