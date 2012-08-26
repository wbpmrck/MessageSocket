MessageSocket
=============

IPC module based on Net.Socket.一个基于纯Socket实现的双向IPC组件。高速、好用。

<hr/>
<h2>Features(特性)<h2>
<ul>
<li>基于纯socket编写，速度快</li>
<li>支持双向通信，server可以主动给client发送消息，反之亦然</li>
<li>server端支持对client进行分组</li>
<li>server端支持对client进行组内的消息广播</li>
<li>server端支持对所有client进行消息广播</li>
<li>灵活可配置的自动重连功能，保证服务持续不间断</li>
<li>支持各种事件(服务器开启、关闭、客户端连接、断开等)</li>
<li>简洁好用的API</li>
</ul>


<hr/>
<h2>TODO<h2>
<ul>
<li>支持服务器关闭和开启</li>
<li>支持客户端主动断开和连接</li>
<li>支持针对某个消息进行回发(reply)</li>
</ul>
