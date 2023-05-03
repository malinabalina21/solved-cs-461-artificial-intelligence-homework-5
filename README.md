Download Link: https://assignmentchef.com/product/solved-cs-461-artificial-intelligence-homework-5
<br>
To complete the assignment, you only need to consider <u>2-d trees</u> (viz. k is 2 throughout).




A k-d tree program normally has two parts: (i) <u>build</u> a tree from a given set of data points and (ii) <u>query</u> that tree with a new data point. The tree in part (i) is not dynamic; it never changes once it is built.




The goal of the homework is to query a 2-d tree (built with data from figure 19.2) with several unknowns (U). For each unknown you have to find the nearest neighbor using the <u>Euclidean</u> metric and report it (its <u>color</u>). Thus, the input is the set of points given in the aforementioned figure. Then an unknown point is entered and the program reports the color of its nearest neighbor.




Make sure that your program is able to single-step its calculations. Essentially, such a trace tells us which parts of the decision tree (cf. Figure 19.7) the program is visiting until it finds the answer.



















Here’s a list of query points (unknowns) that you have to use to test your program. It is crucial to notice that the first coordinate is the <u>width</u> and the second coordinate is the <u>height</u>.




<ul>

 <li>(1 point) <strong>U(1,4)</strong></li>

</ul>

<em>This is the unknown analyzed in ch. 19 (answer: orange block at (2,5))</em>




<ul>

 <li>(1 point) <strong>U(1,1)</strong></li>

</ul>




<ul>

 <li>(2 points) <strong>U(6,6)</strong></li>

</ul>




<ul>

 <li>(2 points) <strong>U(6,1)</strong></li>

</ul>




<ul>

 <li>(4 points) <strong>U(w,h)</strong>, where <strong>w</strong> and <strong>h </strong>are <u>integers</u> belonging to the closed interval [1,6]</li>

</ul>

<em> </em>

<em>CAVEAT: The last test above will be administered by your TA. Thus, your program should be able to read 2 integers separated by spaces from the keyboard. </em>

2


