# Bitcoin Wallet Finder
Checks Bitcoin Private Keys for Balance using bitcoinlist.io <br>
Hits will be saved to a text file
Current version can generate around 2M wallets/s.

This tool is for educational purposes ONLY!

# Feature
<ul>
  <li>Fixed size arithmetic</li>
  <li>Fast Modular Inversion (Delayed Right Shift 62 bits)</li>
  <li>SecpK1 Fast modular multiplication (2 steps folding 512bits to 256bits using 64 bits digits)</li>
  <li>Use some properties of elliptic curve to generate more keys</li>
  <li>SSE Secure Hash Algorithm SHA256 and RIPEMD160 (CPU)</li>
  <li>Multi-GPU support</li>
  <li>CUDA optimisation via inline PTX assembly</li>
  <li>Seed protected by pbkdf2_hmac_sha512 (BIP38)</li>
  <li>Support P2PKH, P2SH and BECH32 addresses</li>
  <li>Support split-key vanity address</li>
</ul>

# Show Your Support

* Donate To Me VIA bitcoin: bc1q8djfqet6tu94afx9n7j528dd8e28d53kzm7hsw
* Donate To Me VIA litecoin: ltc1qf5wh42ayjmdv9jzw6y9ah4qkl562he2eenl97t
* Donate To Me VIA ethereum: 0xC2B73BAD8Cdb400d99A372Ce31747Af9ff8e6dD8