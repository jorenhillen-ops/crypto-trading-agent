# Crypto Trading Agent update channel

Dit repository wordt gebruikt als centrale updatebron voor de lokale Crypto Trading Agent.

- De lokale app blijft in **paper trading** zolang live execution niet expliciet wordt toegevoegd.
- Lokale `.env`, paperdatabase, runtime en logs worden niet in dit repository opgeslagen.
- Binance API-secrets horen nooit in deze repository.
- `VERSION` bepaalt of het dashboard een nieuwe update detecteert.
- `package.parts` + `package.partXX` bevatten het applicatiepakket dat de Windows-updater downloadt.

De huidige paper-configuratie start met €100 en gebruikt BTC/EUR + ETH/EUR, zonder leverage.
