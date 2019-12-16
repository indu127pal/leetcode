<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/minimum-falling-path-sum-ii "Minimum Falling Path Sum II")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/sequential-digits "Sequential Digits")

## [1290. Convert Binary Number in a Linked List to Integer (Easy)](https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer "二进制链表转整数")

<p>Given <code>head</code> which is a reference node to&nbsp;a singly-linked list. The value of each node in the linked list is either 0 or 1. The linked list holds the binary representation of a number.</p>

<p>Return the <em>decimal value</em> of the number in the linked list.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2019/12/05/graph-1.png" style="width: 426px; height: 108px;" />
<pre>
<strong>Input:</strong> head = [1,0,1]
<strong>Output:</strong> 5
<strong>Explanation:</strong> (101) in base 2 = (5) in base 10
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> head = [0]
<strong>Output:</strong> 0
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> head = [1]
<strong>Output:</strong> 1
</pre>

<p><strong>Example 4:</strong></p>

<pre>
<strong>Input:</strong> head = [1,0,0,1,0,0,1,1,1,0,0,0,0,0,0]
<strong>Output:</strong> 18880
</pre>

<p><strong>Example 5:</strong></p>

<pre>
<strong>Input:</strong> head = [0,0]
<strong>Output:</strong> 0
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li>The Linked List is not empty.</li>
	<li>Number of nodes&nbsp;will not exceed <code>30</code>.</li>
	<li>Each node&#39;s value is either&nbsp;<code>0</code> or <code>1</code>.</li>
</ul>

### Related Topics
  [[Bit Manipulation](https://github.com/openset/leetcode/tree/master/tag/bit-manipulation/README.md)]
  [[Linked List](https://github.com/openset/leetcode/tree/master/tag/linked-list/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Traverse the linked list and store all values in a string or array. convert the values obtained to decimal value.
</details>

<details>
<summary>Hint 2</summary>
You can solve the problem in O(1) memory using bits operation. use shift left operation ( << ) and or operation ( | ) to get the decimal value in one operation.
</details>