* **web_thread.h**
	
	(1). 定义了webthread类;
	
	(2). 主线程和工作线程通过该类来进行通信，对工作线程建立对应的wedthread对象。

* **http_conn.h**

	(1).定义了http_conn类和util_timer类;
	
	(2).主要是用于处理http请求和应答;
	
	(3).util_timer是一个定时器类，来监控时间。
	

* **web_function.h**
	
	(1).主要是用于定义全局变量和常量，包括当前活跃的线程数目和缓冲区大小等等;
	
	
* **main.cpp**
	
	(1). 程序运行入口
	
	(2). 主线程只负责监听文件描述符是否有事件发生而不处理面向用户的业务逻辑(Reactor模式);
	
* **server.pro**

	(1). qt通过该文件来生成Makefile文件。

	
		
	
