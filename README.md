Download Link: https://assignmentchef.com/product/solved-csci2720-assignment5-selection-sort-merge-sort-heap-sort-and-quicksort-in-c
<br>
For this project, you will implement Selection sort, Merge sort, Heap sort and Quicksort in C++ and you will write a 1 to 3 page analysis report. <strong>For quicksort, you should provide two implementations</strong>. One implementation should use the first element of the array as the pivot. The second implementation should use a random pivot. All of your sorting algorithms need to keep track of the number of comparisons used by the sorting algorithm. <strong>The sorting algorithms should sort a set of integers in the ascending order.</strong>

<strong>Start early on this assignment as you need to submit a report along with your code. Note most of the code is already provided in the slide so you are free to use that code (just cite it in your read me file) only thing you need to do is calculate the number of comparisons each algorithm is making (something similar to what is explained in the lecture). For comparison you need to count when you compare two ‘data elements’ not the comparison for ‘i’ in a for loop.</strong>

<strong><u>Additional Requirements</u></strong>

<ol>

 <li>You can do this assignment by writing your own classes with required data members and methods. You have full freedom on how you want to build your classes.</li>

 <li>The program must include a makefile that compiles your source files into an executable file called “main”. The makefile should also have a clean directive to clean compiled artifacts. You will require a separate “Sorting.cpp” file for implementing all four sorting algorithms.</li>

 <li>As the program is run (with input filename as a command line argument as shown below), it should ask for which sorting algorithm to be used for sorting. Sorted result should then be generated using that algorithm for sorting.</li>

 <li>Unlike the previous assignments, after printing the results of a sort, exit the program automatically. In other words, <strong><u>do not </u></strong>ask to enter the algorithm again in a loop.</li>

 <li>In each of the sorting functions, you should embed statements to count the total number of comparisons used by the function for sorting. You can use a type long count variable to count comparisons. After sorting is completed, you should print this count exactly as shown in the example output.</li>

 <li>For this assignment you need to do two sets of experiments and prepare a report which will include results, plots and discussion from these two experiments. The first experiment is explained in points 7 and 8 where you just need to find out the number of comparisons for different sorting algorithms for different types of input files. The second experiment is explained in point 9 and 10 where you need to draw a plot between size vs no. of comparisons for different sorting algorithms and then verify that the plots obtained by your experiments match with the theoretical result. You need to prepare a report summarizing all your results, plots, discussion and conclusion from these two experiments.</li>

 <li><strong>You will be given 3 input files for testing the first experiment. Check ELC contents page for these files.</strong>

  <ol>

   <li>Ordered file – Containing integers placed in ascending order from 0 to 9999</li>

   <li>Random file – Containing 10000 integers arranged in a random fashion</li>

   <li>Reversed file – Containing integers placed in reverse order from 9999 to 0</li>

  </ol></li>

 <li>You can use the same code snippet for reading input from the files as in the previous assignments. Write a well-organized, 1 to 3 page report of your work (you can exceed this if you need to). Your report must be submitted as a PDF file with your name in the middle of the cover page. Submit your report on elc and your code on odin. Your report must include an explanation of the experiments you performed for each algorithm. In conclusion answer the following questions :

  <ol>

   <li>Provide the total number of comparisons used by each one of the algorithms and explain whether they align with the Big O time complexity of each algorithm. In case of quick sort, compare and comment about the number of comparisons and complexity with the other quicksort implementation.</li>

   <li>For Ordered file as input. ii. For Random file as input.</li>

  </ol></li>

</ol>

iii.      For Reversed file as input.

Please use the following table format to summarize the content for point a.

<table width="517">

 <tbody>

  <tr>

   <td width="100">Algorithm</td>

   <td width="100">Input Type</td>

   <td width="100"># comparisons</td>

   <td width="217">Comments about time complexity and # comparisons</td>

  </tr>

  <tr>

   <td width="100">…</td>

   <td width="100">…</td>

   <td width="100">…</td>

   <td width="217">…</td>

  </tr>

 </tbody>

</table>

After this table, also answer these questions below:

<ol>

 <li>Did you use extra memory space or other data structures other than the input array? If so, explain where and why?</li>

 <li>Explain what sorting algorithms work best in what situations based on your experimental results.</li>

</ol>

Here is a small example that shows what to expect when you run these algorithms on the input files. The size of input is 10,000 so for an algorithm with N<sup>2 </sup>complexity N<sup>2 </sup>is going to be 10000000 for such an algorithm expect 8-9 digits in the number of comparison value. Similarly for algorithm with

NlogN complexity NlogN will be 40,000 so expect 5-6 digits in the number of comparisons that you will get. For NlogN algorithm if you are getting 8-9 digits in comparisons that will indicate a problem in your comparison calculation.

<ol start="9">

 <li>After completing the above program and report, you will do the next set of experiments where you will draw plots (n , input size vs no. of comparisons) for sorting algorithms and verify that the experimental results match with the theoretical results. You have complete freedom in how you want to implement this part of the assignment. You can create a new main, or add an function to your sorting.cpp class or add an function in the main.cpp that implements this part of the assignment.Your code should use the algorithms created in Sorting.cpp to find additional insights about the 5 different sorting algorithms. For this part of the assignment you are not reading inputs from the text files, but instead you will be generating the inputs within the program itself and it should calculate the comparison values. Your code should be able to run the five algorithms (mentioned below) with different sizes of the inputs and give the number of comparisons. You can use these comparison values to draw the plots. (This is for the grading purpose) provide an interface in your implementation where user can specify which sorting algorithm they want to use and the size of the input that they wish to test. Your program should then generate an array with n number of <strong>random values </strong>(with n being the number specified by the user) and then it should sort those values using the sorting algorithm selected by the user. The number of comparisons should also be printed. <strong>Please specify in your README file how to compile, run and use your implementation because it is mostly up to you for how you want to implement this part of the assignment. Also note there is no sample output for this part of the assignment.</strong></li>

 <li>You are now going to use implementation in point 9 to create multiple different plots for the report mentioned above. Keep track of your experiments in a table formatted like the following and include this on your report:</li>

</ol>

Size of input

<table width="528">

 <tbody>

  <tr>

   <td width="107">Algorithm</td>

   <td width="29">10</td>

   <td width="40">100</td>

   <td width="49">500</td>

   <td width="56">1000</td>

   <td width="55">10000</td>

   <td width="60">20000</td>

   <td width="52">50000</td>

   <td width="80">100000</td>

  </tr>

  <tr>

   <td width="107">Selection</td>

   <td width="29"> </td>

   <td width="40"> </td>

   <td width="49"> </td>

   <td width="56"> </td>

   <td width="55"> </td>

   <td width="60"> </td>

   <td width="52"> </td>

   <td width="80"> </td>

  </tr>

  <tr>

   <td width="107">Merge</td>

   <td width="29"> </td>

   <td width="40"> </td>

   <td width="49"> </td>

   <td width="56"> </td>

   <td width="55"> </td>

   <td width="60"> </td>

   <td width="52"> </td>

   <td width="80"> </td>

  </tr>

  <tr>

   <td width="107">Heap</td>

   <td width="29"> </td>

   <td width="40"> </td>

   <td width="49"> </td>

   <td width="56"> </td>

   <td width="55"> </td>

   <td width="60"> </td>

   <td width="52"> </td>

   <td width="80"> </td>

  </tr>

  <tr>

   <td width="107">QuickSort-fp</td>

   <td width="29"> </td>

   <td width="40"> </td>

   <td width="49"> </td>

   <td width="56"> </td>

   <td width="55"> </td>

   <td width="60"> </td>

   <td width="52"> </td>

   <td width="80"> </td>

  </tr>

  <tr>

   <td width="107">QuickSort-rp</td>

   <td width="29"> </td>

   <td width="40"> </td>

   <td width="49"> </td>

   <td width="56"> </td>

   <td width="55"> </td>

   <td width="60"> </td>

   <td width="52"> </td>

   <td width="80"> </td>

  </tr>

 </tbody>

</table>

Note: <strong>I recommend running each algorithm multiple times and taking the average result for each input size to use in this table and for your plots. You can also use more values of n to make your plot look smoother however in the report you just need to show the results for the above table.</strong>

<ol>

 <li>You should use some sort of graphing software like Microsoft Excel or Google Sheets to generate plots that compare the size of input n to the number of comparisons for the 5 sorting algorithms. You should have 5 separate plots(one for each sorting algorithm) with n on the x-axis and number of comparisons on the y-axis. Include these plots in your report.</li>

 <li>You will then provide some discussion about your results. Compare the theoretical result with your experimental result for each algorithm. Does your experimental result coincide with the Big-O of that specific algorithm? Describe why there may be some inconsistencies between your plot and what the theoretical plot looks like.</li>

</ol>

<strong>Your report must be in PDF format. Submit the report on the submission link provided on the eLC under the assignment section.</strong>

<strong>Note: Example output has not shown the complete list of numbers. However, you must print the complete list of numbers in your program. The number of comparisons shown in sample output below may be slightly different than the numbers that you get, however make sure that you at least get the same number of digits so you know that it is in the correct big-O.</strong>

<strong>quick-sort-fp stands for quick sort with first element as the pivot. quick-sort-rp stands for quick sort with random element as the pivot.</strong>

<strong>Sample Output 1 (ordered.txt)</strong>:

./main ordered.txt

selection-sort (s)     merge-sort (m) heap-sort (h)    quick-sort-fp

(q) quick-sort-rp (r)

Enter the algorithm: s 1 2 3 4 5 ………….. 9999

#Selection-sort comparisons:  49995000

./main ordered.txt

selection-sort (s)     merge-sort (m) heap-sort (h)    quick-sort-fp

(q) quick-sort-rp (r)

Enter the algorithm: m

1 2 3 4 5 ……………. 9999

#Merge-sort comparisons: 69008

./main ordered.txt

<table width="597">

 <tbody>

  <tr>

   <td width="480">selection-sort (s)     merge-sort (m) heap-sort (h)(q) quick-sort-rp (r)Enter the algorithm: h1 2 3 4 5 ……………. 9999#Heap-sort comparisons: 244576./main ordered.txt</td>

   <td width="117">quick-sort-fp</td>

  </tr>

  <tr>

   <td width="480">selection-sort (s)     merge-sort (m) heap-sort (h)(q) quick-sort-rp (r)Enter the algorithm: q1 2 3 4 5 ……………. 9999#Quick-sort-fp comparisons: 49995000./main ordered.txt</td>

   <td width="117">quick-sort-fp</td>

  </tr>

  <tr>

   <td width="480">selection-sort (s)     merge-sort (m) heap-sort (h)(q) quick-sort-rp (r)Enter the algorithm: r1 2 3 4 5 ……………. 9999#Quick-sort-rp comparisons: 161020<strong>Sample Output 2 (random.txt)</strong>:./main random.txt</td>

   <td width="117">quick-sort-fp</td>

  </tr>

  <tr>

   <td width="480">selection-sort (s)     merge-sort (m) heap-sort (h)(q) quick-sort-rp (r)Enter the algorithm: s 1 2 3 4 5 ……………. 9999#Selection-sort comparisons: 49995000./main random.txt</td>

   <td width="117">quick-sort-fp</td>

  </tr>

  <tr>

   <td width="480">selection-sort (s)     merge-sort (m) heap-sort (h)(q) quick-sort-rp (r)Enter the algorithm: m 1 2 3 4 5 ……………. 9999#Merge-sort comparisons: 120414</td>

   <td width="117">quick-sort-fp</td>

  </tr>

 </tbody>

</table>

./main random.txt

<table width="597">

 <tbody>

  <tr>

   <td width="480">selection-sort (s)     merge-sort (m) heap-sort (h)(q) quick-sort-rp (r)Enter the algorithm: h 1 2 3 4 5 ……………. 9999#Heap-sort comparisons: 235440./main random.txt</td>

   <td width="117">quick-sort-fp</td>

  </tr>

  <tr>

   <td width="480">selection-sort (s)     merge-sort (m) heap-sort (h)(q) quick-sort-rp (r)Enter the algorithm: q 1 2 3 4 5 ……………. 9999#Quick-sort-fp comparisons: 159534./main random.txt</td>

   <td width="117">quick-sort-fp</td>

  </tr>

  <tr>

   <td width="480">selection-sort (s)     merge-sort (m) heap-sort (h)(q) quick-sort-rp (r)Enter the algorithm: r 1 2 3 4 5 ……………. 9999#Quick-sort-rp comparisons: 167559<strong>Sample Output 3 (reverse.txt)</strong>:./main reversed.txt</td>

   <td width="117">quick-sort-fp</td>

  </tr>

  <tr>

   <td width="480">selection-sort (s)     merge-sort (m) heap-sort (h)(q) quick-sort-rp (r)Enter the algorithm: s 1 2 3 4 5 ……………. 9999#Selection-sort comparison: 49995000./main reversed.txt</td>

   <td width="117">quick-sort-fp</td>

  </tr>

  <tr>

   <td width="480">selection-sort (s)     merge-sort (m) heap-sort (h)(q) quick-sort-rp (r)Enter the algorithm: m 1 2 3 4 5 ……………. 9999#Merge-sort comparison: 64608./main reversed.txt</td>

   <td width="117">quick-sort-fp</td>

  </tr>

  <tr>

   <td width="480">selection-sort (s)     merge-sort (m) heap-sort (h)</td>

   <td width="117">quick-sort-fp</td>

  </tr>

 </tbody>

</table>

(q) quick-sort-rp (r)

Enter the algorithm: h 1 2 3 4 5 ……………. 9999

#Heap-sort comparison: 226720

./main reversed.txt selection-sort (s) merge-sort (m) heap-sort (h) quick-sort-fp

(q) quick-sort-rp (r)

Enter the algorithm: q 1 2 3 4 5 ……………. 9999

#Quick-sort-fp comparison: 49995000

./main reversed.txt selection-sort (s) merge-sort (m) heap-sort (h) quick-sort-fp

(q) quick-sort-rp (r)

Enter the algorithm: r 1 2 3 4 5 ……………. 9999

#Quick-sort-rp comparison: 165518