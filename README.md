# solr-handler
> 在window服务器中安装solr 并没有提供安装服务的批处理文件，只有运行的。

> 需要自运行不方便！

> 这里记录下安装window服务的批处理文件

> 这里使用Apache服务化组件：[Daemon](http://commons.apache.org/proper/commons-daemon/procrun.html)

> solr 启动后 cmd会在批处理文件目录下新建个端口的solr.端口号.port的文件！

> 直接java.exe启动可能引起solr CLI 无法正常使用! 手动加一个同命名的文件就可以继续使用CLI
