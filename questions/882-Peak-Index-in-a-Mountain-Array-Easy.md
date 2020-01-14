#### 山脉数组的峰顶索引/Peak Index in a Mountain Array
**难度：** 简单/Easy

**Question：** 

<p>Let&#39;s call an array <code>A</code> a <em>mountain</em>&nbsp;if the following properties hold:</p>

<ul>
	<li><code>A.length &gt;= 3</code></li>
	<li>There exists some <code>0 &lt; i&nbsp;&lt; A.length - 1</code> such that <code>A[0] &lt; A[1] &lt; ... A[i-1] &lt; A[i] &gt; A[i+1] &gt; ... &gt; A[A.length - 1]</code></li>
</ul>

<p>Given an array that is definitely a mountain, return any&nbsp;<code>i</code>&nbsp;such that&nbsp;<code>A[0] &lt; A[1] &lt; ... A[i-1] &lt; A[i] &gt; A[i+1] &gt; ... &gt; A[A.length - 1]</code>.</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-1-1">[0,1,0]</span>
<strong>Output: </strong><span id="example-output-1">1</span>
</pre>

<div>
<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-2-1">[0,2,1,0]</span>
<strong>Output: </strong><span id="example-output-2">1</span></pre>
</div>

<p><strong>Note:</strong></p>

<ol>
	<li><code>3 &lt;= A.length &lt;= 10000</code></li>
	<li><code><font face="monospace">0 &lt;= A[i] &lt;= 10^6</font></code></li>
	<li>A&nbsp;is a mountain, as defined above.</li>
</ol>


------

**题目：** 
<p>我们把符合下列属性的数组&nbsp;<code>A</code>&nbsp;称作山脉：</p>

<ul>
	<li><code>A.length &gt;= 3</code></li>
	<li>存在 <code>0 &lt; i&nbsp;&lt; A.length - 1</code> 使得<code>A[0] &lt; A[1] &lt; ... A[i-1] &lt; A[i] &gt; A[i+1] &gt; ... &gt; A[A.length - 1]</code></li>
</ul>

<p>给定一个确定为山脉的数组，返回任何满足&nbsp;<code>A[0] &lt; A[1] &lt; ... A[i-1] &lt; A[i] &gt; A[i+1] &gt; ... &gt; A[A.length - 1]</code>&nbsp;的 <code>i</code>&nbsp;的值。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[0,1,0]
<strong>输出：</strong>1
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[0,2,1,0]
<strong>输出：</strong>1</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>3 &lt;= A.length &lt;= 10000</code></li>
	<li>0 &lt;= A[i] &lt;= 10^6</li>
	<li>A 是如上定义的山脉</li>
</ol>

<p>&nbsp;</p>
