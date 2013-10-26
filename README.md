WebVPN_Starter
==============

鉴于 WebVPN 的设置最近有所改变，不再支持 Chrome + SwitchySharp 的设置方法。现在亟需为 Windows 做一个客户端软件。WebVPN_Starter 是一个短期过渡方案。希望 Windows 能尽快出现可以匹敌 fqrouter2 (Android) 和 goagentx (Mac) 的翻墙客户端软件。或者，有适用的 Chrome 插件出现。

现在的 WebVPN_Starter 只是一个 Windows 批处理文件，调用 stunnel 和 3proxy 程序，这些程序没有包括在这个 repo 里。


```
文件夹结构：
WebVPN_Starter/
  |- START.BAT
  |- stunnel.exe
  |- tstunnel.exe
  |- stunnel.conf
  |- … …
  |- 3proxy.exe
  |- 3proxy.cfg
  |- … … 
  
```
