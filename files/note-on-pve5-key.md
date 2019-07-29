# Proxmox 5 key
PVE team changed their keys from pve3 and 4 to a newer one.

pub   rsa4096 2016-08-29 [SC] [expires: 2026-08-27]
      359E95965E2C3D643159CD300D9A1950E2EF0603
uid           Proxmox Virtual Environment 5.x Release Key <proxmox-release@proxmox.com>

If it's downloaded from their site, it's a binary gpg key(http://download.proxmox.com/debian/proxmox-ve-release-5.x.gpg).

The following command can then convert it to asc:

gpg --enarmor proxmox-ve-release-5.x.gpg

then a new asc key is created:

qwe@ws:~/tmp$ ls
proxmox-ve-release-5.x.gpg
proxmox-ve-release-5.x.gpg.asc

which is the same as the key in this dir, but looks like this:

-----BEGIN PGP ARMORED FILE-----
Comment: Use "gpg --dearmor" for unpacking
...
-----END PGP ARMORED FILE-----