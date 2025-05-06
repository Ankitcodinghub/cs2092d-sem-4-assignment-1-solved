# cs2092d-sem-4-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS2092D Sem 4 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs2092d-sem-4-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97464&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2092D Sem 4 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<u>QUESTIONS </u>

<ol>
<li>A BINARY TREE is a rooted tree in which each node is an object that contains a key value. In addition to a key and satellite data, each node contains attributes left, right, and p that point to the nodes corresponding to its left child, its right child, and its parent, respectively. If a child or the parent is missing, the appropriate attribute contains the value NIL. The root node is the only node in the tree whose parent is NIL. The PARENTHESIS REPRESENTATION of a binary tree is recursively defined as given below.</li>
</ol>
<ul>
<li>The string ( ) represents an empty tree.</li>
<li>The string ( k left-subtree right-subtree ) represents a tree whose root node has key k, left­subtree is the left subtree of the root node in PARENTHESIS REPRESENTATION and right­subtree is the right subtree of the root node in PARENTHESIS REPRESENTATION.</li>
</ul>
Write a program to create a binary tree T and print T in PARENTHESIS REPRESENTATION. Your program should contain the following functions:

<ul>
<li>INSERT(T, k) – inserts the element k to the tree T.</li>
</ul>
Note: To insert an element k into a binary tree T, do a level order traversal of the given tree T. If we find a node whose left child is empty, make new key k as left child of the node. Else if we find a node whose right child is empty, make the new key k as right child. i.e., keep traversing the tree until we find a node whose either left or right child is empty.

<ul>
<li>PRINT(T) – that should take as input a pointer to the root node of a binary tree and print the tree in its PARENTHESIS REPRESENTATION.</li>
</ul>
Input format:

<ul>
<li>Each line contains a character from ‘i’, ‘p’and ‘e’ followed by at most one integer. The integers, if given, are in the range<sup> [</sup><sup>_</sup><sup>106</sup><sup>,</sup> 10<sup>6</sup>].</li>
<li>Character ‘i’ is followed by an integer separated by space. In this operation, a node with this integer as key is created and inserted into T.</li>
<li>Character ‘p’ is to print the PARENTHESIS REPRESENTATION of the tree T.</li>
<li>Character ‘e’ is to ‘exit’ from the program.</li>
</ul>
Output Format:

<ul>
<li>The output is the space separated PARENTHESIS REPRESENTATION of the tree T.</li>
</ul>
Sample Input:

i 4

i 3

i 9

i 5

i 6 i 1 i 8 p

e

Sample Output:

( 4 ( 3 ( 5 ( ) ( ) ) ( 6 ( ) ( ) ) ) ( 9 ( 1 ( ) ( ) ) ( 8 ( ) ( ) ) ) )

<ol start="2">
<li>In a binary tree, two nodes are cousins of each other if they are at the same level and have different parents. Given a binary tree T and a node x, write a program to print all cousins of the given node x. If x has no cousins, print -1. Assume that T contains no duplicate nodes. Note that siblings of x should not be printed.</li>
</ol>
&nbsp;

Input format:

<ul>
<li>The integers, if given, are in the range [_10<sup>6</sup>, 10<sup>6</sup>].</li>
<li>First line of the input contains space separated PARENTHESIS REPRESENTATION of the tree T.</li>
<li>Second line contains the integer k. Output format:</li>
<li>The output is the cousins of the node x with input integer k as key separated by a space. If x has no cousins, print -1.</li>
</ul>
Sample Input 1 :

( 4 ( 3 ( 5 ( ) ( ) ) ( 6 ( ) ( ) ) ) ( 9 ( 1 ( ) ( ) ) ( 8 ( ) ( ) ) ) ) 6

Sample Output 1 :

1 8

Sample Input 2 :

( 4 ( 3 ( 5 ( ) ( ) ) ( 6 ( ) ( ) ) ) ( 9 ( ) ( ) ) ) 6

Sample Output 2 :

-1

<ol start="3">
<li>Given a binary tree T, write a program to count the total number of sub-trees of T which is also a Binary Search Tree (BST) and the sum of all the nodes of that BST is equal to the given sum k. If no such sub-trees are present, print -1.</li>
</ol>
Input Format:

<ul>
<li>The integers, if given, are in the range<sup> [_106</sup><sup>,</sup> 10<sup>6</sup>].</li>
<li>First line of the input contains space separated PARENTHESIS REPRESENTATION of the tree T.</li>
<li>Second line of the input contains the integer value k. Output Format:</li>
<li>Print the total number of BST whose sum is equal to given k. If no such sub-trees are present, print -1.</li>
</ul>
Sample Input 1:

<table>
<tbody>
<tr>
<td width="138">( 5 ( 4 ( 3 ( ) ( ) )</td>
<td width="21">( 6</td>
<td width="19">( )</td>
<td width="19">( )</td>
<td width="20">) )</td>
<td width="21">( 3</td>
<td width="20">( 1</td>
<td width="19">( )</td>
<td width="19">( )</td>
<td width="19">)&nbsp;&nbsp; (</td>
<td width="21">9 (</td>
<td width="19">)&nbsp;&nbsp; (</td>
<td width="19">) )</td>
<td width="214">) )</td>
</tr>
<tr>
<td width="138">13</td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="20"></td>
<td width="21"></td>
<td width="20"></td>
<td width="19"></td>
<td width="19"></td>
<td width="19"></td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="214"></td>
</tr>
<tr>
<td width="138">Sample Output 1:</td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="20"></td>
<td width="21"></td>
<td width="20"></td>
<td width="19"></td>
<td width="19"></td>
<td width="19"></td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="214"></td>
</tr>
<tr>
<td width="138">2</td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="20"></td>
<td width="21"></td>
<td width="20"></td>
<td width="19"></td>
<td width="19"></td>
<td width="19"></td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="214"></td>
</tr>
<tr>
<td width="138">Sample Input 2:</td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="20"></td>
<td width="21"></td>
<td width="20"></td>
<td width="19"></td>
<td width="19"></td>
<td width="19"></td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="214"></td>
</tr>
<tr>
<td width="138">( 5 ( 4 ( 3 ( ) ( ) )</td>
<td width="21">( 3</td>
<td width="19">( )</td>
<td width="19">( )</td>
<td width="20">) )</td>
<td width="21">( 6</td>
<td width="20">( 1</td>
<td width="19">( )</td>
<td width="19">( )</td>
<td width="19">)&nbsp;&nbsp; (</td>
<td width="21">9 (</td>
<td width="19">)&nbsp;&nbsp; (</td>
<td width="19">) )</td>
<td width="214">) )</td>
</tr>
<tr>
<td width="138">2</td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="20"></td>
<td width="21"></td>
<td width="20"></td>
<td width="19"></td>
<td width="19"></td>
<td width="19"></td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="214"></td>
</tr>
<tr>
<td width="138">Sample Output 2:</td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="20"></td>
<td width="21"></td>
<td width="20"></td>
<td width="19"></td>
<td width="19"></td>
<td width="19"></td>
<td width="21"></td>
<td width="19"></td>
<td width="19"></td>
<td width="214"></td>
</tr>
</tbody>
</table>
-1

&nbsp;

<ol start="4">
<li>The BINARY SEARCH TREE (BST) data structure supports many of the dynamic-set operations. A BST is organized as a binary tree in which each node is an object that contains a key value. In addition to a key and satellite data, each node contains attributes left, right, and p that point to the nodes corresponding to its left child, its right child, and its parent, respectively. If a child or the parent is missing, the appropriate attribute contains the value NIL. The root node is the only node in the tree whose parent is NIL. The keys in a binary search tree are always stored in such a way as to satisfy the binary-search-tree property:</li>
</ol>
<ul>
<li>Let x be a node in a binary search tree. If y is a node in the left subtree of x, thenkey<em> &lt; </em>x.key. If y is a node in the right subtree of x, then y.key<em> &gt; </em>x.key.</li>
</ul>
Write a program to create a BINARY SEARCH TREE T and perform the operations insertion, dele­tion, search, find level, find minimum, find maximum, predecessor, successor and traversals(inorder, preorder and postorder) on T. Input should be read from console and output should be shown in console. Your program should include the following functions.

<ul>
<li>MAIN() – creates the Binary Search Tree T with T as the root node (which is NIL initially) and repeatedly reads a character ca’, cd’, cs’, cl’, cm’, cx’, cr’, cu’, ci’, cp’, ct’ or ce’ from the console and calls the sub-functions appropriately until character ce’ is entered.</li>
<li>CREATENODE(k) creates a new node with key value k and returns a pointer to the new node. All the pointer attributes of the new node are set to NIL.</li>
<li>INSERT(T, x) – inserts the node x into the BST T.</li>
</ul>
Note: The caller of this function is assumed to create the node x using the CREATENODE() function.

<ul>
<li>DELETE(T, x) – deletes the node x from the BST T.</li>
</ul>
Note: The caller of this function is assumed to invoke SEARCH() function to locate the node x.

<ul>
<li>SEARCH(T, k) – searches for a node with key k in T, and returns a pointer to a node with key k if one exists; otherwise, it returns NIL.</li>
<li>LEVEL(T, k) – searches for a node with key k in T, and returns the level of the node with key k if one exists; otherwise, it returns NIL.</li>
<li>MINVALUE(T) returns the minimum value in the BST T.</li>
<li>MAXVALUE(T) returns the maximum value in the BST T.</li>
<li>PREDECESSOR(T, y) – searches for a node with key y in T, and returns a pointer to a node which is predecessor of the node with key y if one exists; otherwise, it returns NIL.</li>
<li>SUCCESSOR(T, y) – searches for a node with key y in T, and returns a pointer to a node which is successor of the node with key y if one exists; otherwise, it returns NIL.</li>
<li>INORDER(T) – performs recursive inorder traversal of the BST T and prints the data in the nodes of T in inorder.</li>
<li>PREORDER(T) performs recursive preorder traversal of the BST T and prints the data in the nodes of T in preorder.</li>
<li>POSTORDER(T) performs recursive postorder traversal of the BST T and prints the data in the nodes of T in postorder.</li>
</ul>
Input format:

<ul>
<li>Each line contains a character from ca’, cd’, cs’, cl’, cm’, cx’, cr’, cu’, ci’, cp’, ct’ or ce’ followed by at most one integer. The integers, if given, are in the range<sup> [_106</sup><sup>,</sup> 10<sup>6</sup>].</li>
<li>Character ca’ is followed by an integer separated by space. In this operation, a node with this integer as key is created and inserted into T.</li>
<li>Character cd’ is followed by an integer separated by space. In this operation, the node with this integer as key is deleted from T and the deleted node’s key is printed.</li>
</ul>
&nbsp;

<ul>
<li>Character ‘s’ is followed by an integer separated by space. This operation is to find the node with this integer as key in T.</li>
<li>Character ‘l’ is followed by an integer separated by space. This operation is to find the level of the node with this integer as key in T.</li>
<li>Character ‘m’ is to find the minimum value of T.</li>
<li>Character ‘x’ is to find the maximum value of T.</li>
<li>Character ‘r’ is followed by an integer separated by space. This operation is to find the predecessor of the node with this integer as key in T.</li>
<li>Character ‘u’ is followed by an integer separated by space. This operation is to find the successor of the node with this integer as key in T.</li>
<li>Character ‘i’ is to perform inorder traversal of T.</li>
<li>Character ‘p’ is to perform preorder traversal of T.</li>
<li>Character ‘t’ is to perform postorder traversal of T.</li>
<li>Character ‘e’ is to ‘exit’ from the program.</li>
</ul>
Output Format:

<ul>
<li>The output (if any) of each command should be printed on a separate line.</li>
<li>For option ‘d’, print the deleted node’s key. If a node with the input key is not present in T, then print -1.</li>
<li>For option ‘s’, if the key is present in T, then print 1. If key is not present in T, then print -1.</li>
<li>For option‘l’, if the key is present in T, then print its level. If key is not present in T, then print -1.</li>
<li>For option ‘m’, print the minimum value of T.</li>
<li>For option ‘x’, print the maximum value of T.</li>
<li>For option ‘r’, if the key is present in T, then print its predecessor. If key is not present in T, then print -1.</li>
<li>For option ‘u’, if the key is present in T, then print its successor. If key is not present in T, then print -1.</li>
<li>For option ‘i’, print the data in the nodes of T obtained from inorder traversal.</li>
<li>For option ‘p’, print the data in the nodes of T obtained from preorder traversal.</li>
<li>For option ‘t’, print the data in the nodes of T obtained from postorder traversal.</li>
</ul>
Sample Input:

a 25 a 13 a 50 a 45 a 55 a 18 l 50

l 19

m

x

r 25 u 30 u 25 i

p

t

s 10

&nbsp;

s 25 d 55 d 13 d 10

d 25 i

s 25

e

Sample Output:

2

-1

13 55 18 -1

45

13 18 25 45 50 55

25 13 18 50 45 55

18 13 45 55 50 25

-1

1

55 13 -1

25

18 45 50

-1

<ol start="5">
<li>Given a Binary Search Tree(BST) T and a key value k. Write a program that implements the following function:</li>
</ol>
KSMALLEST(T, k) : Takes as input the root of a BST T and an integer k, such that k<em> &lt; </em>n, where n is the number of nodes in T and returns the k-th smallest value in the BST T. Note that n is not part of the input. Input Format:

<ul>
<li>The integers, if given, are in the range<sup> [_106</sup><sup>,</sup> 10<sup>6</sup>].</li>
<li>First line of the input contains space separated PARENTHESIS REPRESENTATION of the tree T.</li>
<li>Second line contains the integer k.</li>
</ul>
Output Format:

<ul>
<li>Print the kth smallest element in the BST.</li>
</ul>
Sample Input 1:

( 8 ( 5 ( 3 ( ) ( ) ) ( 6 ( ) ( ) ) ) ( 13 ( 10 ( ) ( ) ) ( 19 ( ) ( ) ) ) ) 5

Sample Output 1:

10

<ol start="6">
<li>Given a list of n numbers sorted in ascending order, develop a program to determine the order in which these elements should be inserted into a BST such that the tree construction should be completed in O(nlogn) time.(ie. the tree should be height balanced). Print the BST created by maintaining this property. Also find the level-wise sum of the elements in the tree, starting from root to leaf.</li>
</ol>
&nbsp;

Note: To insert n nodes into a BST you need to make at least O(logn) comparisons. Hence the time complexity for the construction of BST with n elements will be minimum as O(n log n).

Input Format:

<ul>
<li>The integers, if given, are in the range<sup> [_106</sup><sup>,</sup> 10<sup>6</sup>].</li>
<li>Read the number of elements n in the tree.</li>
<li>Second line of the input should contain space separated integers(n in number) in ascending</li>
</ul>
Output Format:

<ul>
<li>First line of the output should contain space separated PARENTHESIS REPRESENTATION of the tree T.</li>
<li>Next line of the output should contain level sums starting from root ([log n<em>] </em>+ 1 entries) separated by single space.</li>
</ul>
Sample Input 1: 7

18 20 24 30 36 50 51

Sample Output 1:

( 30 ( 20 ( 18 ( ) ( ) ) ( 24 ( ) ( ) ) ) ( 50 ( 36 ( ) ( ) ) ( 51 ( ) ( ) ) ) )

30 70 129
