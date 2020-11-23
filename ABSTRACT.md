# SonicChain: A Wait-free, Pseudo-static Approach Toward Concurrency in Blockchains.

In this work we look at blockchains as (yet another) transaction processing system (much like
databases, except being decentralized and trustless), and propose a new approach toward concurrency
therein. The newly devised approach allows higher throughput compared to a sequential one, both when
a block is being created, and when it is being imported. The crux of our approach is embedded in
leveraging static information from transactions, in order to accurately distribute them between
threads, effectively reducing the chance of conflicts. Consequently, given rare conflicts, we can
reduce the complications of runtime machinery and further reduce superfluous overhead. All of this
is achieved, while maintaining the single most important property of blockchains, determinism.
