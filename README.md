# csc3050-project-3-solved
**TO GET THIS SOLUTION VISIT:** [CSC3050 Project 3 Solved](https://www.ankitcodinghub.com/product/csc3050-program-3-instruction-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117526&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC3050 Project 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Overview

In the class, the teacher introduced the Arithmetic and Logic Unit(ALU) to us. This module is to do math co-processing. In this program, we will use verilog to complete it. I will give you examples of verilog module file and testing file. You should add other operations into the code file and analyze the result.

Block Diagram

In the diagram, we also have test bench. In the CPU, we should get information from the instruction and find the data flow of each instruction. However, in the ALU module, the input is sometimes not only rely on the instructions. Therefore, the test bench should also contain the value of relevant registers.

The ALU must support:

– add, addi, addu, addiu

– sub, subu

– mult, multu, div, divu

– and, andi, nor, or, ori, xor, xori

– beq, bne, slt, slti, sltiu, sltu

– lw, sw

– sll, sllv, srl, srlv, sra, srav

I will give you the example of sll.

From test bench to the register, with different kind of instructions, we should send different thing to the ALU module. You should at least show me the value of these registers in the diagram. You can also display other important value in your own data flow and explain it in your report. I will check the value with my test cases.

You should handle at least two verilog file:

– ALU.v

– test_ALU.v

And your project report.

Because maybe some of you will use other modules(adder, etc.), you can handle more than two verilog file. However, I will modify your test file with my own code to test your file.

I will give you example test bench and you should extend the test bench by yourself and analyze the final result in your report.

Grading

Support the Arithmetic/Logic operations – 60%

– Basic operations with value of general registers

– Load and store

– Special operations with other registers (multiplication with Hi, Lo, etc.)

With a clear data flow from instruction to ALU – 20%

– Control part

– Sign extension – Zero extension

With special handling for flags – 10%

– negative flag

– Zero flag

– Overflow detection

Project report – 10%
