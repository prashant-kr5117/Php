# Php
 
Operators 

Arithematic :- + - % / ** *
= Used to set value right value to left value 
== Equality:  check value are same or not      
=== Identical Equality : check value as well as data type   
!= NOt equality : check whether value is not equal or not 
!== identical not equality : also check data type as well as value

 <=>  space ship operator: left number big-1 , equal-0,right side big- -1.
 
 Logical operator
 && = and
 || = or
 
String operator : used for concatenation 
Note : . is used for concatenate which is also used in oops.
print "hello"."class";

.= concatenation assignment operator

Array opoperator
$stu_rec=array();
$stu_rec=array(1,2,3,4);
$stu_cls = [1,2,3,4];

The above three arrays have same meaning with differnt syntax

Php array can contain multiple data types

#Form

get is generally use when , its unsecure-because axix by url which can anyone axis (unauthorised user) , use for bookmark 
data transmit on server -post its secure because it use http so we use it for secure matter and our data transfer , we can not use bookmark because bookmark holds url which is not supported by post ., no limitation for character set . 

The following both are array type :-
$_Get [ ] 
$_Post [ ]

-> To read from one page to another we use  - super global (7 in syllabus)

COOKIE:-
Small text files that are installed on the clients computer in the cache memory of the browser.
Max size - 4kb. Cookie are also known web as cookie, cookie or internet cookie..

Whenever a user visits to a particular website very 1st time the site send packets of data 
The info stored in cookie is not secured because this info. is stored in the text formed in the client side.
We can enable and disable the cookie as per the requirement.
Note:- Sometimes we can also use cookie as a data transfer medium among the various web pages of a website 

$_COOKIE , $_SESSION 
 
 these also creat in user machine and did not on server 


Cookie are independent but sessions are dependent. for ex- user name pass delete when we clear cookie but they stay when we clear session..

7 parameter
NAme of cookie ,actual value of cookie ,time(seconds), path,domain,secure,https

Secure - security rules followed or not .

set cookie funciton to create and delete cookie ....

Super cookie $_cookie- to axis data of coookie

