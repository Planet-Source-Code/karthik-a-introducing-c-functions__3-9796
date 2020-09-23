<div align="center">

## Introducing C\+\+ \- Functions


</div>

### Description

This tutorial intends to teach beginners how to use functions in programs along with the various terms used like 'calling' a function and 'passing' values to a function and so on.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Karthik A](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/karthik-a.md)
**Level**          |Beginner
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |C, C\+\+ \(general\)
**Category**       |[Documents](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/documents__3-27.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/karthik-a-introducing-c-functions__3-9796/archive/master.zip)





### Source Code


<p align="center"><b><font color="#000080" size="6">Introducing C++ - Part 3</font></b></p>
<p align="center">&nbsp;</p>
<p align="center"><font size="6" color="#0000FF"><b>Functions</b></font></p>
<p align="center">&nbsp;</p>
<p align="left"><b><font size="6" color="#0000FF">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</font></b><font size="4" color="#0000FF">W</font><font size="4">e will now see
the usage of functions is C++. Functions are very useful if you desire to use a
particular set of statements or a particular operation again and again. With the
help of a simple example i will explain the concept of functions. </font></p>
<p align="left"><font size="4">The general form of a function is</font></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp; <i>return-type</i>
function-name (<i>parameter 1</i>, <i>parameter 2)</i></font></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp; {</font></p>
<p align="left">&nbsp;</p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp; }</font></p>
<p align="left"><font size="4"><i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
return-type&nbsp;&nbsp;&nbsp;&nbsp; -&gt; </i>Its the value that the function will
return after various calculations. </font></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
function-name -&gt; This is the name of the function that we like to use</font></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <i>
parameter 1</i>&nbsp;&nbsp;&nbsp; -&gt;&nbsp; This is also called as the argument.
These are the variables that are being passed on to the function</font></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <i>
parameter 2</i>&nbsp;&nbsp;&nbsp; -&gt;&nbsp; Another variable that is passed to
the function</font></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I will
illustrate the use of functions with the help of the following example</font></p>
<p align="left"><i><font size="4">#include&lt;iostream.h&gt;</font></i></p>
<p align="left"><i><font size="4">int add(int x, int y)</font></i></p>
<p align="left"><i><font size="4">{</font></i></p>
<p align="left"><i><font size="4">int z;</font></i></p>
<p align="left"><i><font size="4">z=x+y;</font></i></p>
<p align="left"><i><font size="4">return z;</font></i></p>
<p align="left"><i><font size="4">}</font></i></p>
<p align="left"><i><font size="4">void main()</font></i></p>
<p align="left"><i><font size="4">{</font></i></p>
<p align="left"><i><font size="4">int a=3,b=5,c;</font></i></p>
<p align="left"><i><font size="4">c=add(a,b);</font></i></p>
<p align="left"><i><font size="4">cout&lt;&lt;&quot;The sum is &quot;&lt;&lt;c;</font></i></p>
<p align="left"><i><font size="4">}</font></i></p>
<p align="left">&nbsp;</p>
<p align="left"><font size="4">Let us see how the code works</font></p>
<p align="left"><i><font size="4">int add(int x, int y)</font></i></p>
<p align="left"><i><font size="4">{</font></i></p>
<p align="left"><i><font size="4">int z;</font></i></p>
<p align="left"><i><font size="4">z=x+y;</font></i></p>
<p align="left"><i><font size="4">return z;</font></i></p>
<p align="left"><i><font size="4">}</font></i></p>
<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <font size="4">&nbsp; In the
above code segment 'add' is the function name and 'int' is the return-type.
</font></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; There are
two parameters 'int x' and 'int y'.</font></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The variable
int z is used to store the sum of the two numbers.</font></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; As
mentioned before,</font></p>
<p align="left"><i><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
return z;</font></i></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
the integer z is returned back. </font></p>
<p align="left">&nbsp;</p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Ok but where does the terms 'calling' and 'returning' the values arises? We will
see that...</font></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In the
main section you will be able to the lines</font></p>
<p align="center"><i><font size="4">int a=3,b=5,c;</font></i></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Here
we are declaring (and initializing) a and b and declaring a variable c.</font></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Consider the following line:</font></p>
<p align="center"><i><font size="4">c=add(a,b);</font></i></p>
<p align="left"><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; At
this point the function gets 'CALLED'. The function 'add' is called with two
parameters 'a' and 'b'. It is said that the integers a and b are passed to the
function 'add'. </font></p>
<p><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; When the function
is called the program control is transferred to the 'add' function. The two
parameters a and b are added and 'RETURNED' through the variable 'z'. This
variable is stored in 'c' and then printed.</font></p>
<p><font size="4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This is how
functions work in C++ and any other language. This is just one way of using
functions and you will know more as you proceed.</font></p>
<p align="center"><font size="4">RATE THE TUTORIAL IF YOU LIKE IT and GIVE YOUR
COMMENTS TOO.</font></p>
<p align="center"><font size="4">THANK YOU!</font></p>

