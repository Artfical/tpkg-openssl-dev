# openssl-dev

OpenSSL 3.0.2 headers and libraries (libssl.a, libcrypto.a, libssl.so, libcrypto.so) for building programs with gcc

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install openssl-dev
```

| | |
|---|---|
| Version | 3.0.2 |
| Licence | Apache-2.0 |
| Upstream | https://www.openssl.org |
| Needs | [`gcc`](https://github.com/Artfical/tpkg-gcc), [`openssl`](https://github.com/Artfical/tpkg-openssl) |
| Needs tOS build | 615 or newer |
| Size | 5238671 bytes (17436706 unpacked) |
| SHA-256 of the `.tpkg` | `41ffc27c111ebf43f42b548e25b41e1ecf35a92eb9d8dc3b1b7d052dd6a0812b` |

## Commands it adds

| Command | Runs |
|---|---|
| - | - |

## Download

The package file (`openssl-dev-3.0.2.tpkg`) and the sources it was built from are the assets of the
[v3.0.2 release](https://github.com/Artfical/tpkg-openssl-dev/releases/tag/v3.0.2).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `openssl-3.0.2.tar.gz`

Check a download: `sha256sum openssl-dev-3.0.2.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: Apache-2.0. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
