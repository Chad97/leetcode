#### 使数组唯一的最小增量/Minimum Increment to Make Array Unique
**难度：** 中等/Medium

**Question：** 

<p>Given an array of integers A, a <em>move</em> consists of choosing any <code>A[i]</code>, and incrementing it by <code>1</code>.</p>

<p>Return the least number of moves to make every value in <code>A</code> unique.</p>

<p>&nbsp;</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-1-1">[1,2,2]</span>
<strong>Output: </strong><span id="example-output-1">1</span>
<strong>Explanation: </strong> After 1 move, the array could be [1, 2, 3].
</pre>

<div>
<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-2-1">[3,2,1,2,1,7]</span>
<strong>Output: </strong><span id="example-output-2">6</span>
<strong>Explanation: </strong> After 6 moves, the array could be [3, 4, 1, 2, 5, 7].
It can be shown with 5 or less moves that it is impossible for the array to have all unique values.
</pre>

<p>&nbsp;</p>
</div>

<p><strong>Note:</strong></p>

<ol>
	<li><code>0 &lt;= A.length &lt;= 40000</code></li>
	<li><code>0 &lt;= A[i] &lt; 40000</code></li>
</ol>

<div>
<div>&nbsp;</div>
</div>

------

**题目：** 
<p>给定整数数组 A，每次 <em>move</em> 操作将会选择任意&nbsp;<code>A[i]</code>，并将其递增&nbsp;<code>1</code>。</p>

<p>返回使 <code>A</code>&nbsp;中的每个值都是唯一的最少操作次数。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入：</strong>[1,2,2]
<strong>输出：</strong>1
<strong>解释：</strong>经过一次 <em>move</em> 操作，数组将变为 [1, 2, 3]。</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入：</strong>[3,2,1,2,1,7]
<strong>输出：</strong>6
<strong>解释：</strong>经过 6 次 <em>move</em> 操作，数组将变为 [3, 4, 1, 2, 5, 7]。
可以看出 5 次或 5 次以下的 <em>move</em> 操作是不能让数组的每个值唯一的。
</pre>

<p><strong>提示：</strong></p>

<ol>
	<li><code>0 &lt;= A.length &lt;= 40000</code></li>
	<li><code>0 &lt;= A[i] &lt; 40000</code></li>
</ol>

