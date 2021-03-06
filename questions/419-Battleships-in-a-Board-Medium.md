#### 甲板上的战舰/Battleships in a Board
**难度：** 中等/Medium

**Question：** 

Given an 2D board, count how many battleships are in it. The battleships are represented with <code>'X'</code>s, empty slots are represented with <code>'.'</code>s. You may assume the following rules:

<ul>
<li>You receive a valid board, made of only battleships or empty slots.</li>
<li>Battleships can only be placed horizontally or vertically. In other words, they can only be made of the shape <code>1xN</code> (1 row, N columns) or <code>Nx1</code> (N rows, 1 column), where N can be of any size.</li>
<li>At least one horizontal or vertical cell separates between two battleships - there are no adjacent battleships.</li>
</ul>

<p><b>Example:</b><br />
<pre>X..X
...X
...X
</pre>
In the above board there are 2 battleships.

<p><b>Invalid Example:</b><br />
<pre>...X
XXXX
...X
</pre>
This is an invalid board that you will not receive - as battleships will always have a cell separating between them.
<p></p>
<p><b>Follow up:</b><br>Could you do it in <b>one-pass</b>, using only <b>O(1) extra memory</b> and <b>without modifying</b> the value of the board?</p>

------

**题目：** 
<p>给定一个二维的甲板， 请计算其中有多少艘战舰。&nbsp;战舰用&nbsp;<code>&#39;X&#39;</code>表示，空位用&nbsp;<code>&#39;.&#39;</code>表示。&nbsp;你需要遵守以下规则：</p>

<ul>
	<li>给你一个有效的甲板，仅由战舰或者空位组成。</li>
	<li>战舰只能水平或者垂直放置。换句话说,战舰只能由&nbsp;<code>1xN</code> (1 行, N 列)组成，或者&nbsp;<code>Nx1</code> (N 行, 1 列)组成，其中N可以是任意大小。</li>
	<li>两艘战舰之间至少有一个水平或垂直的空位分隔&nbsp;- 即没有相邻的战舰。</li>
</ul>

<p><strong>示例 :</strong></p>

<pre>
X..X
...X
...X
</pre>

<p>在上面的甲板中有2艘战舰。</p>

<p><strong>无效样例 :</strong></p>

<pre>
...X
XXXX
...X
</pre>

<p>你不会收到这样的无效甲板&nbsp;- 因为战舰之间至少会有一个空位将它们分开。</p>

<p><strong>进阶:</strong></p>

<p>你可以用<strong>一次扫描算法</strong>，只使用<strong>O(1)额外空间，</strong>并且<strong>不修改</strong>甲板的值来解决这个问题吗？</p>

