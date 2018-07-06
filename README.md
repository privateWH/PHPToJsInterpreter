# PHPToJsInterpreter
Writing PHP Code To Run On Javascript Environment

Sample Page: (sample.php)
<?=$test?> 
<?php if () : ?> <?php endif ?>
<?php foreach () :?><?php endforeach ?>
<?php for() :?> <?php endfor ?>
<?php echo $test?>

Expected Output:
echo test;
if () { }
foreach () {}
for() {}
echo test;

-----
Sample:
<?php // Server Var To Js Var 
  $Blah = "";
  $Blah2 = 1;
  // End Var
?>

Expected Output:
var Blah = "";
var Blah2 = 1;
-----
Sample:
<?php // Server Var To Js Var
$Test = 'A';
// End Var
?>
pple

Expected Output:
var Test = 'A';
pple

