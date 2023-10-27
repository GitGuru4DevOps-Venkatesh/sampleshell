# sampleshell
Creating Automation using shell script-Git Cloning
*****
#!/bin/bash


# Create MainBranch directory

mkdir directory1

cd directory1



# Create Dir1 and Dir2

mkdir Dir1

mkdir Dir2



# Go to Dir1 and create DirA and DirB

cd Dir1

mkdir DirA

mkdir DirB



# Go back to the main branch and go to Dir2, then create Dirc and Dird

cd ..

cd Dir2

mkdir Dirc

mkdir Dird



# Go to DirA and create File1 and File2

cd ../Dir1/DirA

touch File1

touch File2



# Go back to Dir1 and select DirB, then create File3 and File4

cd ..

cd DirB

touch File3

touch File4



# Go back to the main branch and select DirC, then create File5 and File6

cd ../../

cd Dir2/Dirc

touch File5

touch File6



# Go back to the main branch and select DirD, then create File7 and File8

cd ../../

cd Dir2/Dird

touch File7

touch File8

cd ../../
****************
