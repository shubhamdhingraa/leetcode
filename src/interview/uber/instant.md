Uber 面试 一工程师LinkedIn 联系我， 电话扯逼一番说给推荐。 电面， ABC女，
一道可以用anagram group思路的题, email domain address typo, need to figure out and return correct domain name. e.g. yhaoo--> yahoo, giaml --> gmail, hmailot--> hotmail. Solution: HashMap, key as sorted string, value as correct email domain. 10min finsih coding and proactively add unit test and make it run. 

面完10分钟给onsite. 
Uber Oniste:(China Growth)， 天了噜了居然没看到网上所说的美女工程师 
1. Elevator Design 美国人本科刚毕业，只给了他45分钟其他都是1小时的面试。 
2. Design Uber, web service, API, database. 中国大哥面的，我说API web service database 时他不时冷笑，我都菊花一紧。(需要知道如何解决how to replicate between data center in case of one of them down and make sure realtime data is available) 
3.天了噜了，面试官比我高比我帅比我还聪明! 聊了聊 怎么学技术，怎么吹牛逼，喝啤酒不， 滑船滑雪不。
最后来了不等式判断矛盾, given a > b, b > c, if pass in c > a return false, if a > c return true. 
Solution: 当时脑子里立马想起 Detect cycle in graph(至少证明刷题有用，思路想法可以套用上去), 本来解释用Union-Find的思路，结果他说如果有个d > c 这时候会改变父节点的，而且space会增加，并且看出来 他好像不了解Union-Find的方法，于是我瞎逼催说那就topological sorting吧，for loop + dfs。这时候已经没时间了， 写了个很潦草的伪代码，最后他看明白了。 这白人小哥聊的很开心，丫的要是给我强顶下多好啊，可以陪酒陪滑雪啊我日。 
4. Live Coding, TinyUrl Encode/Decode, run without bug. 
(Base62) 写完后decode部分有bug，数值一大， NullPointerException biu~ biu~ biu~.不是很完美。(Live Coding 还可以选fetch image from Google using Google's API, 我觉略偏前台，而且不熟悉Google Image API, 当场查和写，30多分钟 略有挑战性。除非对语言对API 巨熟悉), 写完他们肯定要让你写测试，时间多得出来的话。（两中国小哥，一个smart face， 一个general face） 
5. HM面，说是FB新来的manager, 先shadow. 我日了就。然后ABC问Spiral Array Print. 写起来很容易。 但是，最后被要求一行一行人脑走程序解释每一步变量值是啥，他给了个错误的干扰信息， 结果被绕进去了。我觉得短时间内写出代码然后举例走4x5的矩阵 spiral array 略有挑战性，时间也就是25分钟， 之前和他蛋逼来着。结果他说you're very close了。回来查了下代码，清清楚楚明明白白，一模一样完全没错。就是没走好代码。 

总结： 题目都不难，难于你我之前的交流和chemsitry,以及运气。 第一天面Apple第二天Uber 以及损伤不少了。 路漫漫其修远兮，希望路过的以后有offer求推啊！万分感谢！ 

链接: https://instant.1point3acres.com/thread/133267
来源: 一亩三分地