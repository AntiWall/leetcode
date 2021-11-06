https://github.com/labuladong/fucking-algorithm
# monotone stack
母题：

496. Next Greater Element I
https://leetcode.com/problems/next-greater-element-i/

解析：
https://www.youtube.com/watch?v=KZhjUwuMC0Y

找下一个最大，下一个最小

- 901 https://leetcode.com/problems/online-stock-span
- 85 https://leetcode.com/problems/maximal-rectangle/

这题分成两部分，先构建H 高度数组，然后通过单调栈来找 数组的连续最大高度

- 1008 https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/

思路： 二叉搜索树，要求所有的数必须严格大于和小于根节点，通过找下一个比根节点大的，来构建单调栈


https://leetcode.com/problems/daily-temperatures/
https://leetcode.com/problems/shortest-unsorted-continuous-subarray/
496. Next Greater Element I
https://leetcode.com/problems/next-greater-element-i/
https://leetcode.com/problems/next-greater-element-ii/
https://leetcode.com/problems/online-stock-span/
https://leetcode.com/problems/132-pattern/
https://leetcode.com/problems/sum-of-subarray-minimums/
https://leetcode.com/problems/largest-rectangle-in-histogram/

https://www.youtube.com/watch?v=m4hvxzLoN_I

# 二叉搜索树 BST
783. Minimum Distance Between BST Nodes

https://leetcode.com/problems/minimum-distance-between-bst-nodes/

这个中序遍历需要多复习


- 1008 https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/

# Stack
388. Longest Absolute File Path https://leetcode.com/problems/longest-absolute-file-path/

注意点： \n \t 是一个char

用stack模拟dfs

split用法，lastIndexOf用法，没有的时候返回-1

# DP
2d dp 母題，非常简单。
62. Unique Paths
https://leetcode.com/problems/unique-paths/


279. Perfect Squares : https://leetcode.com/problems/perfect-squares/

121. Best Time to Buy and Sell Stock
https://leetcode.com/problems/best-time-to-buy-and-sell-stock/

122. Best Time to Buy and Sell Stock II
https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/

123. https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/

309. Best Time to Buy and Sell Stock with Cooldown
https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/

can refer to this:
https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/discuss/75931/Easiest-JAVA-solution-with-explanations



# Tree
129. Sum Root to Leaf Numbers
[https://leetcode.com/problems/sum-root-to-leaf-numbers/]
母题

437. Path Sum III https://leetcode.com/problems/path-sum-iii/
用prefix sum优化（就是 2 sum的hashmap方法)



# BFS
母题1
111. Minimum Depth of Binary Tree
https://leetcode.com/problems/minimum-depth-of-binary-tree/

母题2
200. 

母题3
994. Rotting Oranges
https://leetcode.com/problems/rotting-oranges/


993. Cousins in Binary Tree https://leetcode.com/problems/cousins-in-binary-tree/
简单题

102. Binary Tree Level Order Traversal https://leetcode.com/problems/binary-tree-level-order-traversal/
简单题

# DFS

130. Surrounded Regions https://leetcode.com/problems/surrounded-regions/

这题主要是注意一下 ||的用法，以及dfs返回值可以是boolean

980. Unique Paths III[https://leetcode.com/problems/unique-paths-iii/]

标准dfs！

# String

151. Reverse Words in a String
https://leetcode.com/problems/reverse-words-in-a-string/

541. Reverse String II
https://leetcode.com/problems/reverse-string-ii/

# random
380. Insert Delete GetRandom O(1)
https://leetcode.com/problems/insert-delete-getrandom-o1/

插入和删除是O(1)， 但是随机必须维护一个array，否则得O(1),那array O(1)删除方法就是交换队尾和待删除元素，那么删除队尾，就是O(1)

381. Insert Delete GetRandom O(1) - Duplicates allowed
https://leetcode.com/problems/insert-delete-getrandom-o1-duplicates-allowed/

# Math
1018. Binary Prefix Divisible By 5
https://leetcode.com/problems/binary-prefix-divisible-by-5/

# priority Queue

451. Sort Characters By Frequency
https://leetcode.com/problems/sort-characters-by-frequency/

这题还可以用桶排序做，可以看看

# binary search
154. Find Minimum in Rotated Sorted Array II

https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/

最难的binary search，所有的边界条件都是定死的，一定要注意不能rule out correct answer


540. Single Element in a Sorted Array

https://leetcode.com/problems/single-element-in-a-sorted-array/

可以思考一下怎么优化代码，答案写的都不是很好

# bit manipulation

260. Single Number III[https://leetcode.com/problems/single-number-iii/]
这题是XOR，非常麻烦得看一下注释