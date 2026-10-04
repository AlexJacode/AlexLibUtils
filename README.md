# <p align="center"> Alex Utilities Library 
<p align="center"> Simple CLI Linux/Unix Utilities, Written In C++ 
<p align="center"> Originally Compiled With G++ (GNU/GCC) 

### Setup  
Run `g++ -o /AlexLibUtils/inject inject.cpp` <br>
Run `g++ -o /AlexLibUtils/canonize canonize.cpp` <br>

- Repeat For Any Other Binaries. -O3 Optimization Level Tested For Both inject And canonize As Working <br>

### Bootstrapping With canonize 
Run `./canonize canonize ./canonize` <br>
Run `./canonize inject ./inject`


**Use Sudo If Necessary 


### NOTE ON CANONIZE 

Generally Speaking, You Should Be Using An Absolute Path Instead Of A Relative One, So You Can Use The Tool Anywhere. As Such, The Following Example Outlines The Best Practice For All Usage: 

`./canonize canonize /dir/subdir/canonize` 