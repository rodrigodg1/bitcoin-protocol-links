

## Bitcoin Core

### Algumas informações sobre o protocolo a partir do código fonte

**1. Criação do bloco *genesis* (primeiro bloco da cadeia)**
- [https://github.com/bitcoin/bitcoin/blob/master/src/chainparams.cpp#L18-L37](https://github.com/bitcoin/bitcoin/blob/master/src/chainparams.cpp#L18-L37)

**2. A Famosa mensagem do primeiro bloco:** *The Times 03/Jan/2009 Chancellor on brink of second bailout for banks*
- [https://github.com/bitcoin/bitcoin/blob/master/src/chainparams.cpp#L52-L52](https://github.com/bitcoin/bitcoin/blob/master/src/chainparams.cpp#L52-L52)

**3. O primeiro bloco** [https://www.blockchain.com/explorer/blocks/btc/0](https://www.blockchain.com/explorer/blocks/btc/0)

**4. Definição do total de bitcoins (21 milhões)**
- [https://github.com/bitcoin/bitcoin/blob/master/src/consensus/amount.h#L26](https://github.com/bitcoin/bitcoin/blob/master/src/consensus/amount.h#L26)

**5. Definição da equivalência de satoshis em um BTC**
- [https://github.com/bitcoin/bitcoin/blob/master/src/consensus/amount.h#L15](https://github.com/bitcoin/bitcoin/blob/master/src/consensus/amount.h#L15)

**6. Todos os parâmetros da rede principal (*mainnet*)**
- [https://github.com/bitcoin/bitcoin/blob/master/src/chainparams.cpp#L60-L177](https://github.com/bitcoin/bitcoin/blob/master/src/chainparams.cpp#L60-L177)

**7. Halving interval** ocorre em aproximadamente 4 anos. Refere-se a diminuição das recompensa ao minerar o bloco: ** https://academy.binance.com/en/halving.
- [https://github.com/bitcoin/bitcoin/blob/master/src/chainparams.cpp#L66](https://github.com/bitcoin/bitcoin/blob/master/src/chainparams.cpp#L66)

**8. O cálculo da recompensa em si**
- [https://github.com/bitcoin/bitcoin/blob/master/src/validation.cpp#L1471-L1482](https://github.com/bitcoin/bitcoin/blob/master/src/validation.cpp#L1471-L1482)

**9. Definições do ajuste de dificuldade da rede:** A dificuldade de mineração do Bitcoin é ajustada automaticamente aproximadamente a cada duas semanas para manter o tempo total de bloco (block time) em 10 minutos.
- [https://github.com/bitcoin/bitcoin/blob/master/src/chainparams.cpp#L79](https://github.com/bitcoin/bitcoin/blob/master/src/chainparams.cpp#L79)
