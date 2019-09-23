# game-seeder
Become a Game Distribution Company in 3 Commands!

Create a VPS account

list of Providers that offer Unmettered Traffic:
https://ungleich.ch/
https://zetservers.com/
https://www.vps9.net/
https://www.fastpipe.io/
https://servercheap.net/
https://www.primahost-ng.com/
https://www.enoctus.co.uk/
https://www.zelon.com/
https://afterburst.com/
https://www.ovh.com/
https://buyvm.net/
https://contabo.com/

I can vouch for OVH. For $3.50 you can get syymetrical 100Mbit/s traffic. Perfect for non gigabit home internet.

Create a Ubuntu 18.04 VM

Run Wireguard Ansible playbook to setup VPN Server.

Connect client to VPN.

Use the mirror option to recursivly download a whole site. Not Google of course!...though I havent tried.

wget --mirror fitgirl-repacks.site

I have included a mirror of the site in my repo. I suggest you use mine as to not take their site offline.

Grep command with search pattern to extract magnet link hash.This hash can be imported into clients such as qBittorent.

grep -RisIowh "[[:xdigit:]]\{40\}" * | sort --unique > master.txt

this will leave you with a very large list of hashes.

Optional hardware:
raspberry pi
6 TB HDD
SATA Adapter

Security:

Sources:

