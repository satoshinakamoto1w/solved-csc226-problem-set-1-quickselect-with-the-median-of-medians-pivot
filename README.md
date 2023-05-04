Download Link: https://assignmentchef.com/product/solved-csc226-problem-set-1-quickselect-with-the-median-of-medians-pivot
<br>
<h1>Quickselect with the Median-of-Medians Pivot</h1>

<ul>

 <li>Programming Assignment</li>

</ul>

The assignment is to design and implement Quickselect with the median-of-medians pivot, where the medians are of groups of size 7.

Input:      An array <em>A </em>of <em>n </em>integers and an integer <em>k </em>in the set {1<em>,</em>2<em>,…,n</em>}. Output:    The <em>k </em><sup>th </sup>smallest element of <em>A</em>.

A Java template has been provided containing an empty function QuickSelect, which takes an integer array <em>A </em>and an integer <em>k </em>as arguments, and returns the <em>k </em><sup>th </sup>smallest element of <em>A</em>. Your task is to write the body of the QuickSelect function. In case of incorrect inputs, you should return −1.

You must use the provided Java template as the basis of your submission, and put your implementation inside the QuickSelect function in the template. You may not change the name, return type or parameters of the QuickSelect function or the class. The main function in the template contains code to help you test your implementation by entering test data or reading it from a file. You may modify the main function, but only the contents of the QuickSelect function will be marked, since the main function will be deleted before marking begins.

<ul>

 <li>Examples</li>

</ul>

The table below shows the correct output of the QuickSelect function on various test inputs.

<table width="200">

 <tbody>

  <tr>

   <td width="112">Input Array <em>A</em></td>

   <td width="23"><em>k</em></td>

   <td width="65">Output</td>

  </tr>

  <tr>

   <td width="112">10, 35, 12, 243</td>

   <td width="23">2</td>

   <td width="65">12</td>

  </tr>

  <tr>

   <td width="112">1, 24, 3, 70</td>

   <td width="23">1</td>

   <td width="65">1</td>

  </tr>

  <tr>

   <td width="112">85, 100, 99, 50</td>

   <td width="23">5</td>

   <td width="65">−1</td>

  </tr>

  <tr>

   <td width="112">85</td>

   <td width="23">1</td>

   <td width="65">85</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Grading</li>

</ul>

The programming assignment will be marked out of 40, based on a combination of automated testing (using large test arrays similar to the ones posted on conneX) and human inspection.

There are several possible implementations for Quickselect. For an input array containing <em>n </em>values, the optimal implementation is <em>O</em>(<em>n</em>). The mark for each submission will be based on both the asymptotic worst case running time and the ability of the algorithm to handle inputs of different sizes. The table below shows the expectations associated with different scores.

<table width="450">

 <tbody>

  <tr>

   <td width="56">Score</td>

   <td width="394">Description</td>

  </tr>

  <tr>

   <td width="56">0 – 15</td>

   <td width="394">Submission does not compile or does not conform to the provided template.</td>

  </tr>

  <tr>

   <td width="56">16 – 30</td>

   <td width="394">The implemented algorithm is not <em>O</em>(<em>n</em>) or is substantially inaccurate on the tested inputs.</td>

  </tr>

  <tr>

   <td width="56">31 – 40</td>

   <td width="394">The implemented algorithm is <em>O</em>(<em>n</em>) and gives the correct answer on all tested inputs.</td>

  </tr>

 </tbody>

</table>

1

CSC 226: Problem Set 1

To be properly tested, every submission must compile correctly as submitted, and must be based on the provided template. If your submission does not compile for any reason (even trivial mistakes like typos), or was not based on the template, it will receive at most 15 out of 40. The best way to make sure your submission is correct is to download it from conneX after submitting and test it. You are not permitted to revise your submission after the due date, and late submissions will not be accepted, so you should ensure that you have submitted the correct version of your code before the due date. conneX will allow you to change your submission before the due date if you notice a mistake. After submitting your assignment, conneX will automatically send you a confirmation email. If you do not receive such an email, your submission was not received. If you have problems with the submission process, send an email to the instructor before the due date.

2