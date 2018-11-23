# reading-and-annotate-quic
 

			
借助libquic库实现的客户端和服务端例子编译方法       
===================================     
1. 先进入libquic-client-server-example/libquic目录，编译出libquic库  
mkdir build
cmake ..
make -j 4

2. 进入libquic-client-server-example/quic_client_server_example目录，编译出quic client和quic server可执行文件      

三. 说明    
===================================     
和最新的libquic并不匹配，所以不要更新libquic


编译出现问题参考这里   
===================================  	   
https://github.com/y123456yz/reading-and-annotate-quic/tree/master/libquic%20centos6.5%E7%BC%96%E8%AF%91%E7%8E%AF%E5%A2%83%E8%AE%BE%E7%BD%AE  



文档参考  
===================================  
https://github.com/y123456yz/reading-and-annotate-quic/tree/master/libquic%20centos6.5%E7%BC%96%E8%AF%91%E7%8E%AF%E5%A2%83%E8%AE%BE%E7%BD%AE/%E6%96%87%E6%A1%A3%E8%B5%84%E6%96%99 



nginx http2 quic学习参考:    
===================================    
nginx源码中文详细分析注释参考：https://github.com/y123456yz/reading-code-of-nginx-1.9.2   
libquic goquic编译安装，源码分析注释：https://github.com/y123456yz/reading-and-annotate-quic        
nghttp2相关参考：https://github.com/y123456yz/reading-and-annotate-nghttp2     
		
	
