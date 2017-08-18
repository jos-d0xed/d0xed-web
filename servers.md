Servers
=====

Tungsten
--------
Tungsten is our new central box that handles our central node, as well as services, and bots. We previously had our central node with DigitalOcean, and whilst cheap, it didn't quite have the specs we wanted for the price we paid. Tungsten is run by *JoS*, and is located in Tokyo. Tungsten was our first server to run all production images in Docker containers, and as such, it has paved the way for a new style of operations for us.

*Specs*:

   * 1GB RAM
   * SSD storage
   * Charybdis 3.5.5
   * Arch Linux x64

*Connectivity*:

   * tungsten.d0xed.com / 172.104.116.146
   * Ports 6667, 6668, 6669 (onion only serves 6667)
   * SSL ports 6697, 9999, 11111 (onion only serves 6697)
   * SSL SHA256 fingerprint: 6a:4a:55:7d:ed:46:53:13:5c:82:1d:a2:d8:31:7b:a5:2e:66:94:02:d6:ae:36:a8:6f:e1:76:a1:f7:44:43:6e


GPG Signed Fingerprints
----------------------
~~~~
-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256

tungsten.d0xed.com:
SHA256 fingerprint: 6a:4a:55:7d:ed:46:53:13:5c:82:1d:a2:d8:31:7b:a5:2e:66:94:02:d6:ae:36:a8:6f:e1:76:a1:f7:44:43:6e
-----BEGIN PGP SIGNATURE-----

iQFCBAEBCAAsFiEEcgbaTpU1oNB4L3PxLLVnWMdBaggFAlmWarwOHGpvc0BkMHhl
ZC5jb20ACgkQLLVnWMdBagh8WQf+JlUPfl9uuwGhuu2blT4+yAdfnBuvdsjqeP01
OcHMUTV84B4K+NqCa0K6l9uYkhmvWrCjskOfTNMBHSNIBAz9Hu5Qa+HEHsJrYLFt
m75kvvRymqaq7cdv8/L06hMzwfXuJYdv7yWsoF2XlR5nZfWjvODCviAv9m3mp/tT
O0kkx3FUvK0/uUyl5ykGX4s1Y45Wz57SsVquQ/8pd5d0CDCvVTyNhq0WXUz3tg37
yvdVW5yP5AD8wUAiIewPcLHpJc5ai2rK1K8HB9838ywXGQlDpOhwHZaUhSufqGUa
8HEDj/DY8yn6sE9m4/hyi8PXAwyk/W0kSj8knc2fmuJE7fVeMA==
=8vip
-----END PGP SIGNATURE-----
~~~~

Signed with fingerprint [A7E5 738C AB8B 0CF9 3D36  A32B 6EF2 50FF E8AF 29C3](https://keybase.io/jeremyelder)
