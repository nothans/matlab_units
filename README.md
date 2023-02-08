<h1>Unit 1: Introduction to MATLAB</h1>
<h2>Context</h2>
<p>In this unit, students will be introduced to MATLAB and its basic concepts. This unit will cover the following topics:</p>
<ul>
  <li>Overview of MATLAB</li>
  <li>Basic operations and arithmetic</li>
  <li>Built-in functions and scripts</li>
  <li>Basic plotting and visualization</li>
</ul>
<h2>Specific Code Examples</h2>
<h3>1. Overview of MATLAB:</h3>
<ul>
  <li>Provide a brief overview of MATLAB and its purpose.</li>
  <li>Demonstrate how to start MATLAB and how to use the command window.</li>
</ul>
<h3>2. Basic Operations and Arithmetic:</h3>
<ul>
  <li>Explain how to perform basic arithmetic operations in MATLAB, such as addition, subtraction, multiplication, and division.</li>
  <li>Provide code examples of basic arithmetic operations:</li>
</ul>
<pre>
<code>
5 + 2
5 - 2
5 * 2
5 / 2
</code>
</pre>
<h3>3. Built-in Functions and Scripts:</h3>
<ul>
  <li>Explain how to use built-in functions in MATLAB, such as sin(), cos(), log(), and others.</li>
  <li>Explain how to create and run scripts in MATLAB.</li>
  <li>Provide code examples of using built-in functions and running scripts:</li>
</ul>
<pre>
<code>
sin(pi/2)
x = 0:0.1:2*pi;
y = sin(x);
plot(x,y)
</code>
</pre>
<h3>4. Basic Plotting and Visualization:</h3>
<ul>
  <li>Explain how to create basic plots in MATLAB, including line plots and scatter plots.</li>
  <li>Provide code examples of how to create plots using built-in functions, such as plot():</li>
</ul>
<pre>
<code>
x = -10:0.1:10;
y = sin(x);
plot(x,y)
</code>
</pre>
<p>By the end of this unit, students should have a basic understanding of MATLAB and its basic concepts, including basic operations, built-in functions, and basic plotting and visualization.</p>

<h1>Unit 2: Variables and Data Types</h1>
<h2>Context</h2>
<p>In this unit, students will continue their introduction to MATLAB by learning about variables and arrays. This unit will cover the following topics:</p>
<ul>
  <li>Variables and assignment statements</li>
  <li>Vectors and matrices</li>
  <li>Array operations</li>
  <li>Loading and saving data</li>
</ul>
<h2>Specific Code Examples</h2>
<h3>1. Variables and Assignment Statements:</h3>
<ul>
  <li>Explain what variables are and how they can be used in MATLAB.</li>
  <li>Demonstrate how to assign values to variables using assignment statements.</li>
  <li>Provide code examples of how to use variables in MATLAB:</li>
</ul>
<pre>
<code>
a = 5;
b = 2;
c = a + b
</code>
</pre>
<h3>2. Vectors and Matrices:</h3>
<ul>
  <li>Explain what vectors and matrices are and how they can be used in MATLAB.</li>
  <li>Demonstrate how to create and manipulate vectors and matrices in MATLAB.</li>
  <li>Provide code examples of how to create and manipulate vectors and matrices:</li>
</ul>
<pre>
<code>
a = [1, 2, 3];
b = [4, 5, 6];
c = a + b

A = [1, 2, 3; 4, 5, 6];
B = [7, 8, 9; 10, 11, 12];
C = A + B
</code>
</pre>
<h3>3. Array Operations:</h3>
<ul>
  <li>Explain what array operations are and how they can be used in MATLAB.</li>
  <li>Demonstrate how to perform array operations in MATLAB, such as element-wise operations, transposing, and concatenation.</li>
  <li>Provide code examples of array operations:</li>
</ul>
<pre>
<code>
a = [1, 2, 3];
b = [4, 5, 6];
c = a .* b

A = [1, 2, 3; 4, 5, 6];
B = [7, 8, 9; 10, 11, 12];
C = A'
D = [A; B]
</code>
</pre>
<h3>4. Loading and Saving Data:</h3>
<ul>
  <li>Explain what loading and saving data is and why it is important in MATLAB.</li>
  <li>Demonstrate how to load and save data using MATLAB functions such as load() and save().</li>
  <li>Provide code examples of loading and saving data:</li>
</ul>
<pre>
<code>
b = [4, 5, 6];
save('b.mat', 'b')
clear
load('b.mat')
</code>
</pre>
<h1>Unit 3: Plotting and Visualization</h1>
<h2>Context</h2>
<p>In this unit, students will learn about plotting and visualization in MATLAB. This unit will cover the following topics:</p>
<ul>
  <li>2D plotting</li>
  <li>3D plotting</li>
  <li>Customizing plots</li>
  <li>Saving plots</li>
</ul>
<h2>Specific Code Examples</h2>
<h3>1. 2D Plotting:</h3>
<ul>
  <li>Explain what 2D plotting is and why it is important in MATLAB.</li>
  <li>Demonstrate how to create 2D plots using MATLAB functions such as plot().</li>
  <li>Provide code examples of 2D plotting:</li>
</ul>
<pre>
<code>
x = -5:0.1:5;
y = sin(x);
plot(x, y)
</code>
</pre>
<h3>2. 3D Plotting:</h3>
<ul>
  <li>Explain what 3D plotting is and why it is important in MATLAB.</li>
  <li>Demonstrate how to create 3D plots using MATLAB functions such as plot3().</li>
  <li>Provide code examples of 3D plotting:</li>
</ul>
<pre>
<code>
x = -5:0.1:5;
y = x;
z = x.^2 + y.^2;
plot3(x, y, z)
</code>
</pre>
<h3>3. Customizing Plots:</h3>
<ul>
  <li>Explain what customizing plots is and why it is important in MATLAB.</li>
  <li>Demonstrate how to customize plots using MATLAB functions such as title(), xlabel(), ylabel(), and other customization options.</li>
  <li>Provide code examples of customizing plots:</li>
</ul>
<pre>
<code>
x = -5:0.1:5;
y = sin(x);
plot(x, y)
title('Sine Function')
xlabel('X-axis')
ylabel('Y-axis')
</code>
</pre>
<h3>4. Saving Plots:</h3>
<ul>
  <li>Explain what saving plots is and why it is important in MATLAB.</li>
  <li>Demonstrate how to save plots using MATLAB functions such as saveas().</li>
  <li>Provide code examples of saving plots:</li>
</ul>
<pre>
<code>
x = -5:0.1:5;
y = sin(x);
plot(x, y)
saveas(gcf, 'sine_plot.png')
</code>
</pre>
