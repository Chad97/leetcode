#### 不同的二叉搜索树 II/Unique Binary Search Trees II
**难度：** 中等/Medium

**Question：** 

<p>Given an integer <em>n</em>, generate all structurally unique <strong>BST&#39;s</strong> (binary search trees) that store values 1 ...&nbsp;<em>n</em>.</p>

<p><strong>Example:</strong></p>

<pre>
<strong>Input:</strong> 3
<strong>Output:</strong>
[
&nbsp; [1,null,3,2],
&nbsp; [3,2,null,1],
&nbsp; [3,1,null,null,2],
&nbsp; [2,1,3],
&nbsp; [1,null,2,null,3]
]
<strong>Explanation:</strong>
The above output corresponds to the 5 unique BST&#39;s shown below:

   1         3     3      2      1
    \       /     /      / \      \
     3     2     1      1   3      2
    /     /       \                 \
   2     1         2                 3
</pre>


------

**题目：** 
<p>给定一个整数 <em>n</em>，生成所有由 1 ...&nbsp;<em>n</em> 为节点所组成的<strong>二叉搜索树</strong>。</p>

<p><strong>示例:</strong></p>

<pre><strong>输入:</strong> 3
<strong>输出:</strong>
[
&nbsp; [1,null,3,2],
&nbsp; [3,2,null,1],
&nbsp; [3,1,null,null,2],
&nbsp; [2,1,3],
&nbsp; [1,null,2,null,3]
]
<strong>解释:</strong>
以上的输出对应以下 5 种不同结构的二叉搜索树：

   1         3     3      2      1
    \       /     /      / \      \
     3     2     1      1   3      2
    /     /       \                 \
   2     1         2                 3
</pre>

