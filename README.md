# cose213-assignment-1--c-and-array-solved
**TO GET THIS SOLUTION VISIT:** [COSE213 Assignment 1- C++ and Array Solved](https://www.ankitcodinghub.com/product/cose213-assignment-1-c-and-array-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98272&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COSE213 Assignment 1- C++ and Array&nbsp;Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
COSE213 Assignment 1: C++ and Array

In this assignment, you will implement the polynomial abstract data type (ADT) using C++ and array. The skeleton files – polynomial.h and main.cpp, are provided. You are required to complete the implementation of the class Polynomial in polynomial.cpp. This class definition is based on the version 3 discussed in the class.

a) Skeleton files

polynomial.h

In this file, the polynomial abstract data type (class) is defined as follows.

<ul>
<li>Polynomial(const Polynomial&amp; source) : copy constructor</li>
<li>~Polynomial() : destructor</li>
<li>Polynomial&amp;operator=(constPolynomial&amp;source):
Assignment operator
</li>
<li>Polynomial operator+(const Polynomial&amp; source) : Sum of
polynomials
</li>
<li>Polynomialoperator-(constPolynomial&amp;source):
Subtraction of polynomials
</li>
<li>Polynomialoperator*(constPolynomial&amp;source):
Multiplication of polynomials
</li>
<li>Polynomial Derivative():compute the derivative of polynomial</li>
<li>booloperator==(constPolynomial&amp;source):checkifleftand
right polynomial are identical and return true/false accordingly.
</li>
<li>float Eval(float x) : evaluate polynomial at x</li>
<li>voidCreateTerm(constfloatcoef,constintexp):createa
new polynomial term of coef*x^(exp). exp must be non-negative value. If the same exponent term already exists, replace its coefficient with the new one.

There are several functions pre-defined in the header files (you are not allowed to change the implementation of these functions), such as
</li>
</ul>
<ul>
<li>Polynomial() : default constructor</li>
<li>Print() : print the current polynomial.</li>
<li>Capacity():maximumnumberoftermsthispolynomialcanstore</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>Terms() : returns the number of non-zero terms currently stored in this polynomial</li>
<li>GetTerm(int x) : get the access of a term (x is the index of that term).
polynomial.cpp

This is the actual implementation of the functions defined in the header file. You need to fill in // ToDo part.

Note
</li>
</ul>
<ol>
<li>Make sure you implement the copy constructor and assignment operator correctly so that assigning one polynomial to the other using = operator or creating a new polynomial from an existing polynomial object work correctly.</li>
<li>Make sure that CreateTerm() resizes the array if more terms are created than the current object can handle. Stress tests will be conducted.</li>
<li>When a new term is added using CreateTerm(), if there is no term existing in the current polynomial of a given exponent, you need to create a new term. If the same exponent term exists, then you need to replace its coefficient with the new one.</li>
</ol>
4. CreateTerm() does not need to be called the descending order of exponent term, but the termArray must be internally arranged in a descending order. For example, if you call CreateTerm(3,1) to create a polynomial term 3x, and then you create a higher order term by calling CreateTerm(2,2), then the resulting polynomial should be 2x^2+3x (not 3x+2x^2).

<ol start="5">
<li>If a term has a zero (or close to zero, abs(coef) &lt; 1.0e-6) coefficient, then you need to remove that term from the polynomial. For example, if p1=2x^2+1 and p2=2x^2+x+1, then p1-p2 will make the coefficient of x^2 term zero, so the result should be –x-1.</li>
<li>We provided print() function that prints out the given polynomial as the following form.
cnx^n+cn-1x^(n-1)+ …. +c1x^1+c0

Do not change print() function because this will be used to check your code. You must manage your polynomial terms in a descending order because print function does not automatically sort the order of terms.
</li>
<li>You must submit polynomial.cpp only.</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
8. You are not allowed to use STL library.

main.cpp

This is the driver program to test your Polynomial class. This file contains testing code to evaluate the correctness of your implementation. If your implementation is correct, the result should be as follows:

<pre>f = -4x^3+2.3x^2-3
g = 3x^4-4x^3-8
g (creating a new term) = 3x^4-4x^3+5x^2-8
h (created from f) = -4x^3+2.3x^2-3
h (assigned from g) = 3x^4-4x^3+5x^2-8
f + g = 3x^4-8x^3+7.3x^2-11
f - g = -3x^4-2.7x^2+5
f(3.5) is -146.325
Derivative of f = -12x^2+4.6x^1
</pre>
This is just a simple test code. When we grade your code, we will conduct more rigorous testing to check whether every function is working correctly and robustly.

b) Compile and submit

You must submit the code (polynomial.cpp only) online via blackboard. You can compile the code as follows:

&gt; make

The output executable name is assign_1. You can run your code by simply type in

this name in the terminal.

&gt; assign_1

&nbsp;

</div>
</div>
</div>
