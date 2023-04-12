import Bleed from 'nextra-theme-docs/bleed'
import Callout from 'nextra-theme-docs/callout'

<Bleed>
  ![Velodrome Finance Launch](/biker_hero.png)
</Bleed>

&nbsp;

# Security

As a commitment towards the safety of our users and partners, we want to
be transparent about the changes and the status of the security audits of our
smart contracts.

Velodrome Finance was adapted from Solidly, which [codebase was open
sourced in full](https://github.com/solidlyexchange/) by Andre Cronje and his team in
March 2022. Since its release in February on Fantom network, no security
incidents related to Solidly smart contracts were reported.

Velodrome Finance smart contracts can be found on Optimistic Etherscan at the links below.

<Callout emoji="⚠️">
  Before moving forward, we'd like to remind to our users that
  security audits do not eliminate risks completely and that
  every user should read and agree to our
  [legal disclaimer](/legal) before using Velodrome Finance!

  For security reports, please reach out to us on
  [Discord](https://discord.gg/eGgYPGczaf), or to the contacts provided on our Github page.
</Callout>

## Audits

Solidly went through a partial (only the AMM part was sent for audit) security
audit in January 30, 2022. The audit was done by PeckShield and did reveal 5
low-severity and 1 informal findings.

The full audit is available for [download from Solidly git
repository](https://github.com/solidlyexchange/solidly/blob/master/audits/e456a816-3802-4384-894c-825a4177245a.pdf).

Velodrome Finance went through a security audit and a peer review as part of the Code4rena bug bouncy contest.
Finally, a full MythX deep scan on Velodrome contracts found just a
handful of false-positive, low-severity issues reported.

The Code4rena contest results were released on August 8, 2022 and are available [here](https://code4rena.com/reports/2022-05-velodrome/). All high- or medium-risk issues were either resolved pre-deploy, except for one known issue (users can claim eligible rewards from ExternalBribe contracts more than once) that's currently being addressed (via a wrapped contract solution). No user funds are at risk from this vulnerability, and protocols who wish to deposit external bribes should get in contact with the core team to discuss alternative solutions. More information about our C4 contest can be found [here](/c4report).

Lastly, we also engaged with Coelacanth ([@ImpossibleNFT](https://twitter.com/impossiblenft)) for an informal full audit. Reports from that audit are available [here](https://github.com/velodrome-finance/contracts/tree/master/audits/velo).

## Bug Bounty Programs

Velodrome Finance ran a [bug bounty contest on 23rd to 30th of May 2022 with
awards up to $75,000 on Code4rena](https://code4rena.com/contests/2022-05-velodrome-finance-contest).
The main scope of the contest was to cover all the new changes to the new and
the original contracts.

Solidly's bug bounty program was launched in February 2022 on Immunefi.com.
There were no claims for any of the $200,000 rewards ([on their Github](https://github.com/solidlyexchange/solidly/blob/master/SECURITY.md)).

## Contract Addresses

| Contract Name | Contract Address | Network |
| --- | --- | --- |
| Velo               | [0x3c8B650257cFb5f272f799F5e2b4e65093a11a05](https://optimistic.etherscan.io/address/0x3c8B650257cFb5f272f799F5e2b4e65093a11a05#code) | Optimism |
| GaugeFactory       | [0xC5be2c918EB04B091962fDF095A217A55CFA42C5](https://optimistic.etherscan.io/address/0xC5be2c918EB04B091962fDF095A217A55CFA42C5#code) | Optimism |
| BribeFactory       | [0xA84EA94Aa705F7d009CDDF2a60f65c0d446b748E](https://optimistic.etherscan.io/address/0xA84EA94Aa705F7d009CDDF2a60f65c0d446b748E#code) | Optimism |
| WrappedBribeFactory| [0xFC1AA395EBd27664B11fC093C07E10FF00f0122C](https://optimistic.etherscan.io/address/0xFC1AA395EBd27664B11fC093C07E10FF00f0122C#code) | Optimism |
| PairFactory        | [0x25CbdDb98b35ab1FF77413456B31EC81A6B6B746](https://optimistic.etherscan.io/address/0x25CbdDb98b35ab1FF77413456B31EC81A6B6B746#code) | Optimism |
| Router             | [0x9c12939390052919aF3155f41Bf4160Fd3666A6f](https://optimistic.etherscan.io/address/0x9c12939390052919aF3155f41Bf4160Fd3666A6f#code) | Optimism |
| VelodromeLibrary   | [0xfb1Fc21D2937bF5a49D480189e7FEd42bF8282aD](https://optimistic.etherscan.io/address/0xfb1Fc21D2937bF5a49D480189e7FEd42bF8282aD#code) | Optimism |
| VeArtProxy         | [0x5F2f6721Ca0C5AC522BC875fA3F09bF693dcFa1D](https://optimistic.etherscan.io/address/0x5F2f6721Ca0C5AC522BC875fA3F09bF693dcFa1D#code) | Optimism |
| VotingEscrow       | [0x9c7305eb78a432ced5C4D14Cac27E8Ed569A2e26](https://optimistic.etherscan.io/address/0x9c7305eb78a432ced5C4D14Cac27E8Ed569A2e26#code) | Optimism |
| RewardsDistributor | [0x5d5Bea9f0Fc13d967511668a60a3369fD53F784F](https://optimistic.etherscan.io/address/0x5d5Bea9f0Fc13d967511668a60a3369fD53F784F#code) | Optimism |
| Voter              | [0x09236cfF45047DBee6B921e00704bed6D6B8Cf7e](https://optimistic.etherscan.io/address/0x09236cfF45047DBee6B921e00704bed6D6B8Cf7e#code) | Optimism |
| Minter             | [0x3460Dc71A8863710D1C907B8d9D5DBC053a4102d](https://optimistic.etherscan.io/address/0x3460Dc71A8863710D1C907B8d9D5DBC053a4102d#code) | Optimism |
| RedemptionReceiver | [0x846e822e9a00669dcC647079d7d625d2cd25A951](https://optimistic.etherscan.io/address/0x846e822e9a00669dcC647079d7d625d2cd25A951#code) | Optimism |
| VeloGovernor       | [0x64DD805aa894dc001f8505e000c7535179D96C9E](https://optimistic.etherscan.io/address/0x64DD805aa894dc001f8505e000c7535179D96C9E#code) | Optimism |
| MerkleClaim        | [0x00D59BC35174C3b250Dd92a363495d38C8777a49](https://optimistic.etherscan.io/address/0x00d59bc35174c3b250dd92a363495d38c8777a49#code) | Optimism |
| RedemptionSender   | [0x9809fB94eED086F9529df00d6f125Bf25Ee84A93](https://ftmscan.com/address/0x9809fB94eED086F9529df00d6f125Bf25Ee84A93#code) | Fantom |

All contracts are immutable. The latest public testnet deployment can be found [here](https://docs.velodrome.finance/testnet.json).

## Tokenlist

In addition to the [official Optimism tokens
list](https://tokenlists.org/token-list?url=https://static.optimism.io/optimism.tokenlist.json),
we maintain one as well
with our partner tokens:
https://docs.velodrome.finance/tokenlist.json

## Differences from Solidly

As of August 2022, we've compiled a list of key differences between Velodrome's contracts and Solidly's.

### Major changes

  - **Treat external bribes differently than internal bribes (i.e. fees).**
    We split Bribe into two separate contracts, `InternalBribe` and
    `ExternalBribe`. `InternalBribe` functions essentially the same way as `Bribe`
    did, but `ExternalBribe` ensures that rewards are eliglble to be claimed by
    any voter who votes for the underlying gauge during the epoch, instead of
    only voters who vote after the rewards are sent. `ExternalBribe` also ensures
    that rewards can only be claimed after the epoch ends.`ExternalBribe`
    rewards must also be _whitelisted_ via on-chain governance.
  - **One vote per epoch. In Velodrome, voters are only allowed to make "active"
    voting decisions (i.e. vote and reset) once per epoch.** Voters must wait
    until the next epoch to change their votes. Voters can, however, _cast_
    their votes throughout the epoch.
  - **On-chain governance.** To handle protocol-wide decisions (such as eligible
    tokens for external bribes), we introduce an on-chain Governor. This will
    likely be Tally's first on-chain governor on Optimism following their
    support for the network.
  - **Killable gauges.** To dissuade emissions exploitation via dummy gauges, we're
    allowing the _Velodrome Commissaire_ (akin to Curve's Emergency DAO) to kill
    any "bad" gauges. The Commissaire is composed of individuals from varying
    parties meant to serve as a credibly neutral decision-maker for the broader
    ecosystem.

### Minor changes

  - **Removed the LP boost for voters.** We removed the boost that voters receive
    when staking their LPs with gauges they voted for. This removes the need
    for a veNFT aggregator (more on this later...).
  - **Removed negative voting.** We found negative voting to be zero-sum for
    Solidly, so we decided to remove it.
  - **Team emissions.** 3% of new emissions will be sent to a team address, meant
    to cover on-going expenses and future development.

### Small changes

  - **Modifiable fees.** Fees are now doubled to 0.02%, modifiable up to 0.05%, and
    tracked differently for volatile vs stable pairs.
  - **Upgradeable veNFT art.** Self-explanatory
  - **Velodrome specific.**
  - **Initial distribution.** Initial distribution will be handled in two ways: a
    redemption process that uses LayerZero to burn `$WEVE` for `$USDC` and
    `$VELO` on Optimism, and a Merkle airdrop contract. Unclaimed `$VELO` is
    never minted to ensure emissions aren't affected.
