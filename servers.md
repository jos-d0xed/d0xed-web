Servers
=====

Rasputin
--------
Rasputin is our lovely central box that handles our central node, as well as services, and bots. We previously had our central node with RamNode, and whilst cheap, it wasn't the most stable platform. After our /proc became corrupt overnight one evening, it was decided that DigitalOcean would be our new home for the central node, and that two previous nodes and a separate services box would be merged into one. Rasputin is located in Singapore for geographical diversity, and is run by *JoS*.

*Specs*:

   * 512MB RAM
   * 20GB SSD
   * Charybdis 3.5.1
   * Ubuntu Server 14.04 x64

*Connectivity*:

   * rasputin.d0xed.com / 128.199.176.169 / itskm2br5uvlthvi.onion
   * Ports 6667, 6668, 6669 (onion only serves 6667)
   * SSL ports 6697, 9999, 11111 (onion only serves 6697)
   * SSL SHA256 fingerprint: ab:67:fb:03:6d:4f:90:0d:1d:ee:ea:5c:6c:b2:70:89:39:52:40:6e:0b:78:e4:96:85:b5:f1:2d:c1:a3:b4:05
   * SSL SHA1 fingerprint: 0e:72:50:80:c7:0d:70:b8:ac:4e:76:36:9b:86:f8:c1:f7:89:90:05

Spock
-------
Spock has been kindly donated by *cmc*, however, the IRC daemon is maintained by *JoS*. *cmc* oversees the running and maintenance of the server itself, which resides in Washington.

*Specs*:

   * 8GB RAM
   * 500GB HDD
   * Intel Quad Core Xeon
   * Charybdis 3.5.1
   * Ubuntu server

*Connectivity*:

   * spock.d0xed.com / 207.244.154.125
   * Ports 6667, 6668, 6669
   * SSL ports 6697, 9999, 11111
   * SSL SHA256 fingerprint: c0:78:91:d1:b0:00:f9:e0:85:58:1d:6b:9b:14:ae:ff:58:54:4b:f5:9e:32:a7:33:55:8d:2e:db:d8:45:2f:d7
   * SSL SHA1 fingerprint: 35:19:55:63:f3:32:1f:b5:dd:67:59:1d:c3:e9:95:47:09:7e:c1:82

Zeus
--------
*Jarvis* has volunteered Zeus as a willing sacrifice. 

*Specs*:

   * 512MB RAM
   * 40GB SSD
   * *Currently undergoing upgrade to Charybdis - runs no daemon right now*

*Connectivity*:

   * zeus.d0xed.com / 128.199.237.73
   * Ports 6667, 6668, 6669
   * SSL ports 443, 6697, 9999, 11111


GPG Signed Fingerprints
----------------------
```text
-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256


rasputin.d0xed.com:
SHA256 fingerprint: ab:67:fb:03:6d:4f:90:0d:1d:ee:ea:5c:6c:b2:70:89:39:52:40:6e:0b:78:e4:96:85:b5:f1:2d:c1:a3:b4:05
SHA1 fingerprint: 0e:72:50:80:c7:0d:70:b8:ac:4e:76:36:9b:86:f8:c1:f7:89:90:05
spock.d0xed.com:
SHA256 fingerprint: c0:78:91:d1:b0:00:f9:e0:85:58:1d:6b:9b:14:ae:ff:58:54:4b:f5:9e:32:a7:33:55:8d:2e:db:d8:45:2f:d7
SHA1 fingerprint: 35:19:55:63:f3:32:1f:b5:dd:67:59:1d:c3:e9:95:47:09:7e:c1:82

-----BEGIN PGP SIGNATURE-----
Version: GnuPG v2

iQEcBAEBCAAGBQJXR7cLAAoJECy1Z1jHQWoIyT4IAIYlCrDynloOEPvVozw0HGZh
+TAUtSYxGCAnujTqhvX5szOLfFqv67eJupo/Ek4krQ0r0XRupytyhCd8hJwbfBdV
+Hgs8Y6I5klGOfqEN010oIaQle7Br3iSUMH5BdG7/vlCovC3M7WVN2NEii2d+9zA
u59eRWnpWIzOdAL54i4QSYt3Kknm4qeGdPvk2Wqb/ioR90SWW6BPvzpguv9lq9vb
qR7NzQ0VSoz5iH53bZZGavUr3S7LV+z9H9DsykCsx+Gxx/1dnMFThJ1qJk65XuzF
C18kfIxX+gCl+3FPkD3rPCOVe3RLzKRIKYgU31GszslwZAYydynOzqiBrYq0D3o=
=VJjS
-----END PGP SIGNATURE-----
```

Signed with fingerprint [A7E5 738C AB8B 0CF9 3D36  A32B 6EF2 50FF E8AF 29C3](https://keybase.io/jeremyelder)
