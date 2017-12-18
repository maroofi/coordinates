# coordinates
// Convert UTM to LatLong and vice versa.  

###Usage: 

```php
<?php  

  require_once("coordinates.php");   

  echo ll2utm(36.311665575277935,59.55385813725379);   

  echo "<br/>";   
  
  echo utm2ll(729286.9550018794,4021544.8279992654,40,true);   
  
?>   
```
```php
/*  
  output:  
  {"success":true,"attr":{"x":729286.95500188,"y":4021544.8279993,"zone":40,"aboveEquator":true}}  
  {"success":true,"attr":{"lat":36.311665575271,"lon":59.553858137274}}  
*/  
```
###Functions

utm2ll() --> This function convert UTM to Lat and long.
  
ll2utm() --> This function convert LatLong to UTM.
  
Reference:
based on the javascript code:
http://home.hiwaay.net/~taylorc/toolbox/geography/geoutm.html
