
##########
kernel
##########
1) download source tree of android JB from Google.

2) add mediatek folder and makeMtk file. 

3) replace kernel,external,system,bootable folders.

4) build kernel by 
  . build/envsetup.sh

  choosecombo

Build type choices are:
     1. release
     2. debug

Which would you like? [1] 1

Which product would you like? [full] full

Variant choices are:
     1. user
     2. userdebug
     3. eng
Which would you like? [eng] 3

5) ./makeMtk simcom89_wet_jb2 new kernel uboot


-------------------------------------------------------------------------------
