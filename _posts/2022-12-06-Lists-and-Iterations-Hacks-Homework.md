---
keywords: fastai
title: Title
nb_path: _notebooks/2022-12-06-Lists-and-Iterations-Hacks-Homework.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-12-06-Lists-and-Iterations-Hacks-Homework.ipynb
-->

<div class="container" id="notebook-container">
        
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">words</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;alfa&quot;</span><span class="p">,</span> <span class="s2">&quot;bravo&quot;</span><span class="p">,</span> <span class="s2">&quot;charlie&quot;</span><span class="p">,</span> <span class="s2">&quot;delta&quot;</span><span class="p">,</span> <span class="s2">&quot;echo&quot;</span><span class="p">,</span> <span class="s2">&quot;foxtrot&quot;</span><span class="p">,</span> <span class="s2">&quot;golf&quot;</span><span class="p">,</span> <span class="s2">&quot;hotel&quot;</span><span class="p">,</span> <span class="s2">&quot;india&quot;</span><span class="p">,</span> <span class="s2">&quot;juliett&quot;</span><span class="p">,</span> <span class="s2">&quot;kilo&quot;</span><span class="p">,</span>
<span class="s2">&quot;lima&quot;</span><span class="p">,</span> <span class="s2">&quot;mike&quot;</span><span class="p">,</span> <span class="s2">&quot;november&quot;</span><span class="p">,</span> <span class="s2">&quot;oscar&quot;</span><span class="p">,</span> <span class="s2">&quot;papa&quot;</span><span class="p">,</span> <span class="s2">&quot;quebec&quot;</span><span class="p">,</span> <span class="s2">&quot;romeo&quot;</span><span class="p">,</span> <span class="s2">&quot;sierra&quot;</span><span class="p">,</span> <span class="s2">&quot;tango&quot;</span><span class="p">,</span> <span class="s2">&quot;uniform&quot;</span><span class="p">,</span> <span class="s2">&quot;victor&quot;</span><span class="p">,</span> <span class="s2">&quot;whiskey&quot;</span><span class="p">,</span> <span class="s2">&quot;xray&quot;</span><span class="p">,</span> <span class="s2">&quot;yankee&quot;</span><span class="p">,</span> <span class="s2">&quot;zulu&quot;</span><span class="p">]</span>

<span class="n">inp</span> <span class="o">=</span> <span class="nb">input</span><span class="p">()</span><span class="o">.</span><span class="n">lower</span><span class="p">()</span>
<span class="n">output</span> <span class="o">=</span> <span class="s2">&quot;&quot;</span>

<span class="k">for</span> <span class="n">letter</span> <span class="ow">in</span> <span class="n">inp</span><span class="p">:</span>
    <span class="k">for</span> <span class="n">word</span> <span class="ow">in</span> <span class="n">words</span><span class="p">:</span>
        <span class="k">if</span> <span class="n">letter</span> <span class="o">==</span> <span class="n">word</span><span class="p">[</span><span class="mi">0</span><span class="p">]:</span>
            <span class="n">output</span> <span class="o">+=</span> <span class="n">word</span> <span class="o">+</span> <span class="s2">&quot; &quot;</span>

<span class="nb">print</span><span class="p">(</span><span class="n">inp</span> <span class="o">+</span> <span class="s2">&quot;</span><span class="se">\n</span><span class="s2">&quot;</span> <span class="o">+</span> <span class="n">output</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>whatever
whiskey hotel alfa tango echo victor echo romeo 
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">keypad</span> <span class="o">=</span> <span class="p">[[</span><span class="mi">1</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">],</span> <span class="p">[</span><span class="mi">4</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">6</span><span class="p">],</span> <span class="p">[</span><span class="mi">7</span><span class="p">,</span> <span class="mi">8</span><span class="p">,</span> <span class="mi">9</span><span class="p">],</span> <span class="p">[</span><span class="s2">&quot; &quot;</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="s2">&quot; &quot;</span><span class="p">]]</span>


<span class="k">def</span> <span class="nf">print_matrix3</span><span class="p">(</span><span class="n">matrix</span><span class="p">):</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">matrix</span><span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="o">*</span><span class="n">i</span><span class="p">)</span>
        
<span class="n">print_matrix3</span><span class="p">(</span><span class="n">keypad</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>1 2 3
4 5 6
7 8 9
  0  
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">keyboard</span> <span class="o">=</span> <span class="p">[[</span><span class="s2">&quot;`&quot;</span><span class="p">,</span> <span class="mi">1</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">4</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">6</span><span class="p">,</span> <span class="mi">7</span><span class="p">,</span> <span class="mi">8</span><span class="p">,</span> <span class="mi">9</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="s2">&quot;-&quot;</span><span class="p">,</span> <span class="s2">&quot;=&quot;</span><span class="p">],</span>
            <span class="p">[</span><span class="s2">&quot;Q&quot;</span><span class="p">,</span> <span class="s2">&quot;W&quot;</span><span class="p">,</span> <span class="s2">&quot;E&quot;</span><span class="p">,</span> <span class="s2">&quot;R&quot;</span><span class="p">,</span> <span class="s2">&quot;T&quot;</span><span class="p">,</span> <span class="s2">&quot;Y&quot;</span><span class="p">,</span> <span class="s2">&quot;U&quot;</span><span class="p">,</span> <span class="s2">&quot;I&quot;</span><span class="p">,</span> <span class="s2">&quot;O&quot;</span><span class="p">,</span> <span class="s2">&quot;P&quot;</span><span class="p">,</span> <span class="s2">&quot;[&quot;</span><span class="p">,</span> <span class="s2">&quot;]&quot;</span><span class="p">],</span>
            <span class="p">[</span><span class="s2">&quot;A&quot;</span><span class="p">,</span> <span class="s2">&quot;S&quot;</span><span class="p">,</span> <span class="s2">&quot;D&quot;</span><span class="p">,</span> <span class="s2">&quot;F&quot;</span><span class="p">,</span> <span class="s2">&quot;G&quot;</span><span class="p">,</span> <span class="s2">&quot;H&quot;</span><span class="p">,</span> <span class="s2">&quot;J&quot;</span><span class="p">,</span> <span class="s2">&quot;K&quot;</span><span class="p">,</span> <span class="s2">&quot;L&quot;</span><span class="p">,</span> <span class="s2">&quot;;&quot;</span><span class="p">,</span> <span class="s2">&quot;&#39;&quot;</span><span class="p">],</span>
            <span class="p">[</span><span class="s2">&quot;Z&quot;</span><span class="p">,</span> <span class="s2">&quot;X&quot;</span><span class="p">,</span> <span class="s2">&quot;C&quot;</span><span class="p">,</span> <span class="s2">&quot;V&quot;</span><span class="p">,</span> <span class="s2">&quot;B&quot;</span><span class="p">,</span> <span class="s2">&quot;N&quot;</span><span class="p">,</span> <span class="s2">&quot;M&quot;</span><span class="p">,</span> <span class="s2">&quot;,&quot;</span><span class="p">,</span> <span class="s2">&quot;.&quot;</span><span class="p">,</span> <span class="s2">&quot;/&quot;</span><span class="p">]]</span>

<span class="c1"># Birth Month</span>
<span class="nb">print</span><span class="p">(</span><span class="nb">str</span><span class="p">(</span><span class="n">keyboard</span><span class="p">[</span><span class="mi">3</span><span class="p">][</span><span class="mi">5</span><span class="p">])</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">keyboard</span><span class="p">[</span><span class="mi">1</span><span class="p">][</span><span class="mi">8</span><span class="p">])</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">keyboard</span><span class="p">[</span><span class="mi">3</span><span class="p">][</span><span class="mi">3</span><span class="p">])</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">keyboard</span><span class="p">[</span><span class="mi">1</span><span class="p">][</span><span class="mi">2</span><span class="p">])</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">keyboard</span><span class="p">[</span><span class="mi">3</span><span class="p">][</span><span class="mi">6</span><span class="p">])</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">keyboard</span><span class="p">[</span><span class="mi">3</span><span class="p">][</span><span class="mi">4</span><span class="p">])</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">keyboard</span><span class="p">[</span><span class="mi">1</span><span class="p">][</span><span class="mi">2</span><span class="p">])</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">keyboard</span><span class="p">[</span><span class="mi">1</span><span class="p">][</span><span class="mi">3</span><span class="p">]))</span>
<span class="c1"># Age</span>
<span class="nb">print</span><span class="p">(</span><span class="nb">str</span><span class="p">(</span><span class="n">keyboard</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="mi">1</span><span class="p">])</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">keyboard</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="mi">6</span><span class="p">]))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>NOVEMBER
16
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

