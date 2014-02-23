libre
=====

Libre is a portable and generic library for real-time communications with async IO support 
and a complete SIP stack with support for SDP, RTP/RTCP, STUN/TURN/ICE, BFCP and DNS Client.

Features:

SIP Stack (RFC 3261)
SDP
RTP and RTCP
DNS-Client
STUN/TURN/ICE
BFCP
Jitter-buffer
Async I/O (poll, epoll, select)
UDP/TCP/TLS transport


Building and installation

To build libre we are using GNU Make. External dependencies are automatically detected by the makefile.
$ cd re
$ make
$ sudo make install


Project home: http://www.creytiv.com/re.html
