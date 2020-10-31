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

[435. 无重叠区间](https://leetcode-cn.com/problems/non-overlapping-intervals/)  
像这种贪心的题，一般都是以end排序，理解起来不容易出错些

[665. 非递减数列](https://leetcode-cn.com/problems/non-decreasing-array/)  
没做出来

## 10月28日  
[1207. 独一无二的出现次数](https://leetcode-cn.com/problems/unique-number-of-occurrences/)  
简单的利用哈希法统计频率就可以了，[这题解详细讲了哈希法](https://leetcode-cn.com/problems/unique-number-of-occurrences/solution/1207-du-yi-wu-er-de-chu-xian-ci-shu-shu-zu-zai-ha-/)

[646. 最长数对链](https://leetcode-cn.com/problems/maximum-length-of-pair-chain/)  
贪心题应该都是按照end排序吧，pairs.sort(key = lambda x:x[1])  

[605. 种花问题](https://leetcode-cn.com/problems/can-place-flowers/)  
判断连续的3个0，可以在首尾各添加0，这样形式上就变得统一了

[24. 两两交换链表中的节点](https://leetcode-cn.com/problems/swap-nodes-in-pairs/)  
第二次做没做出来，有迭代和递归的做法.类似25题。  

[26. 删除排序数组中的重复项](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array/)  
第二次做出来了，双指针  

[27. 移除元素](https://leetcode-cn.com/problems/remove-element/)  
官方题解中的方法二，针对重复数量小的时候，效率更快，有点像快排的思想  

[35. 搜索插入位置](https://leetcode-cn.com/problems/search-insert-position/)  
假设题意是叫你在排序数组中寻找是否存在一个目标值。 跟[605. 种花问题](https://leetcode-cn.com/problems/can-place-flowers/)很像。[二分查找的题解汇总](https://leetcode-cn.com/problems/search-insert-position/solution/te-bie-hao-yong-de-er-fen-cha-fa-fa-mo-ban-python-/)  
在一个排好序的数组中，查找一个数字，应该第一时间想到二分查找。二分查找模板没有记住  

[二分查找拉布拉多,包含了找左右边界的情况](https://github.com/labuladong/fucking-algorithm/blob/master/%E7%AE%97%E6%B3%95%E6%80%9D%E7%BB%B4%E7%B3%BB%E5%88%97/%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE%E8%AF%A6%E8%A7%A3.md)  

[704. 二分查找](https://leetcode-cn.com/problems/binary-search/)  
704和3都是二分查找的经典例子了吧

[34. 在排序数组中查找元素的第一个和最后一个位置](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array/)

## 10月29日  
[129. 求根到叶子节点数字之和](https://leetcode-cn.com/problems/sum-root-to-leaf-numbers/)  
没做出来，递归理解不到位,其实自己写完代码代下值就能明白很多,还有层序遍历的做法  

673  354    464   34  
[1095. 山脉数组中查找目标值](https://leetcode-cn.com/problems/find-in-mountain-array/)  

[黄冰衡面试滴滴实习的题](https://leetcode-cn.com/problems/find-minimum-in-rotated-sorted-array/)  

[75. 颜色分类](https://leetcode-cn.com/problems/sort-colors/)  
还是没做出出来  双指针  

[33. 搜索旋转排序数组](https://leetcode-cn.com/problems/search-in-rotated-sorted-array/)  

[66 加一](https://leetcode-cn.com/problems/plus-one/)  

## 10月30日  

[463. 岛屿的周长](https://leetcode-cn.com/problems/island-perimeter/)  
判断边界条件那里自己没弄好  

[滑动窗口问题](https://leetcode-cn.com/problems/find-all-anagrams-in-a-string/solution/hua-dong-chuang-kou-tong-yong-si-xiang-jie-jue-zi-/)  

[剑指 Offer 59 - I. 滑动窗口的最大值](https://leetcode-cn.com/problems/hua-dong-chuang-kou-de-zui-da-zhi-lcof/)  
[239. 滑动窗口最大值](https://leetcode-cn.com/problems/sliding-window-maximum/)
滑动窗口经典的题,  

[209. 长度最小的子数组](https://leetcode-cn.com/problems/minimum-size-subarray-sum/)  
是指连续的数组，不是指连续的数组值  

[76. 最小覆盖子串](https://leetcode-cn.com/problems/minimum-window-substring/)  

[总结滑动窗口题解](https://leetcode-cn.com/problems/minimum-window-substring/solution/hua-dong-chuang-kou-by-powcai-2/)  

## 10月31日  
[381. O(1) 时间插入、删除和获取随机元素 - 允许重复](https://leetcode-cn.com/problems/insert-delete-getrandom-o1-duplicates-allowed/)  
没有认真看，，，只是提交了个题解，字典的value也可以是一个字典，不一定就是一个数字。  
[讲python defaultdict](https://blog.csdn.net/HW_870754395/article/details/86064937?utm_medium=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param)  
defaultdic接受一个工厂函数作为参数，dict = defaultdict(factory_function)，<factory_function可以是list、set、str等>，当key不存在的时候，返回的是工厂函数的默认值（list的默认值[]  set默认值 set()  str默认值字符串  int默认值0）




  














