# BitVm-FAQ
less-technical frequently asked questions on [BitVm](https://bitvm.org/bitvm.pdf)

## What is BitVM?

It is a virtual computer for use in bitcoin contracts. As a virtual computer, BitVM can run programs. It can run anything a developer can write for it. What makes it unique is, it is compatible with bitcoin, meaning BitVM programs can be used to "lock up" bitcoins. In other words, you can put some money in a bitcoin address, and know that they only way someone can take it is if they correctly run a program of your choice -- *any program.*

## Does BitVM make bitcoin like ethereum?

No. BitVM programs are executed off-chain, unlike ethereum programs, which are executed on-chain. In BitVM, you only use the blockchain during a dispute, to prove that someone ran a program *incorrectly* off-chain, whereupon you can take their money. If your counterparty runs the program correctly, nothing about the program goes on the blockchain.

## Where can I learn more?
here are some reads:
- [whitepaper](https://bitvm.org/bitvm.pdf)
- [WIP implementation](https://github.com/supertestnet/tapleaf-circuits/)
- [bitcoin magazine explainer](https://bitcoinmagazine.com/technical/the-big-deal-with-bitvm-arbitrary-computation-now-possible-on-bitcoin-without-a-fork)
- [simple explainer](https://github.com/fiksn/bitvm-explained)
- [LN+ explainer](https://lightningnetwork.plus/posts/450)
- [base58 explainer](https://twitter.com/base58btc/status/1711728898730242112)
  
  if you have another question or you want to follow the development and discussions on BitVm you can join [the BitVM Builders telegram group](https://t.me/bitVM_chat)
