# Regular Expressions Cheat Sheet

A collection of some of the most useful regular expressions

|Anchors|Description|Example|Matches|Zero Matches|
:---|:---|:---|:---|---
^|Starts with|^demo|demos,demonstration|my demo|
$|Ends with|demo$|my demo|demos,demonstration|
\b|Word boundary|\bis\b|this is Sparta|this isn't Sparta|
\B|Not word boundary|\Bis|this is Sparta|it is Sparta|

|Quanti­fiers|Description|Example|Matches|Zero Matches|
:---|:---|:---|:---|---
*|0 or more|goo*gle|google,gooogle,goooogle|gogle|
+|1 or more|goo+gle|google,gooogle,goooogle|gogle|
?|0 or 1|goo?gle|google|gooogle,goooogle|
{x}|Exactly x|w{3}|www|w,ww|
{x,}|x or more|go{2,}gle|google,gooogle,goooogle|gogle|
{x,y}|Between x and y|w{1,3}|w,ww,www|wwww|

|Character Classes|Description|Example|Matches|Zero Matches|
:---|:---|:---|:---|---
\s|White space character|los\sangeles|los angeles|los.angeles|
\S|Non-white space character|los\Sangeles|los.angeles|los angeles|
\d|Digit character|\d{2,}|12,345|1,2,3,4,5|
\D|Non-digit character|\D{3}|foo,bar|fo1|
\w|Word character|\w{4}|v311|v3.1|
\W|Non-word character|\W|.$%?|abc|

