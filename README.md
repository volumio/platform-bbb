"# platform-bbb"

Initial version of platform-BBB.

Uses 4.5.0-botic7-rc1 kernel from following source:

Binaries: http://repo.ieero.com/botic/pool/main/l/linux-upstream/
Source: https://github.com/miero/linux-dev/tree/botic7


Includes binary patches for edma and davinci-mcasp compiled from:
https://github.com/miero/botic-dev


By default it uses a standard 'am335x-boneblack.dtb' configuration.

It can be changed by editing the /boot/uEnv.txt file on the booted image.
