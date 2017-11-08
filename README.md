# Building a Hub that connects you to Bitcoin

As the first and most valuable crypto currency in existence Bitcoin is
still a mysterious black box to most companies that would potentially want
to use it or build applications on top of.

Flowee is being built to help you connect to the Bitcoin network and handle all
the validation, parsing and low level database access for all your Bitcoin
needs. Including many needs you didn't even know you had!

The codebase is derived from the one that originally was created by Satoshi
Nakamoto, the inventor of Bitcoin. This way you know you won't get
compatibility issues. Flowee is adjusted for greatly increased speed and
reliability as well as for scaling up to much larger blocks than the
competition.

# The product

![Flowee Block Diagram](/img/blocks.png)

The first product that is under development now is the hub. It connects to
the Bitcoin network and stays in sync with the latest payments. The
majority of work is going into clarifying the design and making it
maintainable and low risk.

The hub is written in C++ and modern technologies are used to make the hub
fully able to use multiple cores and similar techniques to allow amazing
throughput on relatively modest hardware. A billion payments a day on a sub
$1000 machine will be possible.

On top of Flowee the Hub we allow anyone to build applications,
data-warehouses or just websites that show common Bitcoin data. The hub
provides binary APIs optimised for high speed data-communication over a
sub-net.

The separation of the hub from external tools allows you to plug and play
different components together. Do you want a log-manager to monitor all
your running nodes? You can. Add a data-warehouse that allows fast lookup
of any part of the historical chain, just roll it out anywhere on the
sub-net.

# The vision

The basis of building Flowee the Hub came out of the desire for freedom.
Freedom to innovate, freedom from financial oppression and freedom to use
or extend this software as you please.

Flowee is Free and Open Source Software (FOSS), you can use it for free (as
in beer), but the important freedom we are talking about is that anyone can
change it or simply run it. Flowee will remain perpetually give you that
freedom.

Flowee gives you a large amount of information and power to extend the
Bitcoin ideas of peer to peer payments with no intermediate party and
without central oversight. It allows you to establish your financial
freedom from banks and other rent-seekers.

Flowee is truly a hub in the system where we give you the ability to build
on top of the hub-software and effectively on top of Bitcoin itself.
Innovation will be made easier and we want to create an ecosystem of tools
for handling the blockchain data all with the goal that is to enable you to
focus all your effort on your own work.

# FAQ

## When will you release?

Soon.  
Flowee is not a new codebase, it has been used in production successfully
but we do feel a need to clean up various parts and finish some projects
before we can release.

Please don't let that stop you from compiling it yourself and joining the
project on [github](https://github.com/floweethehub/).

## Which Bitcoin chains will Flowee you support?

Flowee is aiming to only support the Bitcoin Cash chain because it doesn't
make sense to build on top of the legacy Bitcoin chain, there is no growth
opportunity there, there is no freedom there.

## Why do you work on this?

Please see my 2 part explanation on my reasons for believing in Bitcoin
Cash on yours.org; [Part
1](https://www.yours.org/content/on-the-path-to-freedom-of-innovation-3d3cd1e35527),
[Part
2](https://www.yours.org/content/on-the-path-to-freedom-of-innovation--2--a71d2fb53ce3).

