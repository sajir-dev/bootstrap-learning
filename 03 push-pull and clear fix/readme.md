*col-md-8* <br>
*col-md-4* <br>
this one row on md screen can be rearranged by adding classes<br>
*col-md-8 col-md-push-4* <br>
now the first item is pushed 3 columns away from left. The last 4 columns will be overlapping with second item.<br>
*col-md-4 col-md-pull-8* will pull the second item 8 colomn to the left<br>
to avoid repeating the same behaviour on lg screen. Add *col-lg-push-0* and col-lg-pull-0* to each item respectively.<br> 

##clear-fix 

clear-fix is used to clear float and avoid unnecessary complications due to height difference of th div <br>
this can be achieved by putting a *<div class=clear-fix></div>* right after the div which causes the move or right before the div which moved<br><br>
A universal solution would be instead of finding and putting clear-fix class would be applying <br>
*clear:both* for the elements in the styling.<br>