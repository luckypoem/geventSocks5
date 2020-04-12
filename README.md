#gevent-Socks5

A gevent based socks5 tunnel server.

##Features
* gevent Server (StreamServer)
* greenlet based protocol process.
* DNS Cache.
* Fast response to stop signals.

##TODO
* Connection Pool.

##References
* http://xiaoxia.org/2011/03/29/written-by-python-socks5-server/
* https://github.com/wynemo/sockstunnel
<p>把localsocks5.py的第59行的('', 1080)改为('127.0.0.1', 2280)
<p>我只运行 python localsocks5.py
