![github](https://user-images.githubusercontent.com/111548547/192037827-733a5483-905a-4964-91d1-7e4cbf03fae9.png)

[![Generic badge](https://img.shields.io/badge/ferum-docs-blue.svg)](https://ferum.gitbook.io/ferum-dex/) ![](https://img.shields.io/discord/1014040797487824896?label=discord) ![](https://img.shields.io/badge/liquidity-high-brightgreen)


# Ferum Margin Trading Example

This is the complete code from the [Building a Margin trading Protocol on Ferum Tutorial](https://docs.ferum.xyz/quickstart-guides/building-a-margin-trading-protocol-on-ferum).

## Compile locally

Install the Aptos CLI. The framework dependency follows `devnet`, matching the
Ferum contract dependency. Supply the named `ferum` address when compiling:

```sh
aptos move compile --named-addresses ferum=0x42
```

`0x42` is only an example address for offline compilation. When preparing a
deployment, replace it with the address of the Ferum deployment you intend to use.
Compilation does not publish modules or submit transactions.
