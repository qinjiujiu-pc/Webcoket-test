# Webcoket-test
用来部署webscoket服务器的，测试连接项目中的实时数据连通
咋数据测试的时候 我查看了三个开源的服务  打算分别测试一下

1.     PyWebSocket
PyWebSocket采用Python语言编写，可以很好的跨平台，扩展起来也比较简单，目前WebKit采用它搭建WebSocket服务器来做LayoutTest。
我们可以获取源码通过下面的命令
svn checkouthttp://pywebsocket.googlecode.com/svn/trunk/ pywebsocket-read-only
更多的详细信息可以从http://code.google.com/p/pywebsocket/获取。
2.     WebSocket-Node
WebSocket-Node采用JavaScript语言编写，这个库是建立在nodejs之上的，对于熟悉JavaScript的朋友可参考一下，另外Html5和Web应用程序受欢迎的程度越来越高，nodejs也正受到广泛的关注。
我们可以从下面的连接中获取源码
https://github.com/Worlize/Websocket-Node
3.     LibWebSockets
LibWebSockets采用C/C++语言编写，可定制化的力度更大，从TCP监听开始到封包的完成我们都可以参与编程。
我们可以从下面的命令获取源代码
git clone git://git.warmcat.com/libwebsockets
