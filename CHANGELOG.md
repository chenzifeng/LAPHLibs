
19 Nov 2019
-----------
* Added adler32, test_adler32
* Created laphlibs directory, and moved everything there
    
22 Jun 2019
===========
* Adding easing.lua routines for value interpolation

13 Feb 2019
-----------
* Added math_matrix, test_math_matrix




17 Jun 2015
===========
###Cosmetic changes
* changed all core files to be lowercase
* made all functions and constants to be module local
* added exports where they didn't already exist
* changed casing of function calls on objects

##A few additions
* get_opts.lua
* getopt_alt.lua
* alt_getopt.lua - the most posix compliant

##Moved
* removed mrandom.lua
* moved strtoul.lua to experimental
* moved arena.lua to experimental
* moved cvec.lua to experimental

##stringzutils.lua 
* made all functions module local
* added all functions to exports
* strdup used malloc to allocate memory instead of ffi.new


##memorystream.lua
* Created __call() based constructor
* changed to caml casing for functions

##binarystream.lua
* Created __call() based constructor
* changed to caml casing for functions

##moved atoi from strtoul to stdc.lua
* added atol, atoll as aliases for atoi
* using tonumber() instead of cooked up version of the same

##maths.lua
* added kv_roundup32() from cvec.lua
* added is_power_of_two()
* moved round() out of global math. module

##utf.lua
* renamed functions
* added to exports

15 Jun 2015
* Updated to ensure nothing spills into global namespace by default
* Updated to use a consistent function signature style