# Aptos and the Blockchain Programmability Spectrum

**Belief: The blockchain programmability spectrum is well defined between Bitcoin's minimal programmability and Ethereum's maximal programmability. Other L1s can compete with Ethereum, but likely will not find much success on the grounds that Ethereum's programmability and developer infrastructure is dominant. In addition, Ethereum's limitations around scaling aren't well addressed at the computability level anyways, and have more to do with user experience and rollup-based scaling rather than Solidity or Vyper's inability to perform certain computations.**

Posted on 11/25/22.

There's been a lot of discussion about Aptos, a new blockchain project that was spun out of the ruins of Diem. At a high level, it aims to provide serve the DeFi subset of blockchain applications using [Move](https://move-book.com/). The main benefits of Move is that it provides built-in DeFi primitives such as tokens. This leads to easier to audit code and parallelization of on-chain computation. In addition, Aptos aims to have a flexible governance system. By building more modular infrastructure, Aptos aims to be more nimble than its counterparts such as Bitcoin and Ethereum.

In this blog, I'm going to discuss the programmability spectrum, and how it shows that other L1 technologies are forced to compete with Bitcoin and Ethereum on very marginal features.

## Programmability

Right off the bat, I find myself skeptical of Aptos on the grounds that it sounds a lot like other Ethereum killers. The core question I'd like to ask is what can be built on Aptos that cannot be built on Ethereum.

The core idea that differentiated Ethereum from Bitcoin was that it blacklisted transaction templates: anyone could store and compute on any data barring certain operations with the constraint that gas was required to operate them. Conversely, Bitcoin whitelists transaction templates: only certains types of transactions are accepted by nodes on the Bitcoin network.

It isn't immediately apparent where the benefits of adopting Move come from other than some marginal benefits such as ergonomics (e.g. built-in token model). This could very well be an error on my part! After all, it is a black and white view of the blockchain programmability spectrum.

Ultimately, the job of the L1 can be boiled down to filtering execution of computation. From what I can tell, Ethereum and Bitcoin have explored the design space for this.

## Developer Infrastructure

Continuing on from the lack of benefits from just changing languages, Aptos and other competing L1s face an uphill battle of providing sufficient developer infrastructure to attract developers and novel activity on their chains. Today, Ethereum boasts Foundry, Hardhat and a multitude of clients. These frameworks make it very easy for developers to learn how to build, get jobs and raise capital for their projects.

Meanwhile, when we look at Aptos, which has a team from Meta, they have a lot of work to do to attract development. This often leads inorganic activity via incentives from VC funding (see SoLunAvax in 2021).

One model for understanding why some technology gains traction is that it simply makes people's live more convenient. In the case of Ethereum, it directly made developer's lives easier by having lots of competition among clients and multiple programming languages / compilers to enable fast development. This is a big deal as it allows for further specialization among developers with respect to Ethereum, and in turn, deepens Ethereum's dominance in the L1 space. Other protocols can try to replicate this convenience, but by then, Ethereum will have deepened other network effects as well.

## Scaling via Rollups

At a high level, the most effective way to scale blockchains is to use off-chain proofs and incentives, and not focus on L1 differentiators like transaction throughput and latency. If it's guaranteed that the right cryptographic primitives combined with a general computing paradigm works for scaling blockchain, then that's another reason in favor of Ethereum dominating the L1 space over the next few years.

In sum, the new frontier of competition appears to be in services around rollups and making them easier to use for both developers and users. Eventually, cross-chain rollups may become a thing, but in the meantime, it appears that rollup development is mostly focused on Ethereum.

## Conclusion

The programmability spectrum ranges from being explicitly restricted to certain activity (Bitcoin's whitelisting) to do whatever you want, but you'll ultimately be constrained by some resource (Ethereum's blacklisting + gas fee model). Right now, there is a lot of value in dominating the extremes of this spectrum and anything in between is marginal. Conversely, if one finds a way to expand the programmability spectrum beyond Ethereum's current EVM, there might be additional value to be created. In the meantime, Ethereum competitors will compete at the margins on developer infrastructure on things like the choice of programming language and ease of auditability of specific applications. 

### Counterpoint: specialization within a sector

When I originally got into crypto, I dove head-first into the Bitcoin maximalism rabbit hole. As a result, I was heavily biased against the usefulness of Ethereum from 2017 through 2020. However, with the invention of DeFi, and later NFTs, I became convinced that Ethereum had staying power. Ultimately, Ethereum's value came not from directly competing with Bitcoin, but rather from establishing new verticals to attract attention from the market. For example, Ethereum enabled credit creation completely outside of the traditional economy. I suspect if another L1 comes along to grow to Ethereum's size and scope, it will have to focus on disrupting one of Ethereum's core product verticals (e.g. DeFi). 

As a result, a bullish case for Aptos could look like the following:

Move turns out to be really great, not only for auditability and safety, but also for account abstraction and building user experiences that are more in line with traditional banking. This results in Aptos' DeFi applications being able to attract local banking infrastructure and onboard retail users faster than Ethereum can. Over time, this leads to novel products being created on Aptos that start to attract liquidity away from Ethereum's DeFi ecosystem. Finally, this ends with most of DeFi moving to Aptos while other applications such as [gaming NFTs remain on Ethereum](https://twitter.com/gabrielleydon/status/1591624902708432896).

### Counterpoint: meme coins competing with Bitcoin

Although a lot more attention and private funding is focused on Ethereum competitors, Bitcoin still has (weak) competition today! Tokens such $SHIB and $DOGE are direct competitiors with Bitcoin. At the margin, dollars are not deciding between Bitcoin and Ethereum, but rather between the speculative likelihood of a return between $BTC, $LTC and the various dog coins (aka the meme that will attract the most value). This doesn't really make sense based on what I just stated about network effects and liquidity. Savers and speculators alike would probably do better in an equilibrium where they focused entirely on Bitcoin. As a result, we can safely assume that there will always be profitable opportunities for Ethereum L1 competitors. In addition, given that Ethereum L1 competitors attract more private capital, we should expect to see more movements rise up and find niches to compete against Ethereum.