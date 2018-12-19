# WebSocket协议
  
WebSocket是一种在单个TCP连接上进行全双工通讯的协议。WebSocket通信协议于2011年被IETF定为标准RFC 6455，并由RFC7936补充规范。WebSocket API也被W3C定为标准。

WebSocket使得客户端和服务器之间的数据交换变得更加简单，允许服务端主动向客户端推送数据。在WebSocket API中，浏览器和服务器只需要完成一次握手，两者之间就直接可以创建持久性的连接，并进行双向数据传输
  
# STOMP协议

STOMP是面向文本的消息传送协议。STOMP客户端与支持STOMP协议的消息代理进行通信。STOMP使用不同的命令，如连接，发送，订阅，断开等进行通信。
  
# SockJS

SockJS是一个JavaScript库，提供跨浏览器JavaScript的API，创建了一个低延迟、全双工的浏览器和web服务器之间通信通道