[![Build Status](https://travis-ci.org/wtanaka/ansible-role-exfat.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-exfat)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-exfat.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-exfat)

wtanaka.exfat
=============

Installs exFAT support

exFAT (Extended File Allocation Table) is a Microsoft file system
optimized for flash memory such as USB flash drives and SD cards.
It is proprietary and Microsoft owns patents on several elements of
its design.

exFAT can be used where the NTFS file system is not a feasible
solution (due to data structure overhead), yet the file size limit of
the standard FAT32 file system is unacceptable.

exFAT has been adopted by the SD Card Association as the default file
system for SDXC cards larger than 32 GiB.

( description from https://en.wikipedia.org/wiki/ExFAT under
https://creativecommons.org/licenses/by-sa/3.0/ )

Example Playbook
----------------

    - hosts: servers
      roles:
         - wtanaka.exfat

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
