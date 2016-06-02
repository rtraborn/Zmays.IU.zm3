### BSGenome Package for Zea mays

### To forge this package on your machine, please do the following:
#### 1) Move the .fsa files into /extdata
#### 2) From an R console, enter the following commands:
     	> library(BSgenome) #this assumes that BSgenome has been installed
	> forgeBSgenomeDataPkg("/path/to/ZmaysZm3_seed") #this should work without issue (takes ~3-5 minutes), provided the files are in the correct location
	> q() # quit to return to the command line
#### 3) From a linux/unix command line, install the package that you have just created (it should now be in your working directory as "BSgenome.zmv3/")
     	 >$ R CMD INSTALL BSgenome.zmv3 # you will see the package being installed 