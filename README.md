# Following the $LIBRA money

**[Open the case](https://giuppone.github.io/libra-money-trail/)** · **[Trace the money](https://giuppone.github.io/libra-money-trail/dashboard.html)**

957,000 public transactions on 4 blockchains, reduced to 23 points where the trail ends. Only an authority can ask who is behind them.

## The problem

$LIBRA was a memecoin promoted on Feb 14, 2025. It crashed in a few hours. The public question was simple: where did the
money go? Answering it means reading hundreds of thousands of transactions on several blockchains, and most of them do
not matter.

## The data

Only public data, about 957,000 transactions:

- **Solana:** 942,198 transactions (the full history of 6 pools and 1,336 wallets)
- **TRON:** 13,417 transactions
- **Arbitrum and Ethereum:** 1,431 transactions
- **deBridge:** 94 orders between networks

## The method

1. Read each transaction from the balances stored on the blockchain, before and after.
2. Build a graph of the movements that matter: 1,675 addresses and 2,813 movements.
3. Group what we see into nine known patterns (typologies), each with linked transactions.
4. Follow the money until it reaches an exchange or a service, where it mixes with the money of other customers.
5. For each of the 23 exit points, show all the paths that reach it, plus one main route that anyone can check, step by
   step.

## The result

23 points where the on-chain trail ends. For 18 of them, we found no public request for the owner's identity. Each one has
a route with dates, amounts and links to public explorers. Some of them show money that was split into many wallets and
then joined again in one place.

## What this work does not show

- It does not claim that a crime was committed, and it does not identify people. Only the courts can ask a service who a
  customer is.
- An address on the list does not mean its owner did anything wrong. Many are exchange wallets with millions of customers.
- A route shows a connection, not a full amount. A pool mixes the money of everyone who trades in it, so passing through a
  pool does not link two people.
- Wallets are called "team" only when a public source says so. Exchange names come from public labels that the exchanges
  did not confirm.
- This is a research and teaching exercise. It does not replace a court expert's report.

## What this helps you decide

If you work in compliance, law or journalism, the table shows where a request for information could start: which service to
ask, about which address, and why.

## Contact

I turn large sets of transactions into evidence that a compliance team, a lawyer or a journalist can check and use. If you have a similar case, tell me what you need to find out.

[cristian.giuppone@unc.edu.ar](mailto:cristian.giuppone@unc.edu.ar) · [LinkedIn](https://www.linkedin.com/in/cristian-giuppone/)

## Credits

The dashboard uses a modified version of [NeoDash](https://github.com/neo4j-contrib/neodash), Copyright 2023 Niels de Jong,
under the Apache License 2.0. See [NOTICE.md](NOTICE.md), [LICENSE-NeoDash.txt](LICENSE-NeoDash.txt) and
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt). This work is not an official product of the NeoDash authors or of Neo4j,
and they do not endorse it.

The license above covers NeoDash only. It does not cover the case text, the data selection or the video.
