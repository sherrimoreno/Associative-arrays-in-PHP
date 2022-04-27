# Associative-arrays-in-PHP
Associative arrays in PHP
<html>
  <body>
 
  <?php
  /* The first method to create an associative array. */
  $luong_nhan_vien = array("hoang" => 2000, "manh" => 1000, "huong" => 500);
 
  echo "Employee's salary is ". $luong_nhan_vien['hoang'] . "<br />";
  echo "Employee's salary is ". $luong_nhan_vien['manh']. "<br />";
  echo "Employee's salary is ". $luong_nhan_vien['huong']. "<br />";
 
  /* Second method to create associative arrays. */
  $luong_nhan_vien['hoang'] = "high";
  $luong_nhan_vien['manh'] = "medium";
  $luong_nhan_vien['huong'] = "low";
 
  echo "The salary of the wild employee is ". $luong_nhan_vien['hoang'] . "<br />";
  echo "Employee's salary is ". $luong_nhan_vien['manh']. "<br />";
  echo "Employee salary is ". $luong_nhan_vien['huong']. "<br />";
  ?>
 
  </body>
</html>
