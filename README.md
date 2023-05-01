Download Link: https://assignmentchef.com/product/solved-blg242e-experiment2-combinational-logic-circuits
<br>
The aim in this experiment is to find the expression with the lowest cost for combinational logic circuits and implement them. In this experiment, you are allowed to use ‘&amp;’ (Bitwise AND), ‘|’ (Bitwise OR), ‘∼’ (Bitwise NOT), and ‘{}’ (Concatenate) operations. Other operations such as ‘+’, ‘-’, ‘*’, ‘/’, ‘<em>&lt;&lt;</em>’, ‘<em>&gt;&gt;</em>, ‘ˆ’, always, switch case, and if else are forbidden.

<h1>2 Preliminary</h1>

<ol>

 <li>For the function <em>F</em><sub>1 </sub>given in Equation 1, apply the following operations:

  <ol>

   <li>Find its prime implicants using Karnaugh diagram.</li>

   <li>Find its prime implicants using Quine-McCluskey method.</li>

   <li>Create prime implicant chart and find the expression with the minimum cost with 2 units of cost for each variable and 1 unit of cost for complement of a variable.</li>

   <li>Design and draw the lowest cost expression using NOT, AND, and OR gates.</li>

   <li>Design and draw the lowest cost expression using only NAND gates.</li>

   <li>Design and draw the lowest cost expression using a single 8:1 Multiplexer and NOT gates.</li>

  </ol></li>

</ol>

<em>F</em><sub>1</sub>(<em>a,b,c,d</em>) = ∪<sub>1</sub>(0<em>,</em>1<em>,</em>3<em>,</em>5<em>,</em>8<em>,</em>10<em>,</em>13<em>,</em>14) + ∪<em><sub>φ</sub></em>(2<em>,</em>7<em>,</em>11<em>,</em>12)                            (1)

<ol start="2">

 <li>Design and draw the functions <em>F</em><sub>2 </sub>and <em>F</em><sub>3 </sub>given in Equations 2 and 3 using ONE single 3:8 decoder, 2-input OR gates (<em>x</em><sup>0 </sup>represents the complement of <em>x</em>).</li>

</ol>

<table width="329">

 <tbody>

  <tr>

   <td width="311"><em>F</em><sub>2</sub>(<em>a,b,c</em>) = <em>abc</em><sup>0 </sup>+ <em>a</em><sup>0</sup><em>c</em></td>

   <td width="19">(2)</td>

  </tr>

  <tr>

   <td width="311"><em>F</em><sub>3</sub>(<em>a,b,c</em>) = <em>ab</em><sup>0</sup><em>c</em><sup>0 </sup>+ <em>bc</em></td>

   <td width="19">(3)</td>

  </tr>

 </tbody>

</table>

1

<em>Experiment 2: Combinational Logic Circuits</em>

3 Experiment

<h1>Part 1</h1>

Please implement the circuit that you have designed in Preliminary 1.d. section using NOT, AND, and OR modules in Verilog. You should write these “gates” as modules and use them later in your implementations. In other words, for example, when you need to apply an AND operation to two input wires, you should use the modules you have written before, rather than using operators like “&amp;” or “|” directly. Following the implementation, please run simulations for various input combinations to validate your design.

<h1>Part 2</h1>

Please implement the circuit that you have designed in Preliminary 1.e. section using only NAND modules in Verilog. You should implement the gate as a module and use it later in your implementations. Following the implementation, please run simulations for various input combinations to validate your design.

<h1>Part 3</h1>

Please implement the circuit that you have designed in Preliminary 1.f. section using a

8:1 multiplexer and NOT gates in Verilog. You should write the multiplexer and NOT gate as modules and use them later in your implementations. Following the implementation, please run simulations for various input combinations to validate your design.

<h1>Part 4</h1>

Please implement the circuit that you have designed in Preliminary 2 section using a 3:8 decoder and OR gates in Verilog. You should write the decoder and OR gate as modules and use them later in your implementations. Following the implementation, please run simulations for various input combinations to validate your design.

<h1>4 Report</h1>

You should show your work of Preliminary study on the report in detail. You can use any tool for creating tables (for Preliminary 1.a., 1.b. and 1.c.) and circuit designs (for Preliminary 1.d., 1.e. and 1.f.). You may attach them to the report as figures by properly referencing them in the text.

Your report should also contain information about the results of your simulations. If your implementations are not fully correct, discuss what the source of the errors might

2

be in your report.