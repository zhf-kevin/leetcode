- 1
	- 这道题靠遍历肯定是不行的，用map或者hash_map，查找效率更快。另外，还有个小细节，要避免用同一个元素。例如nums[0]=3，target=6这样的情况。
	
- 4
	- 这道题是归并算法的思想。
	
- 5 
	- 主要是题目的分解，得到转移方程，对于这道题来说，从i到j的子串是不是回文字符串，有三种情况：一是，就一个字符，即i等于j的时候，是回文字符串；二是，有两个字符，当这两个字符相同时，就是回文字符串；三是，有多于两个的字符，则i处的字符等于j处的字符，且从i+1到j-1的子串是回文字符串的时候，就是回文字符串。而且，在这个过程中，需要记下回文子串的最大长度和开始的地方，最后运用substr取得子串。
	
- 26
	- 水题，不解释。
	
- 27
	- 水题，不解释。

- 53 
	- 记录的值是以某个位置为结尾的子数组的大小，如果前面的子数组加上这个数，值增加，这个位置的大小就是前面的数组和加当前这个数，否则新的子数组就从这个位置开始，在这个过程中，记录下最大的数组和就行。
	
- 62
	- 跟64题类似，比64题简单，只需要计算不同路径总数就行。
	
- 64 
	- 其实就是记录每个点到右下角的点的最小代价就行，遍历一遍所有的点，最后返回左上角的点到右下角的点的最小代价就行。需要注意的地方就是，这个二维数组，行数和列数不一定相同。
	
- 66
	- 数组倒过来，进位就好做了。

- 70 
	- 这道题直接写递归的是要超时的，解决办法是将递归转化为循环。
	
- 118
	- 水题，不解释。
	
- 119
	- 水题，不解释。
	
- 120
	- 这道题跟64题类似，不同的是，不需要判断那么多边界条件，更为简单。

- 121 
	- 这个直接写递归也不对，还是要用循环，设定买入的价格，后续判断当前的价格是否大于这个价格，如果比这个价格低，就需要把买入价格设置为当前价格，如果比买入价格高就计算利润，然后跟之前的最高利润做对比，比之前的大，就将最高利润设置为当前利润。
	
- 344
	- 这道题太简单，不解释。
	
- 392
	- 这个题很简单，就是依次在t里面找s[pos]，pos是一个游标，只要在t里面找到s[pos]，pos就加1。需要注意的是，空字符串""是任何字符串的子串。
	
- 413
	- 这个题跟回文子串的题比较类似，而且更简单，再遍历的过程中，一旦发现不是等差数列，则新搞一个数列走起，而且观察规律可知，在原等差数列的基础上，如果加一个数还是等差数列，那么等差数列的个数就增加(原等差数列加这个数的数列长度减3再加1)

- 647 
	- 和题目5比较类似，统计回文串的个数就行。
	
- 709
	- 水题，不解释。
	
- 867
	- 水题，不解释。



