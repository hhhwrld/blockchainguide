

## 概念

首先节点自身不知道自己是否是公开的还是躲在NAT /防火墙后面。NAT背后的节点不需要告诉他的不公开的地址，这样可以防止别人拨号以及恶意攻击。同时它可以通过查找relay server 来和其他节点建立间接连接。

通过 autoNAT 协议， 可以尝试拨号其他节点的公共地址，如果失败，说明NAT阻止传入连接。

## AutoNAT 协议

