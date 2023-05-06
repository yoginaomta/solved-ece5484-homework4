Download Link: https://assignmentchef.com/product/solved-ece5484-homework4
<br>
<ol>

 <li>Consider the MARIE program below.

  <ol>

   <li>List the hexadecimal code for <em><sub>each line </sub></em>of the program (including the symbols).</li>

   <li>Draw the symbol table.</li>

   <li>What is the value stored in the AC when the program terminates?</li>

  </ol></li>

</ol>

ORG 100

Begin, LOAD Base ADD Offs

<table width="139">

 <tbody>

  <tr>

   <td width="56">Loop,</td>

   <td width="84">SUBT TwoSTORE AddrSKIPCOND 800JUMP Done CLEARLOAD Offs</td>

  </tr>

  <tr>

   <td width="56">Done,</td>

   <td width="84">HALT</td>

  </tr>

  <tr>

   <td width="56">Base,</td>

   <td width="84">HEX 200</td>

  </tr>

  <tr>

   <td width="56">Offs,</td>

   <td width="84">DEC 11</td>

  </tr>

  <tr>

   <td width="56">Two,</td>

   <td width="84">HEX 0002</td>

  </tr>

  <tr>

   <td width="56">Addr,</td>

   <td width="84">HEX 007</td>

  </tr>

 </tbody>

</table>

<ol start="2">

 <li>Write the assembly language equivalent of the following MARIE machine language instructions:

  <ol>

   <li>0100 0001 1000 0101</li>

   <li>1000 0100 0000 0000</li>

   <li>0111 0000 0000 0000</li>

  </ol></li>

</ol>

<em>Homework 4</em>

<ol start="3">

 <li>Write the following code segment in MARIE’s assembly language:</li>

</ol>

if X &lt; 1 then

Y = X – 2;

<ul>

 <li>= 0;</li>

</ul>

endif;

<ul>

 <li>= Y + 7;</li>

</ul>

<ol start="4">

 <li>Fill in the following table to show how the given integers are represented, assuming 16-bits are used to store values and the machine uses 2’s complement notation.</li>

</ol>

<table width="544">

 <tbody>

  <tr>

   <td width="118">Integer</td>

   <td width="105">Binary</td>

   <td width="201">2 Byte Big Endian(hex value as seen inHex                           memory)</td>

   <td width="120">2 Byte Little Endian(hex value as seen in memory)</td>

  </tr>

  <tr>

   <td width="118">71329-7-2710931307</td>

   <td width="105"> </td>

   <td width="201"> </td>

   <td width="120"> </td>

  </tr>

 </tbody>

</table>

<ol start="5">

 <li>Suppose we have the instruction Load 600. Given memory and register R1 contain the values below and assuming R1 is implied in the indexed addressing mode, determine the actual value loaded into the accumulator and fill in the table below:</li>

</ol>

<table width="309">

 <tbody>

  <tr>

   <td width="153">Mode</td>

   <td width="156">Value loaded into AC</td>

  </tr>

  <tr>

   <td width="153">ImmediateDirectIndirectIndexed</td>

   <td width="156"> </td>

  </tr>

 </tbody>

</table>

<ol start="6">

 <li>Suppose an instruction takes four cycles to execute in a nonpipelined CPU: one cycle to fetch the instruction, one cycle to decode the instruction, one cycle to perform the ALU operation, and one cycle to store the result. In a CPU with a 4-stage pipeline, that instruction still takes four cycles to execute, so how can we say the pipeline speeds up the execution of the program?</li>

 <li><strong><sub>Scavenger Hunt: </sub></strong>John Cocke and David Patterson made significant contributions to Reduced <em>Homework 4</em></li>

</ol>

Instruction Set Computer (RISC) architectures. <em>Answer the following questions separately for each of</em>

<em>these two individuals. </em>Cite the sources you used to find your answers. Your entire answer should be one page or less.

<ol>

 <li>In your own words, what was his contribution to RISC architectures? Try to be specific.</li>

</ol>