---
title: Erlang
weight: 6
toc: true
---

## erlzmq_dnif

<table>
<tr><td>Github</td><td><a href="http://github.com/lukaszsamson/erlzmq" target="_blank">http://github.com/lukaszsamson/erlzmq</a></td></tr>
<tr><td>Hex</td><td><a href="https://hex.pm/packages/erlzmq_dnif" target="_blank">https://hex.pm/packages/erlzmq_dnif</a></td></tr>
</table>

Fork of erlzmq2 using dirty NIFs for blocking IO calls and dedicated threads for safely handling sockets.
Compatible with zmq 4.x
Supports macos and *nix
Supports CurveZMQ

## Chumak

<table>
<tr><td>Github</td><td>

[https://github.com/zeromq/chumak](https://github.com/zeromq/chumak)

</td></tr>
<tr><td>Hex</td><td><a href="https://hex.pm/packages/chumak" target="_blank">https://hex.pm/packages/chumak</a></td></tr>
</table>

Pure Erlang implementation of ZeroMQ Message Transport Protocol.

## ezmq

<table>
<tr><td>Github</td><td>

[https://github.com/zeromq/ezmq](https://github.com/zeromq/ezmq)

</td></tr>
</table>

ezmq implements the ØMQ protocol in 100% pure Erlang.

## erlang-czmq

<table>
<tr><td>Github</td><td><a href="https://github.com/gar1t/erlang-czmq" target="_blank">https://github.com/gar1t/erlang-czmq</a></td></tr>
</table>


erlang-czmq is an Erlang port wrote on top of czmq. The API mirrors that of CZMQ with all functions being available through the czmqmodule.

## erlzmq2

<table>
<tr><td>Github</td><td>

[http://github.com/zeromq/erlzmq2](http://github.com/zeromq/erlzmq2)

</td></tr>
</table>

erlzmq2 is NIF based binding.
Not maintained
Warning: unstable (leaks file descriptors, memory, threads, has race conditions, can deadlock beam and crashes due to accessing zmq sockets from multiple beam threads)

## erlzmq2 - esl fork

<table>
<tr><td>Github</td><td><a href="http://github.com/esl/erlzmq" target="_blank">http://github.com/esl/erlzmq</a></td></tr>
<tr><td>Hex</td><td><a href="https://hex.pm/packages/erlzmq" target="_blank">https://hex.pm/packages/erlzmq</a></td></tr>
</table>

Fork of erlzmq2 published on hex.pm.
Compatible with zmq 4.x
Supports macos and *nix
Warning: unstable (leaks file descriptors, memory, threads, has race conditions, can deadlock beam and crashes due to accessing zmq sockets from multiple beam threads)

## erlzmq

<table>
<tr><td>Github</td><td>

[http://github.com/zeromq/erlzmq](http://github.com/zeromq/erlzmq)

</td></tr>
</table>

erlzmq is port based binding. Compatible with zmq 2.x
Not maintained
