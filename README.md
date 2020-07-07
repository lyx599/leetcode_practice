# leetcode_practice
leetcode刷题记录

# 分类归纳

- [数组](#数组)
- [栈](#栈)
- [队列](#队列)
- [链表](#链表)
- [树](#树)
- [数学](#数学)
- [字符串](#字符串)
- [贪心算法](#贪心算法)
- [DFS](#DFS)
- [BFS](#BFS)
- [双指针](#双指针)
- [动态规划](#动态规划)
- [递归](#递归)
- [回溯](#回溯)
- [分治](#分治)
- [位运算](#位运算)





## 数组

| 编号          | 题目                                                         | 备注               |
| :------------ | ------------------------------------------------------------ | ------------------ |
| 01            | [两数之和](https://leetcode-cn.com/problems/two-sum)         |                    |
| 11            | [盛最多水的容器](https://leetcode-cn.com/problems/container-with-most-water) |                    |
| 15            | [三数之和](https://leetcode-cn.com/problems/3sum)            |                    |
| 16            | [ 最接近的三数之和](https://leetcode-cn.com/problems/3sum-closest) |                    |
| 18            | [四数之和](https://leetcode-cn.com/problems/4sum)            |                    |
| 26            | [删除排序数组中的重复项](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array) |                    |
| 27            | [移除元素](https://leetcode-cn.com/problems/remove-element)  |                    |
| 31            | [下一个排列](https://leetcode-cn.com/problems/next-permutation) |                    |
| 面试题03      | [ 数组中重复的数字](https://leetcode-cn.com/problems/shu-zu-zhong-zhong-fu-de-shu-zi-lcof) | 哈希表，代码鲁棒性 |
| 面试题04      | [二维数组中的查找](https://leetcode-cn.com/problems/er-wei-shu-zu-zhong-de-cha-zhao-lcof) | 利用递增的规律     |
| 面试题05      | [替换空格](https://leetcode-cn.com/problems/ti-huan-kong-ge-lcof) |                    |
| 面试题11      | [旋转数组的最小数字](https://leetcode-cn.com/problems/xuan-zhuan-shu-zu-de-zui-xiao-shu-zi-lcof) |                    |
| 剑指 Offer 21 | [调整数组顺序使奇数位于偶数前面](https://leetcode-cn.com/problems/diao-zheng-shu-zu-shun-xu-shi-qi-shu-wei-yu-ou-shu-qian-mian-lcof) | 双指针降低复杂度   |
| 剑指 Offer 29 | [顺时针打印矩阵](https://leetcode-cn.com/problems/shun-shi-zhen-da-yin-ju-zhen-lcof) | 模拟               |
| 剑指 Offer 39 | [数组中出现次数超过一半的数字](https://leetcode-cn.com/problems/shu-zu-zhong-chu-xian-ci-shu-chao-guo-yi-ban-de-shu-zi-lcof) | 利用性质：投票法   |



## 栈

| 编号          | 题目                                                         | 备注                   |
| :------------ | ------------------------------------------------------------ | ---------------------- |
| 20            | [有效的括号](https://leetcode-cn.com/problems/valid-parentheses) |                        |
| 面试题09      | [用两个栈实现队列](https://leetcode-cn.com/problems/yong-liang-ge-zhan-shi-xian-dui-lie-lcof) |                        |
| 剑指 Offer 30 | [包含min函数的栈](https://leetcode-cn.com/problems/bao-han-minhan-shu-de-zhan-lcof) | 构造辅助栈，减小复杂度 |
| 剑指 Offer 31 | [栈的压入、弹出序列](https://leetcode-cn.com/problems/zhan-de-ya-ru-dan-chu-xu-lie-lcof) | 通过模拟来解决         |

## 队列

| 编号 | 题目 | 备注 |
| :--- | ---- | ---- |
|      |      |      |

## 链表

| 编号          | 题目                                                         | 备注   |
| :------------ | ------------------------------------------------------------ | ------ |
| 2             | [两数相加](https://leetcode-cn.com/problems/add-two-numbers) |        |
| 19            | [删除链表的倒数第N个节点](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list) |        |
| 21            | [合并两个有序链表](https://leetcode-cn.com/problems/merge-two-sorted-lists) |        |
| 24            | [两两交换链表中的节点](https://leetcode-cn.com/problems/swap-nodes-in-pairs) |        |
| 面试题06      | [从尾到头打印链表](https://leetcode-cn.com/problems/cong-wei-dao-tou-da-yin-lian-biao-lcof) |        |
| 面试题18      | [删除链表的节点](https://leetcode-cn.com/problems/shan-chu-lian-biao-de-jie-dian-lcof) |        |
| 剑指 Offer 22 | [链表中倒数第k个节点](https://leetcode-cn.com/problems/lian-biao-zhong-dao-shu-di-kge-jie-dian-lcof) | 双指针 |
| 剑指 Offer 24 | [反转链表](https://leetcode-cn.com/problems/fan-zhuan-lian-biao-lcof) |        |
| 剑指 Offer 25 | [合并两个排序的链表](https://leetcode-cn.com/problems/he-bing-liang-ge-pai-xu-de-lian-biao-lcof) |        |

## 树

| 编号                | 题目                                                         | 备注                                     |
| :------------------ | ------------------------------------------------------------ | ---------------------------------------- |
|                     | 树的解法一般都有递归和迭代两种                               |                                          |
| 面试题07            | [重建二叉树](https://leetcode-cn.com/problems/zhong-jian-er-cha-shu-lcof) |                                          |
| 剑指 Offer 26       | [树的子结构](https://leetcode-cn.com/problems/shu-de-zi-jie-gou-lcof) |                                          |
| 剑指 Offer 27       | [二叉树的镜像](https://leetcode-cn.com/problems/er-cha-shu-de-jing-xiang-lcof) | 递归交换左右节点                         |
| 剑指 Offer 28       | [对称的二叉树](https://leetcode-cn.com/problems/dui-cheng-de-er-cha-shu-lcof) | 根据性质：左右对称，递归                 |
| 剑指 Offer 32 - I   | [从上到下打印二叉树](https://leetcode-cn.com/problems/cong-shang-dao-xia-da-yin-er-cha-shu-lcof) | 层序遍历                                 |
| 剑指 Offer 32 - II  | [从上到下打印二叉树 II](https://leetcode-cn.com/problems/cong-shang-dao-xia-da-yin-er-cha-shu-ii-lcof) | 层序遍历                                 |
| 剑指 Offer 32 - III | [从上到下打印二叉树 III](https://leetcode-cn.com/problems/cong-shang-dao-xia-da-yin-er-cha-shu-iii-lcof) | 层序遍历                                 |
| 剑指 Offer 33       | [二叉搜索树的后序遍历序列](https://leetcode-cn.com/problems/er-cha-sou-suo-shu-de-hou-xu-bian-li-xu-lie-lcof) | 基于性质，逆序后序遍历的输出再使用单调栈 |
| 剑指 Offer 33       | [二叉搜索树的后序遍历序列](https://leetcode-cn.com/problems/er-cha-sou-suo-shu-de-hou-xu-bian-li-xu-lie-lcof) |                                          |
| 剑指 Offer 34       | [二叉树中和为某一值的路径](https://leetcode-cn.com/problems/er-cha-shu-zhong-he-wei-mou-yi-zhi-de-lu-jing-lcof) | 回溯法，迭代法                           |
| 剑指 Offer 36       | [二叉搜索树与双向链表](https://leetcode-cn.com/problems/er-cha-sou-suo-shu-yu-shuang-xiang-lian-biao-lcof) | 基于性质：中序遍历                       |

## 数学

| 编号 | 题目                                                         | 备注 |
| :--- | ------------------------------------------------------------ | ---- |
| 02   | [两数相加](https://leetcode-cn.com/problems/add-two-numbers) |      |
| 07   | [整数反转](https://leetcode-cn.com/problems/reverse-integer) |      |
| 08   | [ 字符串转换整数 (atoi)](https://leetcode-cn.com/problems/string-to-integer-atoi) |      |
| 09   | [回文数](https://leetcode-cn.com/problems/palindrome-number) |      |
| 12   | [整数转罗马数字](https://leetcode-cn.com/problems/integer-to-roman) |      |
| 13   | [罗马数字转整数](https://leetcode-cn.com/problems/roman-to-integer) |      |

## 字符串

| 编号          | 题目                                                         | 备注           |
| :------------ | ------------------------------------------------------------ | -------------- |
| 03            | [无重复字符的最长子串](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters) |                |
| 05            | [最长回文子串](https://leetcode-cn.com/problems/longest-palindromic-substring) |                |
| 06            | [Z 字形变换](https://leetcode-cn.com/problems/zigzag-conversion) |                |
| 08            | [ 字符串转换整数 (atoi)](https://leetcode-cn.com/problems/string-to-integer-atoi) |                |
| 12            | [整数转罗马数字](https://leetcode-cn.com/problems/integer-to-roman) |                |
| 13            | [罗马数字转整数](https://leetcode-cn.com/problems/roman-to-integer) |                |
| 14            | [最长公共前缀](https://leetcode-cn.com/problems/longest-common-prefix) |                |
| 17            | [电话号码的字母组合](https://leetcode-cn.com/problems/letter-combinations-of-a-phone-number) |                |
| 20            | [有效的括号](https://leetcode-cn.com/problems/valid-parentheses) |                |
| 22            | [ 括号生成](https://leetcode-cn.com/problems/generate-parentheses) |                |
| 28            | [实现 strStr()](https://leetcode-cn.com/problems/implement-strstr) | KMP算法（☆）   |
| 剑指 Offer 20 | [表示数值的字符串](https://leetcode-cn.com/problems/biao-shi-shu-zhi-de-zi-fu-chuan-lcof) | 有限状态自动机 |

## 贪心算法

| 编号         | 题目                                                         | 备注 |
| :----------- | ------------------------------------------------------------ | ---- |
| 面试题14- I  | [剪绳子](https://leetcode-cn.com/problems/jian-sheng-zi-lcof) |      |
| 面试题14- II | [剪绳子 II](https://leetcode-cn.com/problems/jian-sheng-zi-ii-lcof) |      |

## DFS

| 编号          | 题目                                                         | 备注                                   |
| :------------ | ------------------------------------------------------------ | -------------------------------------- |
| 面试题12      | [矩阵中的路径](https://leetcode-cn.com/problems/ju-zhen-zhong-de-lu-jing-lcof) |                                        |
| 面试题17      | [打印从1到最大的n位数](https://leetcode-cn.com/problems/da-yin-cong-1dao-zui-da-de-nwei-shu-lcof) | 大数问题                               |
| 剑指 Offer 35 | [复杂链表的复制](https://leetcode-cn.com/problems/fu-za-lian-biao-de-fu-zhi-lcof) | 此题把链表当成图来理解，DFS和BFS都能用 |

## BFS

| 编号          | 题目                                                         | 备注     |
| :------------ | ------------------------------------------------------------ | -------- |
| 面试题13      | [机器人的运动范围](https://leetcode-cn.com/problems/ji-qi-ren-de-yun-dong-fan-wei-lcof) |          |
| 剑指 Offer 37 | [序列化二叉树](https://leetcode-cn.com/problems/xu-lie-hua-er-cha-shu-lcof) | 层序遍历 |

## 双指针

| 编号 | 题目                                                         | 备注 |
| :--- | ------------------------------------------------------------ | ---- |
| 03   | [无重复字符的最长子串](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters) |      |
| 11   | [盛最多水的容器](https://leetcode-cn.com/problems/container-with-most-water) |      |
| 15   | [三数之和](https://leetcode-cn.com/problems/3sum)            |      |
| 16   | [ 最接近的三数之和](https://leetcode-cn.com/problems/3sum-closest) |      |
| 18   | [四数之和](https://leetcode-cn.com/problems/4sum)            |      |
| 19   | [ 删除链表的倒数第N个节点](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list) |      |

## 动态规划

| 编号         | 题目                                                         | 备注               |
| :----------- | ------------------------------------------------------------ | ------------------ |
| 面试题14- I  | [剪绳子](https://leetcode-cn.com/problems/jian-sheng-zi-lcof) |                    |
| 面试题14- II | [剪绳子 II](https://leetcode-cn.com/problems/jian-sheng-zi-ii-lcof) |                    |
| 面试题19     | [正则表达式匹配](https://leetcode-cn.com/problems/zheng-ze-biao-da-shi-pi-pei-lcof) | 困难，主要状态分析 |

## 递归

| 编号         | 题目                                                         | 备注 |
| :----------- | ------------------------------------------------------------ | ---- |
| 面试题10- I  | [斐波那契数列](https://leetcode-cn.com/problems/fei-bo-na-qi-shu-lie-lcof) |      |
| 面试题10- II | [青蛙跳台阶问题](https://leetcode-cn.com/problems/qing-wa-tiao-tai-jie-wen-ti-lcof) |      |
| 面试题17     | [打印从1到最大的n位数](https://leetcode-cn.com/problems/da-yin-cong-1dao-zui-da-de-nwei-shu-lcof) |      |

## 回溯

| 编号          | 题目                                                         | 备注           |
| :------------ | ------------------------------------------------------------ | -------------- |
| 17            | [电话号码的字母组合](https://leetcode-cn.com/problems/letter-combinations-of-a-phone-number) |                |
| 22            | [ 括号生成](https://leetcode-cn.com/problems/generate-parentheses) |                |
| 面试题12      | [矩阵中的路径](https://leetcode-cn.com/problems/ju-zhen-zhong-de-lu-jing-lcof) |                |
| 面试题13      | [机器人的运动范围](https://leetcode-cn.com/problems/ji-qi-ren-de-yun-dong-fan-wei-lcof) |                |
| 剑指 Offer 34 | [二叉树中和为某一值的路径](https://leetcode-cn.com/problems/er-cha-shu-zhong-he-wei-mou-yi-zhi-de-lu-jing-lcof) | 回溯法         |
| 剑指 Offer 38 | [字符串的排列](https://leetcode-cn.com/problems/zi-fu-chuan-de-pai-lie-lcof) | 交换位置很巧妙 |

## 分治

| 编号          | 题目                                                         | 备注     |
| :------------ | ------------------------------------------------------------ | -------- |
| 剑指 Offer 33 | [二叉搜索树的后序遍历序列](https://leetcode-cn.com/problems/er-cha-sou-suo-shu-de-hou-xu-bian-li-xu-lie-lcof) | 递归分治 |

## 位运算

| 编号     | 题目                                                         | 备注 |
| :------- | ------------------------------------------------------------ | ---- |
| 29       | [两数相除](https://leetcode-cn.com/problems/divide-two-integers) |      |
| 面试题15 | [二进制中1的个数](https://leetcode-cn.com/problems/er-jin-zhi-zhong-1de-ge-shu-lcof) |      |