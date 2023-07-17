lian'jlianj
### TCP: transmission control protocol
### UDP: user datagram protocol
二者均为网络传输协议

1. 连接方式
  TCP为面向连接的协议，每次通信需要建立连接，通信后需要释放连接
  UDP为无连接协议，直接发送数据
3. 可靠性
  TCP可靠连接，数据丢失或损坏，会自动重传
  UDP不可靠连接，数据丢失、重复、损耗不会做反应
5. 传输速度
  UDP快于TCP，UDP没有重传机制、流量控制机制、拥塞控制机制，系统开销小
6. 数据包大小
  UDP不超过64k，TCP无限制
7. 适用场景
  TCP：邮件、文件传输
  UDP：音频、视频实时传输
