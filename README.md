#Uso  no inut.php

function dd($ResponSer){
  return   MasterClass::Debug($ResponSer);
}

function ddd($ResponSer){
  echo '<pre>';
  print_r($ResponSer);
}
