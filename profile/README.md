<p align="center">
  <a href="https://xdrproof.dev">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/xdrproof-banner-dark.gif">
      <img alt="XDRProof: If stellar-core can emit it, your code should survive it. A test kit for every program that reads the Stellar ledger. Beside the motto, a terminal replays real runs recorded on 19 Nov 2026: make verify, where the WASM decoder fails on 13 ledgers stellar-core produced (reported as stellar/js-stellar-xdr-json#67); make conformance, six SDK builds matching every pre-registered result; and a replay of pubnet ledger 56085459 into wallet-backend main, which stores seven balances short (reported as stellar/wallet-backend#834)." src="./assets/xdrproof-banner-light.gif" width="100%">
    </picture>
  </a>
</p>

<p align="center">
  <b><a href="https://xdrproof.dev/docs/start/quickstart">Quickstart</a></b> ·
  <a href="https://xdrproof.dev/docs">Docs</a> ·
  <a href="https://xdrproof.dev/docs/corpus">Corpus</a> ·
  <a href="https://xdrproof.dev/docs/findings">Findings</a> ·
  <a href="https://github.com/XDRProof/xdrproof/blob/main/ARCHITECTURE.md">Architecture</a>
</p>

<p align="center">A test kit for every program that reads the Stellar ledger: rare but valid ledgers that stellar-core actually wrote, each with the answer a correct reader must give, and tools that show exactly where an SDK or indexer breaks.</p>

<table align="center">
  <tr>
    <td><a href="https://github.com/XDRProof/xdrproof"><b>xdrproof</b></a></td>
    <td>The corpus (263 entries, 634 ledger variants), the SDK conformance runner, the indexer replay harness and the xplint linter, each result re-runnable with one command.</td>
  </tr>
</table>

<p align="center">
  <b>Reported upstream:</b>
  <a href="https://github.com/stellar/wallet-backend/issues/834">wallet-backend#834</a> ·
  <a href="https://github.com/stellar/js-stellar-xdr-json/issues/67">js-stellar-xdr-json#67</a> ·
  <a href="https://github.com/stellar/wallet-backend/issues/820#issuecomment-7009772300">wallet-backend#820</a>
</p>

<p align="center"><sub>Independent open-source project. Not affiliated with the Stellar Development Foundation.</sub></p>
