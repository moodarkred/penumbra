# Running a fullnode

In order to interact with the Penumbra network, users must provide an RPC URL
so that client software can read chain state and submit transactions.
This is true of the [Prax wallet], and of [pcli]. While users can select a publicly available
RPC URL from a party they trust, this guide demonstrates how a user can self-host
an RPC URL for use by themselves and others.

## Renting a server

There are a variety of cloud providers that provide dedicated hardware for a per-month cost basis.
Generally, hardware-based solutions will have superior performance, particularly in storage latency,
and also more reliable performance over time. One suitable option is the
[Matrix AX52 by Hetzner](https://www.hetzner.com/dedicated-rootserver/ax52/).

To get started with Hetzner, [create an account](https://accounts.hetzner.com/signUp), provide billing information,
then request a dedicated hardware server. While preparing the server request,
you'll need to provide an SSH public key for the root user account. Shortly after requesting the server, you should
receive an email notifying you that it's ready to accept logins.

## Setting up DNS

In order to use HTTPS over the web interface, you'll need to create an A record for the domain you want to use,
pointing to the IPv4 address for the server. Visit the website for your DNS provider, and create the A record,
using the 

## Provisioning the server


[pcli]: ../pcli.md
[Prax wallet]: https://chromewebstore.google.com/detail/prax-wallet/lkpmkhpnhknhmibgnmmhdhgdilepfghe
