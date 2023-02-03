# Dude（大佬）

Dude这个名字来源自电影《失控玩家》，本来这个程序原来的名字叫（侦察兵）但是感觉（大佬）更符合各位渗透大佬的气质。

这是一款手工WEB渗透辅助工具，开发这款工具的动机主要是个人在日常进行渗透测试时，发现在进行WEB渗透这块主要工具还是WEB漏扫、浏览器、Burpsuite完成，在空闲的时候把经常使用到的功能集合成一个程序，期望能替代浏览器及Burpsuite的一些常用功能进行快速操作，其实还写了很多辅助的小工具但是鉴于如果把这些东西全塞进Dude整个程序会变得很臃肿而且未必是常用的，后续会把这些小工具做成插件供大家在程序里有选择的调用。

功能介绍：
    用户手册实在是懒得写，有这时间不如多写点代码，粗略介绍一下主要功能和应用范围。

1. 网站浏览、数据监视
    提供常规的网站浏览，主要实现浏览器UserAgent和Cookie的快速修改，配合数据监视可精准定位重要请求以便进行后续的数据包修改，实在不满足还有F12控制台功能，实现更复杂的操作。
2. 数据重放
    提供数据改发包功能，在实际应用中什么POC验证、注入、上传、伪造IP、COOKIE都可以在这里实现，并具有插入荷载功能方便操作不可见字符和字符串进行编码加密等，后续更多的功能会增加。
3. 数据爆破
    提供灵活自定义的爆破功能，在数据重放的基础上实现自动化，主要是通过插入字典标记来实现各类型的爆破，例如账号密码爆破、文件爆破、路径爆破等等，字典标记可结合荷载标记直接让字典实现编码和加密。
    
![Duda](https://user-images.githubusercontent.com/73023058/216543166-0420c208-ad3b-4078-bf3c-b79f68bdadc3.jpg)

历史版本：
--- v1.0.0.1 ------------------
1. 完成程序主体；
2. 完成基于Edge的WebView2内核的嵌入浏览器及相关操作功能；
3. 完成浏览器数据监视拦截及相关数据过滤操作功能；
4. 完成基于socket的http及https的原始数据包操作数据重放功能及其附属功能；
5. 完成数据爆破功能，可对账号、密码、目录、文件等原始数据可操作层面进行自定义爆破的功能；
6. 完成反射插件调用及外部程序调用等功能；
7. 其他。
