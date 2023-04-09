---
keywords: fastai
description: Vocab from weeks 13-16 (Unit 3 presentations)
title: Unit 3 Vocab
layout: default
comments: true
toc: true
permalink: /vocabulary
categories: [Student Teaching Portfolio]
nb_path: _notebooks/2022-12-16-studentTeachingVocab.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-12-16-studentTeachingVocab.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Definitions">Definitions<a class="anchor-link" href="#Definitions"> </a></h1><table>
<thead><tr>
<th>Term</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>Algorithm</td>
<td>At its core, an algorithm is really just a generalized, conceptual solution to a problem that can later be implemented in some real-world form like a computer program.</td>
</tr>
<tr>
<td>Application Program Interface</td>
<td>Application program interface (API) is a set of routines, protocols, and tools for constructing software applications. An API specifies how software components should interact. In addition, APIs are used when programming graphical user interface (GUI) components.</td>
</tr>
<tr>
<td>Binary</td>
<td>A numeric system of base 2 that only uses combinations of the digits zero and one; this is used in one of the lowest levels of abstraction. Computers operate in binary, as they store data and perform calculations using only zeros and ones. While a single binary digit can be used to represent True (1) or False (0) in boolean logic, multiple binary digits can be used in conjunction to store large numbers and perform complex functions. Computers translate between binary and what you actually work with such as numbers and text.</td>
</tr>
<tr>
<td>Binary Search</td>
<td>A search algorithm that locates the position of a target value within a sorted array by repeatedly dividing the search interval in half; can only be used when the list is sorted. Because of its divide-and-conquer approach, the amount of work required to find an item grows much more slowly with Binary Search than with Sequential Search. In fact, with this logarithmic behavior</td>
</tr>
<tr>
<td>Boolean Function*</td>
<td>Any function based on the operations AND, OR, and NOT, and whose elements are from the domain of Boolean algebra. A function whose arguments, as well as the function itself, assume values from a two-element set (usually {0,1}) Central Processing Unit CPU, or processor, is the brains of the computer where most calculations take place. Contains the circuitry necessary to interpret and execute program instructions.</td>
</tr>
<tr>
<td>Computational Artifact</td>
<td>Something created by a human using a computer and can be, but is not limited to, a program, an image, an audio, a video, a presentation, or web page file</td>
</tr>
<tr>
<td>Cryptography</td>
<td>The science of coding and decoding messages in order to keep them secure. Coding takes place using a key that ideally is known only by the sender and intended recipient of the message.</td>
</tr>
<tr>
<td>Floating Point Numbers</td>
<td>As the name implies, floating point numbers are numbers that contain floating decimal points. Examples include, the numbers 5.5, 0.001, and -2,345.6789. Numbers without decimal places are called integers. Computers recognize real numbers that contain fractions as floating point numbers.</td>
</tr>
<tr>
<td>Hexadecimal</td>
<td>Hexadecimal describes a base-16 number system. That is, it describes a numbering system containing 16 sequential numbers as base units (including 0) before adding a new position for the next number. The hexadecimal numbers are 0-9 and then use the letters A-F. Used to represent digital data because it utilizes fewer digits than binary.</td>
</tr>
<tr>
<td>Integers</td>
<td>An integer is a whole number (not a fraction) that can be positive, negative, or zero. In computer science, an integer is a datum of integral data type, a data type that represents some finite subset of the mathematical integers. Integral data types may be of different sizes and may or may not be allowed to contain negative values.</td>
</tr>
<tr>
<td>Iterations</td>
<td>Iteration is the repetition of part of an algorithm until a condition is met or for a specified number of times. This is often called a ‘loop’. Recursive functions repeatedly execute themselves as part of their operation. Upon completing all instructions and resetting to the first one iteration has been completed.</td>
</tr>
<tr>
<td>Libraries</td>
<td>In computer science, a library is a collection of non-volatile resources that a program can use often to develop software. Libraries are particularly useful for storing frequently used routines because you do not need to explicitly link them to every program that uses them. The linker automatically looks in libraries for routines that it does not find elsewhere. Resources which may be found in libraries include data, documentation, message templates, pre-written code, classes, or values.</td>
</tr>
<tr>
<td>Linear/Sequential Search</td>
<td>A process that checks every element in the list sequentially until the desired element is found or all elements have been searched. Can be used in any type of list. Has linear performance.</td>
</tr>
<tr>
<td>Lossless Data Compression</td>
<td>With lossless compression, every single bit of data that was originally in the file remains after the file is uncompressed. All of the information is completely restored. This is generally the technique of choice for text or spreadsheet files, where the loss of words or financial data could pose a problem. PNG is an image format that provides lossless compression.</td>
</tr>
<tr>
<td>Lossy Data Compression</td>
<td>Lossy compression reduces a file by permanently eliminating certain information, especially redundant information. When the file is uncompressed, only a part of the original information is still there (although the user may not notice it). Lossy compression is generally used for video and sound, where a certain amount of information loss will not be detected by most users. JPEG provides lossy compression.</td>
</tr>
<tr>
<td>Metadata</td>
<td>Metadata is data that describes other data. Metadata summarizes basic information about data, which can make finding and working with particular instances of data easier. It provides information concerning an item’s content such as image resolution and size.</td>
</tr>
<tr>
<td>Pseudocode</td>
<td>Pseudocode is a detailed yet readable description of what a computer program or algorithm must do. It may also describe an operating principle. It is expressed in a formally-styled natural language rather than in a programming language intended for humans. The conventions of normal programming continue.</td>
</tr>
<tr>
<td>Sequencing</td>
<td>The execution of each step/action of an algorithm in the precise order in which the statements are given.</td>
</tr>
</tbody>
</table>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Code-Examples">Code Examples<a class="anchor-link" href="#Code-Examples"> </a></h1><p>Algorithm + binary:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># converts decimal to binary</span>

<span class="k">def</span> <span class="nf">decimal_to_binary</span><span class="p">(</span><span class="n">num</span><span class="p">):</span>
  <span class="c1"># Create an empty list to store the binary digits</span>
  <span class="n">binary_digits</span> <span class="o">=</span> <span class="p">[]</span>

  <span class="c1"># Create a loop that continues until the number is zero</span>
  <span class="k">while</span> <span class="n">num</span> <span class="o">&gt;</span> <span class="mi">0</span><span class="p">:</span>
    <span class="c1"># Use the modulo operator to find the remainder when the number is divided by 2</span>
    <span class="n">remainder</span> <span class="o">=</span> <span class="n">num</span> <span class="o">%</span> <span class="mi">2</span>

    <span class="c1"># Divide the number by 2 and store the result in the same variable</span>
    <span class="n">num</span> <span class="o">=</span> <span class="n">num</span> <span class="o">//</span> <span class="mi">2</span>

    <span class="c1"># Insert the remainder at the beginning of the list</span>
    <span class="n">binary_digits</span><span class="o">.</span><span class="n">insert</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span> <span class="n">remainder</span><span class="p">)</span>

  <span class="c1"># Return the list of binary digits as a string</span>
  <span class="k">return</span> <span class="s2">&quot;&quot;</span><span class="o">.</span><span class="n">join</span><span class="p">([</span><span class="nb">str</span><span class="p">(</span><span class="n">x</span><span class="p">)</span> <span class="k">for</span> <span class="n">x</span> <span class="ow">in</span> <span class="n">binary_digits</span><span class="p">])</span>


<span class="c1"># calling the code</span>
<span class="n">decimal_num</span> <span class="o">=</span> <span class="mi">14</span>
<span class="n">binary_num</span> <span class="o">=</span> <span class="n">decimal_to_binary</span><span class="p">(</span><span class="n">decimal_num</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">binary_num</span><span class="p">)</span> <span class="c1"># Output: 1110</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>1110
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Binary search:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Binary search</span>

<span class="k">def</span> <span class="nf">binary_search</span><span class="p">(</span><span class="n">arr</span><span class="p">,</span> <span class="n">target</span><span class="p">):</span>
  <span class="c1"># Set the initial bounds of the search area</span>
  <span class="n">low</span> <span class="o">=</span> <span class="mi">0</span>
  <span class="n">high</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">arr</span><span class="p">)</span> <span class="o">-</span> <span class="mi">1</span>

  <span class="c1"># Continue searching until the bounds are the same or cross each other</span>
  <span class="k">while</span> <span class="n">low</span> <span class="o">&lt;=</span> <span class="n">high</span><span class="p">:</span>
    <span class="c1"># Find the midpoint of the search area</span>
    <span class="n">mid</span> <span class="o">=</span> <span class="p">(</span><span class="n">low</span> <span class="o">+</span> <span class="n">high</span><span class="p">)</span> <span class="o">//</span> <span class="mi">2</span>

    <span class="c1"># Check if the target is the midpoint</span>
    <span class="k">if</span> <span class="n">arr</span><span class="p">[</span><span class="n">mid</span><span class="p">]</span> <span class="o">==</span> <span class="n">target</span><span class="p">:</span>
      <span class="k">return</span> <span class="n">mid</span>

    <span class="c1"># If the target is greater than the midpoint, narrow the search area to the right</span>
    <span class="k">elif</span> <span class="n">arr</span><span class="p">[</span><span class="n">mid</span><span class="p">]</span> <span class="o">&lt;</span> <span class="n">target</span><span class="p">:</span>
      <span class="n">low</span> <span class="o">=</span> <span class="n">mid</span> <span class="o">+</span> <span class="mi">1</span>

    <span class="c1"># If the target is less than the midpoint, narrow the search area to the left</span>
    <span class="k">else</span><span class="p">:</span>
      <span class="n">high</span> <span class="o">=</span> <span class="n">mid</span> <span class="o">-</span> <span class="mi">1</span>

  <span class="c1"># If the target was not found, return -1</span>
  <span class="k">return</span> <span class="o">-</span><span class="mi">1</span>

<span class="c1"># calling the code</span>
<span class="n">arr</span> <span class="o">=</span> <span class="p">[</span><span class="mi">1</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">7</span><span class="p">,</span> <span class="mi">9</span><span class="p">,</span> <span class="mi">11</span><span class="p">,</span> <span class="mi">13</span><span class="p">,</span> <span class="mi">15</span><span class="p">]</span>
<span class="n">target</span> <span class="o">=</span> <span class="mi">7</span>
<span class="n">index</span> <span class="o">=</span> <span class="n">binary_search</span><span class="p">(</span><span class="n">arr</span><span class="p">,</span> <span class="n">target</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">index</span><span class="p">)</span> <span class="c1"># Output: 3</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>3
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Boolean function:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Is the number even or odd? (using Boolean)</span>


<span class="n">num</span> <span class="o">=</span> <span class="mi">7</span>

<span class="k">def</span> <span class="nf">is_even</span><span class="p">(</span><span class="n">num</span><span class="p">):</span>
  <span class="k">if</span> <span class="n">num</span> <span class="o">%</span> <span class="mi">2</span> <span class="o">==</span> <span class="mi">0</span><span class="p">:</span>
    <span class="k">return</span> <span class="kc">True</span>
  <span class="k">else</span><span class="p">:</span>
    <span class="k">return</span> <span class="kc">False</span>

<span class="k">if</span> <span class="n">is_even</span><span class="p">(</span><span class="n">num</span><span class="p">):</span>
  <span class="nb">print</span><span class="p">(</span><span class="n">num</span><span class="p">,</span> <span class="s2">&quot;is even.&quot;</span><span class="p">)</span>
<span class="k">else</span><span class="p">:</span>
  <span class="nb">print</span><span class="p">(</span><span class="n">num</span><span class="p">,</span> <span class="s2">&quot;is odd.&quot;</span><span class="p">)</span>


<span class="n">result</span> <span class="o">=</span> <span class="n">is_even</span><span class="p">(</span><span class="n">num</span><span class="p">)</span> <span class="c1"># Output: Boolean value (true for even, false for odd)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">result</span><span class="p">)</span> <span class="c1"># Output: False</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>7 is odd.
False
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Computer Artifact:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Calculates factorial of a given number</span>

<span class="k">def</span> <span class="nf">factorial</span><span class="p">(</span><span class="n">n</span><span class="p">):</span>
  <span class="k">if</span> <span class="n">n</span> <span class="o">==</span> <span class="mi">0</span><span class="p">:</span>
    <span class="k">return</span> <span class="mi">1</span>
  <span class="k">else</span><span class="p">:</span>
    <span class="k">return</span> <span class="n">n</span> <span class="o">*</span> <span class="n">factorial</span><span class="p">(</span><span class="n">n</span><span class="o">-</span><span class="mi">1</span><span class="p">)</span>

<span class="n">result</span> <span class="o">=</span> <span class="n">factorial</span><span class="p">(</span><span class="mi">5</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">result</span><span class="p">)</span>  <span class="c1"># prints 120</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>120
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Floating point numbers:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">a</span> <span class="o">=</span> <span class="mf">3.14</span>
<span class="n">b</span> <span class="o">=</span> <span class="mf">1.0</span>

<span class="c1"># perform some arithmetic operations on the numbers</span>
<span class="n">c</span> <span class="o">=</span> <span class="n">a</span> <span class="o">+</span> <span class="n">b</span>  <span class="c1"># c is 4.14</span>
<span class="n">d</span> <span class="o">=</span> <span class="n">a</span> <span class="o">*</span> <span class="n">b</span>  <span class="c1"># d is 3.14</span>
<span class="n">e</span> <span class="o">=</span> <span class="n">a</span> <span class="o">/</span> <span class="n">b</span>  <span class="c1"># e is 3.14</span>

<span class="c1"># c, d, and e are also floating point numbers</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Hexadecimal:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">decimal_num</span> <span class="o">=</span> <span class="mi">59302</span>

<span class="c1"># convert the decimal number to hexadecimal</span>
<span class="n">hex_num</span> <span class="o">=</span> <span class="nb">hex</span><span class="p">(</span><span class="n">decimal_num</span><span class="p">)</span>

<span class="c1"># print the hexadecimal number</span>
<span class="nb">print</span><span class="p">(</span><span class="n">hex_num</span><span class="p">)</span>  <span class="c1"># prints &quot;0xe7a6&quot;</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>0xe7a6
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Integers, iterations, and libraries:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">math</span>

<span class="k">def</span> <span class="nf">sum_of_squares</span><span class="p">(</span><span class="n">n</span><span class="p">):</span>
  <span class="c1"># initialize the sum to 0</span>
  <span class="nb">sum</span> <span class="o">=</span> <span class="mi">0</span>

  <span class="c1"># iterate over the first n positive integers</span>
  <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="n">n</span><span class="o">+</span><span class="mi">1</span><span class="p">):</span>
    <span class="c1"># add the square of the current integer to the sum</span>
    <span class="nb">sum</span> <span class="o">+=</span> <span class="n">math</span><span class="o">.</span><span class="n">pow</span><span class="p">(</span><span class="n">i</span><span class="p">,</span> <span class="mi">2</span><span class="p">)</span>

  <span class="c1"># return the sum</span>
  <span class="k">return</span> <span class="nb">sum</span>

<span class="n">result</span> <span class="o">=</span> <span class="n">sum_of_squares</span><span class="p">(</span><span class="mi">5</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="nb">round</span><span class="p">(</span><span class="n">result</span><span class="p">))</span>  <span class="c1"># prints 55</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>55
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Linear/Sequential Search:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">linear_search</span><span class="p">(</span><span class="n">numbers</span><span class="p">,</span> <span class="n">target</span><span class="p">):</span>
  <span class="c1"># iterate over the numbers in the list</span>
  <span class="k">for</span> <span class="n">number</span> <span class="ow">in</span> <span class="n">numbers</span><span class="p">:</span>
    <span class="c1"># if the current number is the target, return True</span>
    <span class="k">if</span> <span class="n">number</span> <span class="o">==</span> <span class="n">target</span><span class="p">:</span>
      <span class="k">return</span> <span class="kc">True</span>

  <span class="c1"># if the target was not found, return False</span>
  <span class="k">return</span> <span class="kc">False</span>

<span class="n">numbers</span> <span class="o">=</span> <span class="p">[</span><span class="mi">1</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">4</span><span class="p">,</span> <span class="mi">5</span><span class="p">]</span>
<span class="n">target</span> <span class="o">=</span> <span class="mi">3</span>
<span class="n">result</span> <span class="o">=</span> <span class="n">linear_search</span><span class="p">(</span><span class="n">numbers</span><span class="p">,</span> <span class="n">target</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">result</span><span class="p">)</span>  <span class="c1"># prints True</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>True
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Lossless data compression:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">zlib</span>

<span class="c1"># define the string to compress</span>
<span class="n">data</span> <span class="o">=</span> <span class="s2">&quot;Hello, world! This is a test of the data compression algorithm.&quot;</span>

<span class="c1"># compress the string</span>
<span class="n">compressed_data</span> <span class="o">=</span> <span class="n">zlib</span><span class="o">.</span><span class="n">compress</span><span class="p">(</span><span class="n">data</span><span class="o">.</span><span class="n">encode</span><span class="p">(</span><span class="s2">&quot;utf-8&quot;</span><span class="p">))</span>

<span class="c1"># print the compressed data</span>
<span class="nb">print</span><span class="p">(</span><span class="n">compressed_data</span><span class="p">)</span>  <span class="c1"># prints a byte sequence representing the compressed data</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>b&#39;x\x9c\r\xc2\xd1\t\x800\x0c\x05\xc0U\x9e\xff\xe2\x1c\x0e\xe0\x02\xc1FSH\xfb$\t\xb8\xbe\x1e\xb7\xab;W\xbc\x0co\x0b\x0e\xeb\x89\xbf\xa04\x0b\xbcP\xa6hR\x82\x93\xe3\t\xcd\xec\x9c\x10\xbf\x19\xbdll\x1f\xbcW\x16\x96&#39;
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">decompressed_data</span> <span class="o">=</span> <span class="n">zlib</span><span class="o">.</span><span class="n">decompress</span><span class="p">(</span><span class="n">compressed_data</span><span class="p">)</span>

<span class="c1"># print the decompressed data</span>
<span class="nb">print</span><span class="p">(</span><span class="n">decompressed_data</span><span class="o">.</span><span class="n">decode</span><span class="p">(</span><span class="s2">&quot;utf-8&quot;</span><span class="p">))</span>  <span class="c1"># prints &quot;Hello, world! This is a test of the data compression algorithm.&quot;</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Hello, world! This is a test of the data compression algorithm.
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Metadata:</p>
<p>front matter is a form of metadata. This is what front matter for Fastpages looks like in html</p>
<p>toc: true <br>
layout: post <br>
description: Description here! <br>
image: /images/image.jpg <br>
categories: [tag] <br>
title: Type the title here! <br>
permalink: /example <br></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Pseudocode:</p>
<p><img src="/fastpages-project/images/copied_from_nb/../images/pseudocode.jpg" alt="pseudocode example"></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Sequencing:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">numbers</span> <span class="o">=</span> <span class="p">[</span><span class="mi">3</span><span class="p">,</span> <span class="mi">1</span><span class="p">,</span> <span class="mi">4</span><span class="p">,</span> <span class="mi">1</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">9</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">6</span><span class="p">]</span>

<span class="c1"># create an empty list for the sequenced numbers</span>
<span class="n">sequenced_numbers</span> <span class="o">=</span> <span class="p">[]</span>

<span class="c1"># iterate over the numbers in the list</span>
<span class="k">for</span> <span class="n">number</span> <span class="ow">in</span> <span class="n">numbers</span><span class="p">:</span>
  <span class="c1"># append the current number to the sequenced numbers list</span>
  <span class="n">sequenced_numbers</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">number</span><span class="p">)</span>

<span class="c1"># print the sequenced numbers</span>
<span class="nb">print</span><span class="p">(</span><span class="n">sequenced_numbers</span><span class="p">)</span>  <span class="c1"># prints [3, 1, 4, 1, 5, 9, 2, 6]</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[3, 1, 4, 1, 5, 9, 2, 6]
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 
