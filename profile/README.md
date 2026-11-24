<p align="center">
  <a href="https://xdrproof.dev">
    <img alt="XDRProof: If stellar-core can emit it, your code should survive it. A test kit for every program that reads the Stellar ledger. Beside the motto, a terminal plays a real run of make verify recorded on 24 Nov 2026: 634 corpus ledgers read back byte for byte, 1,715 expected values hold, and the second reader, stellar-xdr-json, refuses 13 very deep ledgers stellar-core produced (reported as stellar/js-stellar-xdr-json#67)." src="./assets/xdrproof-banner.svg" width="100%">
  </a>
</p>

<p align="center">
  <b><a href="https://xdrproof.dev/demo">▶ Pitch film (3 min)</a></b> ·
  <b><a href="https://xdrproof.dev/docs/start/quickstart">Quickstart</a></b> ·
  <a href="https://xdrproof.dev/docs">Docs</a> ·
  <a href="https://xdrproof.dev/docs/corpus">Corpus</a> ·
  <a href="https://xdrproof.dev/docs/findings">Findings</a> ·
  <a href="https://github.com/XDRProof/xdrproof/blob/main/ARCHITECTURE.md">Architecture</a>
</p>

<p align="center">A test kit for every program that reads the Stellar ledger: rare but valid ledgers that stellar-core actually wrote, each with the answer a correct reader must give, and tools that name the exact ledger and check an SDK or indexer gets wrong.</p>

<table align="center">
  <tr>
    <td><a href="https://github.com/XDRProof/xdrproof"><b>xdrproof</b></a></td>
    <td>The corpus (263 entries, 634 ledger variants), the SDK conformance runner, the indexer replay harness and the xplint linter, each result re-runnable with one command.</td>
  </tr>
</table>

<p align="center">
  <b>New bugs reported:</b>
  <a href="https://github.com/stellar/wallet-backend/issues/834">wallet-backend#834</a> ·
  <a href="https://github.com/stellar/js-stellar-xdr-json/issues/67">js-stellar-xdr-json#67</a><br>
  <b>Fix offered:</b>
  <a href="https://github.com/stellar/wallet-backend/issues/820#issuecomment-7009772300">a tested bound on wallet-backend#820</a><br>
  <b>Evidence added:</b>
  <a href="https://github.com/lightsail-network/java-stellar-sdk/issues/835#issuecomment-7016550020">13 deep ledgers on java-stellar-sdk#835</a>
</p>

<p align="center"><sub>Independent open-source project. Not affiliated with the Stellar Development Foundation.</sub></p>
