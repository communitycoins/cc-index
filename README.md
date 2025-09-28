# cc-index

## Getting started
This project intends to be the central repository of all community coins by collecting information about
- their story and history
- our subjective qualification
- their objective parameters
- The intended community 

Most of these coins/teams/projects have been promoted/motivated by participants of the communitycoins dialog, wether on discord, twitter or telegram.
While the communitycoins definition is unambiguously defined on communitycoins.org, several other coins bare a similar history or are simply regarded as sympathetic to the concept of community driven assets that bare the satoshi mindset of freedom, decentralisation and limited supply.
These could at least be considered as guests and promotors of communitycoins.

## Communitycoins.org
The Communitycoin Alliance kicked-off in may 2018 by a meeting in Lissabon between de developers of Cryptoescudo (CESC) and eGulden (EFL) and by a joint elaboration of the website communitycoins.org with a shared manifest. During the next four years the inititiative was mainly carried by the teams of eGulden, Auroracoin and Canadaecoin through weekly meetings while raiding each others communities and other teams. Along the way Deutsche Emark, Pakcoin, Sterlingcoin, Bolivarcoin and Kobocoin more or less actively joined that group.

### Alliance (cc)
These teames actively contributed to the alliance and are considered community coins
- [eGulden-EFL](https://egulden.org) The Netherlands
- [Canadaecoin-CDN](https://canadaecoin.site/) Canada
- [Auroracoin-AUR](https://auroracoin.is/) Iceland
- [Deutsche eMark-DEM](https://deutsche-emark.org/) Germany
- [Bolivarcoin-BOLI](https://bolis.info/) Venezuela
- [Sterlingcoin-SLG](https://sterlingcoin.org/) Great Brittain
- [Pakcoin-PAK](https://www.pakcoin.io/) Pakistan
- [Cryptoescudo-CESC](https://cryptoescudo.pt) Portugal
- [Kobocoin-KOBO](http://kobocoin.com/) Africa
### Endorsed by the alliance
These teams are considered communitycoins but due to language or geographical/time distance had a hard time cooperating
- [Fujicoin-FJC](https://fujicoin.org/)
- [Russian Bitcoin-RUBTC](https://russian.nationalbitcoin.org/)
### Contributed 
These teams actively contributed and/or endorse community coins but the nature of their projects make them less suitable to be classified community coins. EUR because it is more about federation and NESS because it focusses on technology favoring decentralisation
- Europecoin,
- [Privateness Network-NESS](https://privateness.network/)
### In consideration or invited 
- [Mazacoin-MAZA](https://mazacoin.org)
- [Monacoin-MONA](https://monacoin.org/)
### Off the radar
- [scottcoin](https://scotcoinproject.com/) 
- [russiacoin](https://www.russiacoin.info/)
- [irishcoin](http://www.irishcoin.com/)
### Guests
These teams are selected by the participating communitycoin teams on demand.
### index.dat 
[This file](index.dat) will be accessed by the communitycoin-wallet to present coin options and information. Wether the proposed coins become available to wallet users depends on the availability of a redundant core-wallet interface ([ROT](https://gitlab.com/c4319/wallet/rot)).

The entries have three parameters: 
- the coin tikker-symbol
- wether the coin is considered a communitycoin, and a default asset in the communitycoins wallet [cc-wallet](https://gitlab.com/c4319/wallet/cc-wallet), or as a guest and an optional asset.
- a proxy-server that mediates between the Ring-of-Trust ([ROT](https://gitlab.com/c4319/wallet/rot)) and the client-wallet
