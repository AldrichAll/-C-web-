# Tiny-Cpp-Web-Server
主要是使用C++开发基于服务端/客户端模型的web服务器，运行在Linux环境中，使用epoll来实现IO多路复用，事件处理模式使用Reactor模式，主线程只负责监听文件描述符是否有事件发生，读写数据以及处理客户请求均在工作线程中实现。
