Servers
=====

Rasputin
--------
Rasputin is our lovely central box that handles our central node, as well as services, and bots. We previously had our central node with RamNode, and whilst cheap, it wasn't the most stable platform. After our /proc became corrupt overnight one evening, it was decided that DigitalOcean would be our new home for the central node, and that two previous nodes and a separate services box would be merged into one. Rasputin is located in Singapore for geographical diversity, and is run by *JoS*.

*Specs*:

   * 512MB RAM
   * 20GB SSD
   * ngIRCd 22
   * Ubuntu Server 14.04 x64

*Connectivity*:

   * rasputin.d0xed.com / 128.199.176.169 / itskm2br5uvlthvi.onion
   * Ports 6667, 6668, 6669 (onion only serves 6667)
   * SSL ports 6697, 9999, 11111 (onion only serves 6697)
   * SSL SHA1 Fingerprint=E4:40:3F:7A:81:47:9D:4A:AF:B7:3E:23:98:8C:D9:23:9A:C2:63:55

Spock
-------
Spock has been kindly donated by *cmc*, however, the IRC daemon is maintained by *JoS*. *cmc* oversees the running and maintenance of the server itself, which resides in Washington.

*Specs*:

   * 8GB RAM
   * 500GB HDD
   * Intel Quad Core Xeon
   * ngIRCd 21.1
   * Ubuntu server

*Connectivity*:

   * spock.d0xed.com / 207.244.154.125
   * Ports 6667, 6668, 6669
   * SSL ports 6697, 9999, 11111
   * SSL SHA1 Fingerprint=79:B9:38:9B:57:B2:C6:F9:F4:D9:55:66:C3:AA:1B:E4:F8:78:9A:1D

Zeus
--------
*Jarvis* has volunteered Zeus as a willing sacrifice. 

*Specs*:

   * 512MB RAM
   * 40GB SSD
   * ngIRCd 23 

*Connectivity*:

   * zeus.d0xed.com / 128.199.237.73
   * Ports 6667, 6668, 6669
   * SSL ports 443, 6697, 9999, 11111
   * SSL SHA256 Fingerprint=09:58:7f:8e:3a:fb:07:ad:fc:a6:33:af:20:46:42:e1:9a:25:59:b5:53:23:6a:7e:bb:16:56:1b:aa:ef:2d:e2
   * SSL SHA1 Fingerprint=92:2c:7a:f3:ed:d3:ab:8d:7c:8a:64:44:53:4a:16:f3:65:98:85:76
