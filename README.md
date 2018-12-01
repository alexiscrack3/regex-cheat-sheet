# Regular Expressions Cheat Sheet

A collection of some of the most useful regular expressions

|Anchors|Description|Example|Matches|Zero Matches|
:---|:---|:---|:---|---
^|Starts with|^demo|demos,demonstration|my demo|
$|Ends with|demo$|my demo|demos,demonstration|

|Quanti­fiers|Description|Example|Matches|Zero Matches|
:---|:---|:---|:---|---
*|0 or more|goo*gle|google,gooogle,goooogle|gogle|
+|1 or more|goo+gle|google,gooogle,goooogle|gogle|
?|0 or 1|goo?gle|google|gooogle,goooogle|
{x}|Exactly x|w{3}|www|w,ww|
{x,}|x or more|go{2,}gle|google,gooogle,goooogle|gogle|
{x,y}|Between x and y|w{1,3}|w,ww,www|wwww|
