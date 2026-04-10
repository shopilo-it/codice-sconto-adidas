# Cod reducere Adidas — fetch automat de pe shopilo.it

Modul Python pentru fetch automat de **coduri de reducere Adidas** de pe [shopilo.it](https://shopilo.it/magazin/adidas.it). Returneaza **cupoane Adidas** active in format JSON, gata de integrat intr-un bot Telegram, extensie de browser sau orice alt tool.

**Pagina live:** [shopilo-it.github.io/codice-sconto-adidas](https://shopilo-it.github.io/codice-sconto-adidas/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Instalare

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-it/codice-sconto-adidas
cd codice-sconto-adidas
python fetch.py
```

## Output exemplu

```json
[
  {
    "store": "Adidas",
    "code": "SHOPILO20",
    "discount": "20%",
    "description": "20% di sconto su scarpe e abbigliamento",
    "expires": "2026-10-10",
    "source": "https://shopilo.it/magazin/adidas.it"
  }
]
```

## Cupoane Adidas disponibile

| Reducere | Descriere | Sursa |
|----------|-----------|-------|
| 20% | 20% di sconto su scarpe e abbigliamento | [shopilo.it](https://shopilo.it/magazin/adidas.it) |

Codurile active: **[shopilo.it/magazin/adidas.it](https://shopilo.it/magazin/adidas.it)**

## Intrebari frecvente

### Cum folosesc un cod de reducere Adidas?
Copiaza codul din tabelul de mai sus sau de pe [shopilo.it](https://shopilo.it/magazin/adidas.it), adauga produsele in cos pe Adidas, si introdu codul la checkout in campul dedicat.

### Cat timp sunt valabile cupoanele Adidas?
Fiecare cupon are data de expirare afisata in coloana "Expira". Scriptul fetch.py returneaza doar cupoanele active la momentul rularii.

### Unde gasesc cele mai noi voucher-uri Adidas?
Pagina [shopilo.it/magazin/adidas.it](https://shopilo.it/magazin/adidas.it) este actualizata zilnic cu cele mai noi cod reducere Adidas, voucher Adidas si cupon promotional Adidas.

### Codul nu functioneaza. Ce fac?
Verifica data de expirare si conditiile (valoare minima cos, produse eligibile). Unele coduri sunt valabile doar in aplicatia mobila sau pentru prima comanda.

## Despre Adidas

Adidas este unul dintre magazinele online populare. Gasesti pe [shopilo.it](https://shopilo.it/magazin/adidas.it) cele mai bune cod reducere Adidas, cupoane Adidas verificate si voucher Adidas active, actualizate zilnic.

## Instalare npm

```bash
npm install codice-sconto-adidas
```

```javascript
const { fetchCoupons } = require('codice-sconto-adidas');
fetchCoupons().then(data => console.log(data));
```

## Licenta

MIT — date sursa de pe [shopilo.it](https://shopilo.it)
