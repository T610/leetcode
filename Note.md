# leetcode

[  ](  )
## 10月11日	 周赛
[1614. 括号的最大嵌套深度](https://leetcode-cn.com/problems/maximum-nesting-depth-of-the-parentheses/)  

[1615. 最大网络秩](https://leetcode-cn.com/problems/maximal-network-rank/)

## 10月17日
[  235. 二叉搜索树的最近公共祖先 ](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-search-tree/submissions/)  

[590. N叉树的后序遍历](https://leetcode-cn.com/problems/n-ary-tree-postorder-traversal/)  

[二叉树的路径](https://leetcode-cn.com/problems/binary-tree-paths/)  

## 10月19日  双周赛 周赛
字符串 轮转 和 加数字   两个循环

## 10月20日

[143. 重排链表 ](https://leetcode-cn.com/problems/reorder-list/)  

[14. 最长公共前缀](https://leetcode-cn.com/problems/longest-common-prefix/)  
有方法是利用python的zip 和set特性 在面试中  不能用zip函数 因为和python高度相关了  

[997. 找到小镇的法官](https://leetcode-cn.com/problems/find-the-town-judge/)  
第一次做出来了  思路和别人题解一样  

[1042. 不邻接植花](https://leetcode-cn.com/problems/flower-planting-with-no-adjacent/)  
自己的做法 时间和内存都会超出限制  

[399. 除法求值 ](https://leetcode-cn.com/problems/evaluate-division/)  
带权重的  图的并查集  

[547. 朋友圈](https://leetcode-cn.com/problems/friend-circles/)  
并查集的经典题  

[130. 被围绕的区域](https://leetcode-cn.com/problems/surrounded-regions/)  
用并查集  不是特别有效  只是方便理解并查集  

[952. 按公因数计算最大组件大小](https://leetcode-cn.com/problems/largest-component-size-by-common-factor/)    
学习这道题找公因数的过程  之前写的太慢了  

## 10月21日
[925. 长按键入](https://leetcode-cn.com/problems/long-pressed-name/)   
双指针还不是很熟   没写对  

[990. 等式方程的可满足性](https://leetcode-cn.com/problems/satisfiability-of-equality-equations/?_blank )  
<a href="https://leetcode-cn.com/problems/satisfiability-of-equality-equations/" target="_blank">  990. 等式方程的可满足性  </a>  

[684. 冗余连接](https://leetcode-cn.com/problems/redundant-connection/)  
就是在加边连通的时候，我们需要判断一下  如果已经连通了 说明找到了冗余的边

[685. 冗余连接 II](https://leetcode-cn.com/problems/redundant-connection-ii/)  

[1576. 替换所有的问号](https://leetcode-cn.com/problems/replace-all-s-to-avoid-consecutive-repeating-characters/)  
第一次做出来了  

[459. 重复的子字符串](https://leetcode-cn.com/problems/repeated-substring-pattern/)  
有点像循环旋转一个字符串的感觉，然后找不同。有个字符串找子字符串匹配的算法：KMP  

[416. 分割等和子集](https://leetcode-cn.com/problems/partition-equal-subset-sum/)  
01背包问题   两个状态的dp

## 10月22日
[763. 划分字母区间](https://leetcode-cn.com/problems/partition-labels/)  
贪心算法  学习题解的写法  

[474. 一和零](https://leetcode-cn.com/problems/ones-and-zeroes/)  
动态规划  相当于是3个状态的dp了  

[70. 爬楼梯](https://leetcode-cn.com/problems/climbing-stairs/)  
一维的动态规划  

[283. 移动零](https://leetcode-cn.com/problems/move-zeroes/)  
借助了快速排序的思想,还不是特别熟练  

[448. 找到所有数组中消失的数字](https://leetcode-cn.com/problems/find-all-numbers-disappeared-in-an-array/)  
相当于利用确实的数字 来做小动作。第一次做小动作，第二次来找出这些小动作。

## 10月23日

[234. 回文链表](https://leetcode-cn.com/problems/palindrome-linked-list/)  
快慢节点找中间节点的程序还不是很熟  

[887. 鸡蛋掉落](https://leetcode-cn.com/problems/super-egg-drop/)  
经典的动态规划问题  

[461. 汉明距离](https://leetcode-cn.com/problems/hamming-distance/)  
可以使用异或操作   这样简单  然后再统计1的个数  
注意官方题解的方法三有一个记位的方法  
n & (n - 1) 即 n &= (n - 1) 实质是抹掉二进制最右边的 1 。  

## 10月24日  
[1024. 视频拼接](https://leetcode-cn.com/problems/video-stitching/)  
贪心算法，类似于排课表那个.还有动态规划的做法  

[55. 跳跃游戏](https://leetcode-cn.com/problems/jump-game/)  
贪心算法  

[392. 判断子序列](https://leetcode-cn.com/problems/is-subsequence/)  
简单的双指针  

[45. 跳跃游戏 II](https://leetcode-cn.com/problems/jump-game-ii/)  
贪心算法  

## 10月25日  

[845. 数组中的最长山脉](https://leetcode-cn.com/problems/longest-mountain-in-array/)  
自己想的太复杂了，有点像统计最大深度的感觉  

[5546. 按键持续时间最长的键](https://leetcode-cn.com/problems/slowest-key/)  
第一次做出来了，一次遍历  

[5547. 等差子数组](https://leetcode-cn.com/problems/arithmetic-subarrays/)  

[5548. 最小体力消耗路径](https://leetcode-cn.com/problems/path-with-minimum-effort/)  
实际可以转化成图，寻找最短路径。着重看下。 

[743. 网络延迟时间](https://leetcode-cn.com/problems/network-delay-time/)  
dijkstra的普通版本和利用堆的版本  

## 10月26日  

[1365. 有多少小于当前数字的数字](https://leetcode-cn.com/problems/how-many-numbers-are-smaller-than-the-current-number/)  
学习计数排序的原理  

[455. 分发饼干](https://leetcode-cn.com/problems/assign-cookies/)  
简单的贪心算法

[860. 柠檬水找零](https://leetcode-cn.com/problems/lemonade-change/)

[134. 加油站](https://leetcode-cn.com/problems/gas-station/)  
python的braak是跳出最小的循环，不是直接跳出所有的循环,[这个题解的想法很好](https://leetcode-cn.com/problems/gas-station/solution/shi-yong-tu-de-si-xiang-fen-xi-gai-wen-ti-by-cyayc/)  官方题解的时间复杂度可以降到O(N)

[316. 去除重复字母](https://leetcode-cn.com/problems/remove-duplicate-letters/)  
用了栈。学习官方题解思想  

## 10月27日
[144. 二叉树的前序遍历](https://leetcode-cn.com/problems/binary-tree-preorder-traversal/)  
递归写出来了，迭代没写出来  

[452. 用最少数量的箭引爆气球](https://leetcode-cn.com/problems/minimum-number-of-arrows-to-burst-balloons/)  
跟排课表很类似，本题有两个排序的解法，学习二维数组怎么按照不同列排序的写法  
[这题解不错](https://leetcode-cn.com/problems/minimum-number-of-arrows-to-burst-balloons/solution/chuan-shang-yi-fu-wo-jiu-bu-ren-shi-ni-liao-lai-3/)
 464  646  605  665

[435. 无重叠区间](https://leetcode-cn.com/problems/non-overlapping-intervals/)  
像这种贪心的题，一般都是以end排序，理解起来不容易出错些

[665. 非递减数列](https://leetcode-cn.com/problems/non-decreasing-array/)  
没做出来

## 10月28日  
[1207. 独一无二的出现次数](https://leetcode-cn.com/problems/unique-number-of-occurrences/)  
简单的利用哈希法统计频率就可以了，[这题解详细讲了哈希法](https://leetcode-cn.com/problems/unique-number-of-occurrences/solution/1207-du-yi-wu-er-de-chu-xian-ci-shu-shu-zu-zai-ha-/)














