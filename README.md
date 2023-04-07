<h1 align="center">
	<a href="https://en.wikipedia.org/wiki/C_(programming_language)"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C Programming Language" width="100"height="100"></a>
	<a href="https://unix.org/"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unix/unix-original.svg" alt="UNIX" width="100" height="100"></a>
	<br>
	ft_printf
</h1>

<p>
ft_printf is the recode of the printf function.
<br>The function takes a format string as its first argument specifies the format. The format string can include placeholders for values to be printed. The placeholders are denoted by % symbols, followed by a letter indicating the data type of the printed value.
</p>
<p>
Function handles the following conversions: cspdiuxX%. These conversions are:<br>
<ul>
<li>%: prints a percent sign</li>
<li>c: prints a single character</li>
<li>s: prints a string</li>
<li>p: prints a pointer address in hexadecimal</li>
<li>d or i: prints a signed decimal integer</li>
<li>u: prints an unsigned decimal integer</li>
<li>x or X: prints a hexadecimal integer, with x producing lowercase letters and X producing uppercase letters.</li>
</ul>
These conversions are used to format and print the values of the corresponding arguments that are passed to ft_printf. For example, to print a string, you would use %s in the format string and pass the string as an argument to ft_printf. Similarly, to print an integer, you would use %d or %i in the format string and pass the integer as an argument.
</p>

<h2>&#128736; Usage</h2>
<h3>&#128679; Requirements</h3>
The function is written in C language and thus needs the gcc compiler and some standard C libraries to run.

<h3>&#128466; Instructions</h3>

<p><b>1. Using it in your code</b></p>
To use the function in your code, simply include its header:
<p><code>#include "ft_printf.h"</code></p>

<p><b>2. Compiling</b></p>
To compile, go to the library path and run:
<p><code>$ make</code></p>

<h2>&#128221; Testing</h2>
<p>You can use the printf function to compare and test the project.</p>
