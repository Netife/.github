# Netife  
一款适用于Windows的高效，精练的应用层数据包分析工具。Netife可以高效的抓取、分析、修改另分发HTTP/HTTPS/WS/WSS协议请求和回复。Netife是一款专精于网络安全从业者高效调试，软件开发中定向MOCK的有力工具。 
# 交流与教程    
Netife官方QQ交流群：685708349    
Netife官方教程文档地址：[NetifeDocs](https://netife.github.io/NetifeDocs/)  
# Netife特点  
- Netife支持协议分析工具，提供`Stream Mode`和`Proxy Mode`。前者旨在监听和捕获网络包，后者旨在通过代理服务器，以`MITM`方式修改另分发网络包。  
- Netife具有网络包调试工具，支持若干高自由度的调试模式：`Interceptor`(对所有请求进行全响应拦截)、`SilentScript`(基于策略的静态定向响应拦截)、`AutoScript`(基于JS脚本的动态响应拦截)、`Replay`(重放请求)，调试工具支持HTTP和WS两套。  
- Netife具有数据分析工具，提供包含但不限于`Session Comparer`(会话比较)、`Payload Analysis`(载体自动分析器)等等。  
- Netife具有数据发送工具，提供HTTP和WS和`Composer`，可以自由调试，且支持更多的自由度。  
- Netife支持插件包和脚本包，在数据修改层提供`JS`脚本注入，可定制为特定脚本包，在整个软件层面提供`DLL`式插件加载，可极大程度扩展软件。Netife框架支持多语言调用，例如在C++插件中使用原生函数调用JS脚本暴露的命令，极大方便开发。  
# Netife前端工具  
- [Netife](https://github.com/Netife/Netife):Netife主仓库  
- [Netife-Cli](https://github.com/Netife/Netife-cli):Netife本地调试工具  
- [Netife-SilentScript](https://github.com/Netife/NetifeSlientScript):Netife静默前端  
# Netife接入相关  
- [Netife文档](https://github.com/Netife/NetifeDocs):提供Netife开发文档的相关信息  
- [NetifeC++模板插件](https://github.com/Netife/NetifeCppPluginTemplateV1):提供C++插件开发模板  
- [Netife扩展组件](https://github.com/Netife/NetifeExtraLibSupport):Netife扩展组件，以gRpc直接接入Netife核心调度器  
- [NetifeCommunity](https://github.com/Netife/AwesomeNetifeProject):Netife社区项目 
