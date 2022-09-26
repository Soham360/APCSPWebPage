---
keywords: fastai
title: Python Lists and dictionaires Post
toc: true
comments: true
categories: [Week_2]
nb_path: _notebooks/2022-08-29-python_lists.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-08-29-python_lists.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="InfoDb">InfoDb<a class="anchor-link" href="#InfoDb"> </a></h2><p>InfoDb is a dictionary inside of a list. Here is an example code using InfoDb:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">InfoDb</span> <span class="o">=</span> <span class="p">[]</span>

<span class="c1"># Append to List a Dictionary of key/values related to a person and cars</span>
<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;John&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Mortensen&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;October 21&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;San Diego&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;jmortensen@powayusd.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;2015-Fusion&quot;</span><span class="p">,</span> <span class="s2">&quot;2011-Ranger&quot;</span><span class="p">,</span> <span class="s2">&quot;2003-Excursion&quot;</span><span class="p">,</span> <span class="s2">&quot;1997-F350&quot;</span><span class="p">,</span> <span class="s2">&quot;1969-Cadillac&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="c1"># Append to List a 2nd Dictionary of key/values</span>
<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Sunny&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Naidu&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;August 2&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;Temecula&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;snaidu@powayusd.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;4Runner&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Ryan&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Hakimipour&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;June 15&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;San Diego&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;hakimipourryan@gmail.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;None&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Soham&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Kamat&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;March 9&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;San Diego&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;sohamk10039@stu.powayusd.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;None&quot;</span><span class="p">]</span>
<span class="p">})</span>
<span class="c1"># Print the data structure</span>
<span class="nb">print</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[{&#39;FirstName&#39;: &#39;John&#39;, &#39;LastName&#39;: &#39;Mortensen&#39;, &#39;DOB&#39;: &#39;October 21&#39;, &#39;Residence&#39;: &#39;San Diego&#39;, &#39;Email&#39;: &#39;jmortensen@powayusd.com&#39;, &#39;Owns_Cars&#39;: [&#39;2015-Fusion&#39;, &#39;2011-Ranger&#39;, &#39;2003-Excursion&#39;, &#39;1997-F350&#39;, &#39;1969-Cadillac&#39;]}, {&#39;FirstName&#39;: &#39;Sunny&#39;, &#39;LastName&#39;: &#39;Naidu&#39;, &#39;DOB&#39;: &#39;August 2&#39;, &#39;Residence&#39;: &#39;Temecula&#39;, &#39;Email&#39;: &#39;snaidu@powayusd.com&#39;, &#39;Owns_Cars&#39;: [&#39;4Runner&#39;]}, {&#39;FirstName&#39;: &#39;Ryan&#39;, &#39;LastName&#39;: &#39;Hakimipour&#39;, &#39;DOB&#39;: &#39;June 15&#39;, &#39;Residence&#39;: &#39;San Diego&#39;, &#39;Email&#39;: &#39;hakimipourryan@gmail.com&#39;, &#39;Owns_Cars&#39;: [&#39;None&#39;]}, {&#39;FirstName&#39;: &#39;Soham&#39;, &#39;LastName&#39;: &#39;Kamat&#39;, &#39;DOB&#39;: &#39;March 9&#39;, &#39;Residence&#39;: &#39;San Diego&#39;, &#39;Email&#39;: &#39;sohamk10039@stu.powayusd.com&#39;, &#39;Owns_Cars&#39;: [&#39;None&#39;]}]
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="For-Loops-and-Index">For Loops and Index<a class="anchor-link" href="#For-Loops-and-Index"> </a></h2><p>Using <code>for loops</code> and iterating through using <code>index</code> in python. Here is a simple example:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">Food</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Burger&quot;</span><span class="p">,</span> <span class="s2">&quot;Hot Dog&quot;</span><span class="p">,</span> <span class="s2">&quot;Fries&quot;</span><span class="p">,</span> <span class="s2">&quot;Pizza&quot;</span><span class="p">,</span> <span class="s2">&quot;Goldfish&quot;</span><span class="p">,</span> <span class="s2">&quot;Donut&quot;</span><span class="p">,</span> <span class="s2">&quot;M&amp;M&quot;</span><span class="p">,</span> <span class="s2">&quot;Beef Kebab&quot;</span><span class="p">,</span> <span class="s2">&quot;Chicken Kebab&quot;</span><span class="p">,</span> <span class="s2">&quot;Burrito&quot;</span><span class="p">,</span> <span class="s2">&quot;Tacos&quot;</span><span class="p">,</span> <span class="s2">&quot;Chicken Sandwich&quot;</span><span class="p">]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">Food</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">i</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Burger
Hot Dog
Fries
Pizza
Goldfish
Donut
M&amp;M
Beef Kebab
Chicken Kebab
Burrito
Tacos
Chicken Sandwich
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Outputting-in-Reverse-Order">Outputting in Reverse Order<a class="anchor-link" href="#Outputting-in-Reverse-Order"> </a></h2><p>It is possible to output data in a reverse order. Here is an example using a palindrome:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">is_palindrome</span><span class="p">(</span><span class="n">prompt</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">prompt</span><span class="p">[::</span><span class="o">-</span><span class="mi">1</span><span class="p">])</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">prompt</span><span class="p">)</span>
    <span class="k">return</span> <span class="n">prompt</span><span class="p">[::</span><span class="o">-</span><span class="mi">1</span><span class="p">]</span> <span class="o">==</span> <span class="n">prompt</span>

<span class="n">word</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s2">&quot;Enter a word: &quot;</span><span class="p">)</span>
<span class="k">if</span> <span class="n">is_palindrome</span><span class="p">(</span><span class="n">word</span><span class="o">.</span><span class="n">lower</span><span class="p">())</span> <span class="ow">is</span> <span class="kc">True</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="si">{0}</span><span class="s2"> is a palindrome!&quot;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">word</span><span class="p">))</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;The provided word is not a palindrome.&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>olleh
hello
The provided word is not a palindrome.
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Other-list-methods">Other list methods<a class="anchor-link" href="#Other-list-methods"> </a></h2><p>Lists can have a variety of methods performed on them. A couple being <code>.append()</code> or <code>while loop</code>. Here is an example using <code>.append()</code> and <code>.lower()</code> with a <code>for loop</code>:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">Dangerous_Animals</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Box Jellyfish&quot;</span><span class="p">,</span> <span class="s2">&quot;African CAPE BuFfalo&quot;</span><span class="p">,</span> <span class="s2">&quot;BLAck MambA&quot;</span><span class="p">,</span> <span class="s2">&quot;Blue-RINGED octopus&quot;</span><span class="p">]</span>
<span class="n">Dangerous_Animals</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="s2">&quot;Cone SnAIl&quot;</span><span class="p">)</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">Dangerous_Animals</span><span class="p">)):</span>
    <span class="n">Dangerous_Animals</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">=</span> <span class="n">Dangerous_Animals</span><span class="p">[</span><span class="n">i</span><span class="p">]</span><span class="o">.</span><span class="n">lower</span><span class="p">()</span>
<span class="nb">print</span><span class="p">(</span><span class="n">Dangerous_Animals</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[&#39;box jellyfish&#39;, &#39;african cape buffalo&#39;, &#39;black mamba&#39;, &#39;blue-ringed octopus&#39;, &#39;cone snail&#39;]
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Adding-to-a-Dictionary">Adding to a Dictionary<a class="anchor-link" href="#Adding-to-a-Dictionary"> </a></h2><p>You can also add or create new keys and values to a dictionary data set. This can also be done with input. Here is an example:</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">My_Dict</span> <span class="o">=</span> <span class="p">{</span>
    <span class="s2">&quot;Absence&quot;</span><span class="p">:</span> <span class="s2">&quot;The lack or unavailability of something or someone.&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Approval&quot;</span><span class="p">:</span> <span class="s2">&quot;Having a positive opinion of something or someone.&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Answer&quot;</span><span class="p">:</span> <span class="s2">&quot;The response or receipt to a phone call, question, or letter.&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Attention&quot;</span><span class="p">:</span> <span class="s2">&quot;Noticing or recognizing something of interest.&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Amount&quot;</span><span class="p">:</span> <span class="s2">&quot;A mass or a collection of something.&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Borrow&quot;</span><span class="p">:</span> <span class="s2">&quot;To take something with the intention of returning it after a period of time.&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Baffle&quot;</span><span class="p">:</span> <span class="s2">&quot;An event or thing that is a mystery and confuses.&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Ban&quot;</span><span class="p">:</span> <span class="s2">&quot;An act that is prohibited by social pressure or law.&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Cars&quot;</span><span class="p">:</span> <span class="s2">&quot;Four-wheeled vehicles used for traveling.&quot;</span><span class="p">,</span>
<span class="p">}</span>
<span class="nb">print</span><span class="p">(</span><span class="n">My_Dict</span><span class="p">)</span>
<span class="n">My_Dict</span><span class="p">[</span><span class="s2">&quot;Care&quot;</span><span class="p">]</span> <span class="o">=</span> <span class="s2">&quot;extra responsibility and attention.&quot;</span> <span class="c1">#Added new key and value into dictionary</span>
<span class="nb">print</span><span class="p">(</span><span class="n">My_Dict</span><span class="p">)</span>
<span class="n">My_Dict</span><span class="p">[</span><span class="s2">&quot;Chip&quot;</span><span class="p">]</span> <span class="o">=</span> <span class="nb">input</span><span class="p">()</span> <span class="c1"># Added new value with input</span>
<span class="nb">print</span><span class="p">(</span><span class="n">My_Dict</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>{&#39;Absence&#39;: &#39;The lack or unavailability of something or someone.&#39;, &#39;Approval&#39;: &#39;Having a positive opinion of something or someone.&#39;, &#39;Answer&#39;: &#39;The response or receipt to a phone call, question, or letter.&#39;, &#39;Attention&#39;: &#39;Noticing or recognizing something of interest.&#39;, &#39;Amount&#39;: &#39;A mass or a collection of something.&#39;, &#39;Borrow&#39;: &#39;To take something with the intention of returning it after a period of time.&#39;, &#39;Baffle&#39;: &#39;An event or thing that is a mystery and confuses.&#39;, &#39;Ban&#39;: &#39;An act that is prohibited by social pressure or law.&#39;, &#39;Cars&#39;: &#39;Four-wheeled vehicles used for traveling.&#39;}
{&#39;Absence&#39;: &#39;The lack or unavailability of something or someone.&#39;, &#39;Approval&#39;: &#39;Having a positive opinion of something or someone.&#39;, &#39;Answer&#39;: &#39;The response or receipt to a phone call, question, or letter.&#39;, &#39;Attention&#39;: &#39;Noticing or recognizing something of interest.&#39;, &#39;Amount&#39;: &#39;A mass or a collection of something.&#39;, &#39;Borrow&#39;: &#39;To take something with the intention of returning it after a period of time.&#39;, &#39;Baffle&#39;: &#39;An event or thing that is a mystery and confuses.&#39;, &#39;Ban&#39;: &#39;An act that is prohibited by social pressure or law.&#39;, &#39;Cars&#39;: &#39;Four-wheeled vehicles used for traveling.&#39;, &#39;Care&#39;: &#39;extra responsibility and attention.&#39;}
{&#39;Absence&#39;: &#39;The lack or unavailability of something or someone.&#39;, &#39;Approval&#39;: &#39;Having a positive opinion of something or someone.&#39;, &#39;Answer&#39;: &#39;The response or receipt to a phone call, question, or letter.&#39;, &#39;Attention&#39;: &#39;Noticing or recognizing something of interest.&#39;, &#39;Amount&#39;: &#39;A mass or a collection of something.&#39;, &#39;Borrow&#39;: &#39;To take something with the intention of returning it after a period of time.&#39;, &#39;Baffle&#39;: &#39;An event or thing that is a mystery and confuses.&#39;, &#39;Ban&#39;: &#39;An act that is prohibited by social pressure or law.&#39;, &#39;Cars&#39;: &#39;Four-wheeled vehicles used for traveling.&#39;, &#39;Care&#39;: &#39;extra responsibility and attention.&#39;, &#39;Chip&#39;: &#39;Absence&#39;}
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Python-Quiz">Python Quiz<a class="anchor-link" href="#Python-Quiz"> </a></h2><p>Making a quiz that uses a list of dictionaries (InfoDb):</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">Python_Quiz</span><span class="p">(</span><span class="n">prompt</span><span class="p">):</span>
    <span class="k">global</span> <span class="n">word</span>
    <span class="nb">print</span> <span class="p">(</span><span class="s2">&quot;Question: &quot;</span> <span class="o">+</span> <span class="n">prompt</span><span class="p">)</span>
    <span class="n">word</span> <span class="o">=</span> <span class="nb">input</span><span class="p">()</span>
    <span class="k">return</span> <span class="n">word</span>

<span class="n">questions_number</span> <span class="o">=</span> <span class="mi">5</span>
<span class="n">correct_answer</span> <span class="o">=</span> <span class="mi">0</span>

<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Hello, you will be asked &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">questions_number</span><span class="p">)</span> <span class="o">+</span> <span class="s2">&quot; short questions&quot;</span><span class="p">)</span>

<span class="n">My_Quiz</span> <span class="o">=</span> <span class="p">[{</span>
    <span class="s2">&quot;What is the answer to this math problem: What does 45x7=&quot;</span><span class="p">:</span> <span class="s2">&quot;315&quot;</span><span class="p">,</span>
    <span class="s2">&quot;What is the most popular religion in the world?&quot;</span><span class="p">:</span> <span class="s2">&quot;Christianity&quot;</span><span class="p">,</span>
    <span class="s2">&quot;What is the capital of the U.S?&quot;</span><span class="p">:</span> <span class="s2">&quot;Washington D.C.&quot;</span><span class="p">,</span>
    <span class="s2">&quot;How many kg is in 5g?&quot;</span><span class="p">:</span> <span class="s2">&quot;0.005 kg&quot;</span><span class="p">,</span>
    <span class="s2">&quot;How many mm are in 1 km?&quot;</span><span class="p">:</span> <span class="s2">&quot;1000000 mm&quot;</span><span class="p">,</span>
<span class="p">}]</span>
<span class="c1"># My_Quiz.append({</span>
<span class="c1">#     &quot;What is the answer to this math problem: What does 45x7=&quot;: &quot;315&quot;,</span>
<span class="c1">#     &quot;What is the most popular religion in the world?&quot;: &quot;Christianity&quot;,</span>
<span class="c1">#     &quot;What is the capital of the U.S?&quot;: &quot;Washington D.C.&quot;,</span>
<span class="c1">#     &quot;How many kg is in 5g?&quot;: &quot;0.005 kg&quot;,</span>
<span class="c1">#     &quot;How many mm are in 1 km?&quot;: &quot;1000000 mm&quot;,</span>
<span class="c1"># })</span>

<span class="k">for</span> <span class="nb">dict</span> <span class="ow">in</span> <span class="n">My_Quiz</span><span class="p">:</span>
    <span class="k">for</span> <span class="n">questions</span><span class="p">,</span> <span class="n">answers</span> <span class="ow">in</span> <span class="nb">dict</span><span class="o">.</span><span class="n">items</span><span class="p">():</span>
        <span class="n">Python_Quiz</span><span class="p">(</span><span class="n">questions</span><span class="p">)</span>
        <span class="k">if</span> <span class="n">word</span> <span class="o">==</span> <span class="n">answers</span><span class="p">:</span>
            <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Answer is correct&quot;</span><span class="p">)</span>
            <span class="n">correct_answer</span> <span class="o">+=</span> <span class="mi">1</span>
        <span class="k">else</span><span class="p">:</span>
            <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Answer is incorrect&quot;</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;You scored &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">correct_answer</span><span class="p">)</span> <span class="o">+</span> <span class="s2">&quot;/&quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">questions_number</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Hello, you will be asked 5 short questions
Question: What is the answer to this math problem: What does 45x7=
Answer is correct
Question: What is the most popular religion in the world?
Answer is correct
Question: What is the capital of the U.S?
Answer is correct
Question: How many kg is in 5g?
Answer is correct
Question: How many mm are in 1 km?
Answer is incorrect
You scored 4/5
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 
