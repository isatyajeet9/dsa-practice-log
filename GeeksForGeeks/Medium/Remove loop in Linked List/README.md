# Remove loop in Linked List

## Difficulty: Medium

## Platform: GeeksForGeeks

## Problem Link
[View Problem](https://www.geeksforgeeks.org/problems/remove-loop-in-linked-list/1?page=1&category=Linked%20List&sortBy=submissions)

## Solved On
08 Apr 2026 at 10:03 pm

<h2><a href="https://www.geeksforgeeks.org/problems/remove-loop-in-linked-list/1?page=1&category=Linked%20List&sortBy=submissions">Remove loop in Linked List</a></h2><h3>Difficulty Level: Medium</h3><hr><p data-pm-slice="0 0 []"><span style="font-size: 14pt;">Given the<strong> head </strong>of a singly linked list, the task is to <strong>remove a cycle</strong> if present. A cycle exists when a node's next pointer points back to a previous node, forming a loop. Internally, a variable <strong>pos</strong> denotes the index of the node where the cycle starts, but it is not passed as a parameter. The terminal will print <strong>true</strong> if a cycle is removed otherwise, it will print <strong>false.</strong></span></p>
<p><span style="font-size: 14pt;"><strong>Examples:</strong></span></p>
<pre><span style="font-size: 14pt;"><strong>Input: </strong>head =<strong> </strong>1 -&gt; 3 -&gt; 4, pos = 2
<strong>Output: </strong>true<strong>
Explanation: </strong>The linked list looks like<br><img src="https://media.geeksforgeeks.org/img-practice/prod/addEditProblem/700332/Web/Other/blobid0_1718609709.png" width="403" height="161"><br>A loop is present in the list, and it is removed.
</span></pre>
<pre><span style="font-size: 14pt;"><strong>Input: </strong>head = 1 -&gt; 8 -&gt; 3 -&gt; 4, pos = 0
<strong>Output: </strong>true<strong>
Explanation: <br></strong><strong><img src="https://media.geeksforgeeks.org/img-practice/prod/addEditProblem/700332/Web/Other/blobid0_1718609876.png" height="100"><br></strong>The Linked list does not contains any loop. </span></pre>
<pre><span style="font-size: 14pt;"><strong>Input: </strong>head =<strong> </strong>1 -&gt; 2 -&gt; 3 -&gt; 4, pos = 1
<strong>Output: </strong>true<strong>
Explanation: </strong>The linked list looks like <br><img src="https://media.geeksforgeeks.org/img-practice/prod/addEditProblem/700332/Web/Other/blobid2_1718609744.png" width="400" height="160"><br>A loop is present in the list, and it is removed.</span></pre>
<p><span style="font-size: 14pt;"><strong>Constraints:</strong><br>1 ≤ size of linked list ≤ 10<sup>5</sup></span></p>