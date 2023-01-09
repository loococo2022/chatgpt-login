# chatgpt-login
chatgpt成功解决Access denied 1020错误
​
        从前两天网上开始一直开着的chatgpt网页突然打不开了，提示1020错误，尝试换了不同代理软件或者代理地点仍然无法解决，也搜了很多资料，比如删除cookie、重启浏览器、更换浏览器等均不起作用。问题错误情况如下：Access denied Error code 1020。

Access denied Error code 1020
You do not have access to chat.openai.com.
The site owner may have set restrictions that prevent you from accessing the site.
I got an error when visiting chat.openai.com/.
 
Error code: 1020
Ray ID: 784d1879ce7e919c
Country: SG
Data center: sin08
IP: 2406:da18:18:7c00:a921:5c97:89f4:a78c
Timestamp: 2023-01-05 15:02:33 UTC


#  一、问题原因
        造成1020错误的主要原因是代理问题。chatgpt登录网址为“https://chat.openai.com/”。当打开代理时，登录该网站会直接显示上述错误“Access denied Error code 1020”。前几天登录是不会出现这个问题的。

        如果我们不采用代理，则可以打开如下登录界面，但是登录账号之后会出现“Oops! OpenAI's services are not available in your country. (error=unsupported_country)”，即国内IP已被限制。
# 二、解决方法
        第一步：在关闭代理的情况下进行登录，进入到输入密码界面。输入密码后，打开代理，然后点击“Continue”进行登录。登录之后，仍然会提示1020错误，即  Access denied Error code 1020。如果关闭代理仍然无法进入登录界面且出现Access denied Error code 1020，建议清理cookie后重启浏览器重试。另外，确认代理服务是完全关闭的。
        第二步：请关注“乐乐感知学堂”微信公众号，在公众号内回复“clog”即可获得完整内容，后续遇到其他问题均第一时间在公众号内进行更新。

# 三、长期关注
        chatgpt相关问题本博客将持续跟进。参考之前的博文无需编程即可将chatgpt接入自己的微信公众号_Coding的叶子的博客-CSDN博客也可在公众号被中直接体验chatgpt或者将其接入自己的公众号（无需代理、注册账号），可直接使用。chatgpt网页版替代方法_Coding的叶子的博客-CSDN博客
        微信公众号：乐乐感知学堂。
        CSDN：https://blog.csdn.net/suiyingy/article/details/128598359

        
