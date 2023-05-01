Download Link: https://assignmentchef.com/product/solved-caa-homework-1
<br>
1.5 [4] &lt;S1.6&gt; Consider three different processors PI, P2, and P3 executing the same instruction set. PI has a 3GHz clock rate and a CPI of 1.5. P2 has a 2.5 GHz clock rate and a CPI of 1.0. P3 has a 4.0 GHz clock rate and has a CPI of 2.2.

<ol>

 <li>Which processorhas the highestperformance expressedin instructions per second?</li>

 <li>If the processors each execute a program in 10 seconds, find the number of cycles and the number of instructions.</li>

 <li>We are trying to reduce the execution time by 30%, but this leads to an increase of20% in the CPI. What clock rate should we have to get this time reduction?</li>

</ol>

1.6 [20] Consider two different implementations of the same instruction set architecture. The instructions can be divided into four classes according to their CPI (classes A, B, C, and D). PI with a clock rate of 2.5 GHz and CPIs of 1, 2, 3, and 3, and P2 with a clock rate of 3 GHz and CPIs of 2, 2, 2, and 2.

Given a program with a dynamic instruction count of 1.0E6 instructions divided into classes as follows: 10% class A, 20% class B, 50% class C, and 20% class D, which is faster: PI or P2?

<ol>

 <li>What is the global CPI for each implementation?</li>

 <li>Find the clock cycles required in both cases.</li>

</ol>

1.7 [15] &lt;S1.6&gt; Compilers can have a profound impact on the performance of an application. Assume that for a program, compiler A results in a dynamic instruction count of 1.0E9 and has an execution time of 1.1 s, while compiler B results in a dynamic instruction count of 1.2E9 and an execution time of 1.5 s.

<ol>

 <li>Find the average CPI for each program given that the processor has a clock cycle time of 1 ns.</li>

 <li>Assume the compiled programs run on two different processors. If the execution times on the two processors are the same, how much faster is the clock of the processor running compiler A’s code versus the clock of the processor running compiler B’s code?</li>

 <li>A new compiler is developed that uses only 6.0E8 instructions and has an average CPI of 1.1. What is the speedup of using this new compiler versus using compiler A or B on the original processor?</li>

</ol>

1.11 The results of the SPEC CPU2006 bzip2 benchmark running on an AMD Barcelona has an instruction count of 2.389E12, an execution time of 750 s, and a reference time of 9650 s.

<ul>

 <li>[5] &lt;SS1.6, 1.9&gt; Find the CPI if the clock cycle time is 0.333 ns.</li>

 <li>[5] Find the SPECrati0.</li>

 <li>[5] &lt;SS1.6, 1.9&gt; Find the increase in CPU time ifthe number ofinstructions of the benchmark is increased by 10% without affecting the CPI.</li>

 <li>[5] &lt;SSI .6, 1.9&gt; Find the increase in CPU time ifthe number ofinstructions of the benchmark is increased by 10% and the CPI is increased by 5%.</li>

 <li>[5] &lt;SS1.6, 1.9&gt; Find the change in the SPECratio for this change.</li>

 <li>[10] &lt;S1.6&gt; Suppose that we are developing a new version of the AMD Barcelona processor with a 4GHz clock rate. We have added some additional instructions to the instruction set in such a way that the number of instructions has been reduced by 15%. The execution time is reduced to 700s and the new SPECratio is 13.7. Find the new CPI.</li>

 <li>[10] This CPI value is larger than obtained in 1.11.1 as the clock rate was increased from 3 GHz to 4 GHz. Determine whether the increase in the CPI is similar to that of the clock rate. If they are dissimilar, why?</li>

 <li>[5] By how much has the CPU time been reduced?</li>

 <li>[10] &lt;S1.6&gt; For a second benchmark, libquantum, assume an execution time of 960ns, CPI of 1.61, and clock rate of 3 GHz. If the execution time is reduced by an additional 10% without affecting the CPI and with a clock rate of 4 GHz, determine the number of instructions.</li>

 <li>[10] &lt;S1.6&gt; Determine the clock rate required to give a further 10% reduction in CPU time while maintaining the number of instructions and with the CPI unchanged.</li>

 <li>[10] &lt;S1.6&gt; Determine the clock rate if the CPI is reduced by 15% and the CPU time by 20% while the number of instructions is unchanged.</li>

</ul>

1.14 Assume a program requires the execution of 50 x 10<sup>6 </sup>FP instructions, 110 x 10<sup>6 </sup>INT instructions, 80 x 10<sup>6 </sup>L/S instructions, and 16 x 10<sup>6 </sup>branch instructions. The CPI for each type of instruction is 1, 1, 4, and 2, respectively. Assume that the processor has a 2 GHz clock rate.

<ul>

 <li>[10] By how much must we improve the CPI of FP instructions if we want the program to run two times faster?</li>

 <li>[10] By how much must we improve the CPI of L/S instructions ifwe want the program to run two times faster?</li>

 <li>[5] By how much is the execution time of the program improved if the CPI of INT and FP instructions is reduced by 40% and the CPI of L/S and Branch is reduced by 30%?</li>

</ul>