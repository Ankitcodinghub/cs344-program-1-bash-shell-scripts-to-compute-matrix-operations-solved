# cs344-program-1-bash-shell-scripts-to-compute-matrix-operations-solved
**TO GET THIS SOLUTION VISIT:** [CS344 Program 1-Bash shell scripts to compute matrix operations Solved](https://www.ankitcodinghub.com/product/cs344-program-1-bash-shell-scripts-to-compute-matrix-operations-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;81609&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS344 Program 1-Bash shell scripts to compute matrix operations Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
This assignment asks you to write bash shell scripts to compute matrix operations. The purpose is to get you familiar with the Unix shell, shell programming, Unix utilities, standard input, output, and error, pipelines, process ids, exit values, and signals (at a basic level).

What you’re going to submit is your script, called simply “matrix”.

<h1>Overview</h1>
In this assignment, you will write a bash shell script that calculates basic matrix operations using input from either a file or stdin. The input will be whole number values separated by tabs into a rectangular matrix. Your script should be able to print the dimensions of a matrix, transpose a matrix, calculate the mean vector of a matrix, add two matrices, and multiply two matrices.

You will be using bash builtins and Unix utilities to complete the assignment. Some commands to read up on are ​while​, ​cat​, ​read​, ​expr​, ​cut​, ​head​, ​tail​, ​wc​, and sort.​

Your script must be called simply “matrix”. The general format of the matrix command is:

<strong>matrix</strong>​ ​<em>OPERATION</em>​ [​<em>ARGUMENT</em>​]…

Refer to ​<strong>man(1)</strong>​ for an explanation of the conventional notation regarding command syntax, to understand the line above. Note that many terminals render italic font style as an underline:

<strong>matrix</strong>​ OPERATION [ARGUMENT]…

<h1>Specifications</h1>
Your program must perform the following operations: dims, transpose, mean, add, and multiply. Usage is as follows:

<strong>matrix dims</strong>​ [​<em>MATRIX</em>​] <strong>matrix transpose</strong>​ [​<em>MATRIX</em>​] <strong>matrix mean</strong>​ [​<em>MATRIX</em>​] <strong>matrix add</strong>​ ​<em>MATRIX_LEFT</em>​ ​<em>MATRIX_RIGHT</em> <strong>matrix multiply</strong>​ ​<em>MATRIX_LEFT</em>​ ​<em>MATRIX_RIGHT</em>

The dims, transpose, and mean operations should either perform their respective operations on the file named ​<em>MATRIX</em>​, or on a matrix provided via stdin. The add and multiply operations do not need to process input via stdin.

<ul>
<li>dims should print the dimensions of the matrix as the number of rows, followed by a space, then the number of columns.</li>
<li>transpose should reflect the elements of the matrix along the main diagonal. Thus, an MxN matrix will become an NxM matrix and the values along the main diagonal will remain unchanged.</li>
<li>mean should take an MxN matrix and return an 1xN row vector, where the first element is the mean of column one, the second element is the mean of column two, and so on.</li>
<li>add should take two MxN matrices and add them together element-wise to produce an MxN matrix. add should return an error if the matrices do not have the same dimensions.</li>
<li>multiply should take an MxN and NxP matrix and produce an MxP matrix. Note that, unlike addition, matrix multiplication is not commutative. That is A*B != B*A.</li>
</ul>
Here is a brief example of what the output should look like.

<h2>$ cat m1</h2>
1&nbsp;&nbsp;&nbsp; 2&nbsp;&nbsp;&nbsp; 3&nbsp;&nbsp;&nbsp; 4

5&nbsp;&nbsp;&nbsp; 6&nbsp;&nbsp;&nbsp; 7&nbsp;&nbsp;&nbsp; 8

<h2>$ cat m2</h2>
1&nbsp;&nbsp;&nbsp; 2

3&nbsp;&nbsp;&nbsp; 4

5&nbsp;&nbsp;&nbsp; 6

7&nbsp;&nbsp;&nbsp; 8

<strong>$ ./matrix dims m1</strong>

2 4

<strong>$ cat m2 | ./matrix dims</strong>

4 2

<h2>$ ./matrix add m1 m1</h2>
2&nbsp;&nbsp;&nbsp; 4&nbsp;&nbsp;&nbsp; 6&nbsp;&nbsp;&nbsp; 8

10&nbsp;&nbsp; 12&nbsp;&nbsp; 14&nbsp;&nbsp; 16

<h2>$ ./matrix add m2 m2</h2>
2&nbsp;&nbsp;&nbsp; 4

6&nbsp;&nbsp;&nbsp; 8

10&nbsp;&nbsp; 12

&nbsp;

3&nbsp;&nbsp;&nbsp; 4&nbsp;&nbsp;&nbsp; 5&nbsp;&nbsp;&nbsp; 6

<h2>$ ./matrix transpose m1</h2>
<ul>
<li>5</li>
<li>6</li>
<li>7</li>
<li>8</li>
</ul>
<h2>$ ./matrix multiply m1 m2</h2>
50&nbsp;&nbsp; 60

114 140

&nbsp;

You must check for the right number and format of arguments to matrix. This means that, for example, you must check that a given input file is readable, before attempting to read it. You are not required to test if the input file ​<em>itself</em>​ is valid. In other words, the behavior of matrix is undefined when the matrix input is not a valid matrix. for the purposes of this assignment, a valid matrix is a tab-delimited table containing at least one element, where each element is a signed integer, every entry is defined, and the table is rectangular.

The following are examples of invalid matrices and will not be tested against your code, and may ​<em>not</em>​ be output by your program:

<ul>
<li>An empty matrix.</li>
<li>A matrix where the final entry on a row is followed by a tab character.</li>
<li>A matrix with empty lines.</li>
<li>A matrix with any element that is blank or not an integer.</li>
</ul>
Here is a valid matrix file, m1:

<h2>$ cat m1</h2>
8&nbsp;&nbsp;&nbsp; 5&nbsp;&nbsp;&nbsp; 6

3&nbsp;&nbsp;&nbsp; 2&nbsp;&nbsp;&nbsp; 2

1&nbsp;&nbsp;&nbsp; 6&nbsp;&nbsp;&nbsp; 7

5&nbsp;&nbsp;&nbsp; 0&nbsp;&nbsp;&nbsp; 7

2&nbsp;&nbsp;&nbsp; 2&nbsp;&nbsp;&nbsp; 4

<strong>$ cat -A m1 </strong>​ # The ‘-A’ flag shows tabs as ‘^I’ and newlines as ‘$’. This is a good way to check correctness.

8^I5^I6$

3^I2^I2$

1^I6^I7$

5^I0^I7$

2^I2^I4$

<strong>$</strong>

If the inputs are valid — your program should output only to stdout, and nothing to stderr. The return value should be 0.

If the inputs are invalid — your program should output only to stderr, and nothing to stdout. The return value should be any number except 0. The error message you print is up to you; you will receive points as long as you print ​<em>something</em>​ to stderr and return a non-zero value.

Your program will be tested with matrices up to dimension 100 x 100.

Though optional, I do recommend that you use temporary files; arrays are not recommended. For this assignment, anytemporary files you use should be put in the current working directory. (A more standard place for temporary files is in /tmp but don’t do that for this assignment; it makes grading easier if they are in the current directory.) <em>Be sure any temporary file you create uses the process id as part of its name, so that there will not be conflicts if the program is running more than once.</em>​ Be sure you remove any temporary files when your program is done. You should also use the trap command to catch interrupt, hangup, and terminate signals to remove the temporary files if the program is terminated unexpectedly.

All values and results are and must be integers. You may use the ​expr​ command to do your calculations, or any other bash shell scripting method, such as ​((expr))​. Do not use any other languages other than bash shell scripting: this means that, among others, awk, sed, tcl, bc, perl, &amp; the python languages and tools are off-limits for this assignment. Note that ​expr​ only works with whole numbers. When you calculate the average you must round to the nearest integer, where half values round away from 0 (i.e. 7.5 rounds up to 8, but -7.5 rounds down to -8). This is the most common form of rounding. When doing truncating integer division (as bash does), this formula works to divide two numbers and end up with the proper rounding:

(a + (b/2)*( (a&gt;0)*2-1 )) / b

You can learn more about rounding methods here:

<a href="https://en.wikipedia.org/wiki/Rounding#Round_half_away_from_zero">Rounding – Wikipedia (Links to an external site.)Links to an external site.</a>

<h1>Grading With a Script</h1>
To make it easy to see how you’re doing, you can download the actual grading script here:

<a href="https://oregonstate.instructure.com/courses/1662153/files/69600734/download?verifier=vZS1snugFOcmxYlg3mH4OdWdvNb1vsbL2khxpzyS&amp;wrap=1">p1gradingscript</a>

This script is very close to the one that will be used to assign your script a grade. To use the script, just place it in the same directory as your matrix script and run it like this:

$ ./p1gradingscript

When we run your script for grading, we will do this to put your results into a file we can examine more easily:

$ ./p1gradingscript &gt; grading_result.username

To compare yours to a perfect solution, you can download here a completely correct run of my script that shows what you should get if everything is working correctly:

<a href="https://oregonstate.instructure.com/courses/1662153/files/69504683/download?verifier=k0jTVXQz2FAg3sBtFnv7ouH4judiCxk60ETAO2um&amp;wrap=1">p1perfectoutput</a>

The p1gradingscript itself is a good resource for seeing how some of the more complex shell scripting commands work, too.

<h1>Summary</h1>
Your script must support the following operations:

<ul>
<li><strong>matrix dims</strong>​ [​<em>MATRIX</em>​]</li>
</ul>
○ Prints error message to stderr, nothing to stdout and return value != 0 if:

■ Argument count is greater than 1 (e.g.

`matrix dims m1 m2`).

■ Argument count is 1 but the file named by argument 1 is not readable (e.g. `matrix dims no_such_file`).

<ul>
<li>Otherwise, prints “​<em>ROWS</em>​ ​<em>COLS</em>​” (Space separated!) to stdout, nothing to stderr, and returns 0.</li>
</ul>
<ul>
<li><strong>matrix transpose</strong>​ [​<em>MATRIX</em>​]
<ul>
<li>Prints error message to stderr, nothing to stdout and return value != 0 if:</li>
</ul>
</li>
</ul>
■ Argument count is greater than 1 (e.g.

`matrix transpose m1 m2`).

■ Argument count is 1 but the file named by argument 1 is not readable (e.g. `matrix transpose no_such_file`).

○ Otherwise, prints the transpose of the input, in a valid matrix format to stdout, nothing to stderr, and returns 0.

<ul>
<li><strong>matrix mean</strong>​ [​<em>MATRIX</em>​]
<ul>
<li>Prints error message to stderr, nothing to stdout and return value != 0 if:</li>
</ul>
</li>
</ul>
■ Argument count is greater than 1 (e.g.

`matrix mean m1 m2`).

■ Argument count is 1 but the file named by argument 1 is not readable (e.g. `matrix mean no_such_file`).

○ Otherwise, prints a row vector mean of the input matrix, in a valid matrix format to stdout, nothing to stderr, and returns 0. All values must round to the nearest integer, with ***.5 values rounded away from zero.

<ul>
<li><strong>matrix add</strong>​ ​<em>MATRIX_LEFT</em>​ ​<em>MATRIX_RIGHT </em>
<ul>
<li>Prints error message to stderr, nothing to stdout and return value != 0 if:</li>
</ul>
</li>
</ul>
■ Argument count does not equal 2 (e.g.

`matrix add m1 m2 m3` or `matrix add m1`).

■ Argument count is 2 but the file named by either argument is not readable (e.g.

`matrix add m1 no_such_file`).

■ The dimensions of the input matrices do not allow them to be added together following the rules of matrix addition.

○ Otherwise, prints the sum of both matricies, in a valid matrix format to stdout, nothing to stderr, and returns 0.

<ul>
<li><strong>matrix multiply</strong>​ ​<em>MATRIX_LEFT</em>​ ​<em>MATRIX_RIGHT </em></li>
</ul>
○ Prints error message to stderr, nothing to stdout and return value != 0 if:

■ Argument count does not equal 2 (e.g. `matrix multiply m1 m2 m3` or `matrix multiply m1`).

■ Argument count is 2 but the file named by either argument is not readable (e.g.

`matrix multiply m1 no_such_file`).

■ The dimensions of the input matrices do not allow them to be multiplied together following the rules of matrix multiplication.

○ Otherwise, prints the product of both matricies, with the first argument as the left matrix and the second argumentas the right matrix, in a valid matrix format to stdout, nothing to stderr, and returns 0. (`matrix multiply A B` should return A*B, not B*A)

`

An invalid command must result in an error message to stderr, nothing to stdout, and a return value != 0.

&nbsp;
