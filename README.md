((TBT))
* CREATING COUNTER STRIKE MAPS USING HAMMER
* WORKING ON GNDU CSE DEPARTMENT MAP
* de_gndu.bsp is the compiled map
* de_gndu.rmf is what you have to work on
* Use NULL texture on surfaces which aren't visible to player in any case
* Tie objects to func_detail entity to prevent chopping
* NOTICE - don't tie to much entities... else map will compile but won't start
* Try to tie multiple object in one entity. E.g:- all benches in a classroom
* Don't tie all similar objects in whole map in one entity it will hang up the compiler
* while testing map use start game press ` key a dialog box will appear type in following commands :
1)- map <map_name> WHERE map_name is the name of the map
2)- developer 1
3)- r_speeds 1
4)- gl_wireframe 1
5)- gl_wireframe 2
NOTE:- out of last two commands use only one acc. to ur need(try both u will know ur needs)

**************************** KEEP WORKING *****************************************
