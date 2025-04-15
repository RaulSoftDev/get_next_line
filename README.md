<div align="center">
  <img width="175" src="https://img.shields.io/badge/Grade-100%25-00dd13?style=for-the-badge&logo=42"/>
</div>

<div align="center">
  <h1 align="center">get_next_line</h1>
</div>

<p direction="auto">
 get_next_line is a 42 Madrid Common Core project in which you have to code a function that will return a line read from a file descriptor.
</p>

## About the project
<p direction="auto">
  In this project you will have to code a function that when used in a loop will read and return all the lines from a file using its file descriptor.  
</p>
<h3>Mandatory parts</h3>
<ul>
  <li>Function protoype: <code>char *get_next_line(int fd);</code></li>
  <li>Your function must return the line read, <code>NULL</code> if reaches the end of file or returns error.</li>
  <li>Your function have to work with files and with <code>stdin</code>.</li>
  <li>Every line read from your function must end with the <code>\n</code> null char, except at the end of the file if it does not end with it.</li>
  <li>The script must have a static variable <code>BUFFER_SIZE</code> to set the default buffer size.</li>
  <li>The project must compile with the <code>-D BUFFER_SIZE=XX</code> flag but should have to compile without it.</li>
</ul>
<h3>Restrictions</h3>
<ul>
  <li>The use of the <code>libft</code> library is forbidden.</li>
  <li>The use of <code>lseek</code> is forbidden.</li>
  <li>The use of global variables is forbidden.</li>
</ul>

## Compilation
<h3>Requirements</h3>
<ul>
  <li>C compiler: <code>gcc</code>, <code>cc</code>, etc...</li>
</ul>

<h3>Build project</h3>
<ol>
<li>
<p dir="auto">Clone the repository:</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><samp>git clone https://github.com/RaulSoftDev/get_next_line.git</samp></pre>
</div>
</li>
<li>
<p dir="auto">Use the function in your project:</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>#include "get_next_line/get_next_line.h"</pre>
</div>
</li>
<li>
<p dir="auto">Compile your project:</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><samp>gcc -Wall -Wextra -Werror -D BUFFER_SIZE=42 *.c</samp></pre>
</div>
</li>
</ol>
