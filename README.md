<?php

$keys = array('TestKey',); 
$users = array('2450740717',); 
$sub = $_GET["key"];
$subuser = $_GET["user"];
if (in_array($sub,$keys,TRUE)) if (in_array($subuser,$users,TRUE)) {
print('~ True ~');
}
else
{
print ($_SERVER['REMOTE_ADDR']);
}
?>
