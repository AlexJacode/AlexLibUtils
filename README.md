# <p align="center"> Alex Utilities Library 
<p align="center"> Simple CLI Linux/Unix Utilities, Written In C++ 
<p align="center"> Originally Compiled With G++ (GNU/GCC) 

### Setup  
Run `g++ -o AlexLibUtils/inject AlexLibUtils/inject.cpp` <br>
Run `g++ -o AlexLibUtils/canonize AlexLibUtils/canonize.cpp` <br>

- Repeat For Any Other Binaries. -O3 Optimization Level Was Tested For `inject`, `injectCX`, `hconvc++` And `canonize` As Working <br>

### <p align="center"> Rust Portions (Rewrites) 
<p align="center"> Originally Compiled With rustc <br> 

### Rust Setup <br> 
Run `rustc -o AlexLibUtils/rinject AlexLibUtils/rinject.rs` <br> 
Run `rustc -o AlexLibUtils/canonizer AlexLibUtils/canonize.rs` <br> 

- Repeat For Any Other Binaries. `-C opt-level=3` Optimization Level Has Been Tested On `rinject`, `hconvrs` And `canonizer` As Working. <br>


### Bootstrapping With canonize 
Run `./canonize canonize ./canonize` <br>
Run `./canonize inject ./inject`


**Use Sudo If Necessary 


### NOTE ON CANONIZE 

Generally Speaking, You Should Be Using An Absolute Path Instead Of A Relative One, So You Can Use The Tool Anywhere. As Such, The Following Example Outlines The Best Practice For All Usage: 

`./canonize canonize /dir/subdir/canonize` 

<br> <br> 
Note: injectCX (inject-CustomX) Is A Custom Version Of inject That Uses Memory For Holding All Data Instead Of Disk. This Means That While It Is Faster And More Efficient, It’s Incapable Of Handling Files That Are Larger Than The Amount Of Available System RAM. As Such, Large Files Should Be Handled With Regular inject. 
