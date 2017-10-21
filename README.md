出现错误：
Server Tomcat v8.0 Server at localhost failed to start.

错我原因：
对于同一个servlet
web.xml中配置了这个servlet对应的url-pattern，在servlet中又一次配置url-pattern

解决方法：
将servlet中对应的url-pattern删除

学习收获：
对于servlet对应的url指定，可以在web.xml中定义，也可以在servlet中直接定义，两种方法效果相同，不可同时进行
工作能力就是解决问题的能力，而学习就是一个遇到问题，发现问题，然后解决问题的过程，在不断的解决问题的过程中，掌握知识，提高能力。
