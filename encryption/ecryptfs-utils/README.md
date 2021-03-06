# ecryptfs-utils

* Homepage: https://launchpad.net/ecryptfs

eCryptfs is a POSIX-compliant enterprise-class stacked cryptographic filesystem
 for Linux.

 It provides advanced key management and policy features. eCryptfs stores
 cryptographic metadata in the header of each file written, so that encrypted
 files can be copied between hosts; the file will be decryptable with the proper
 key, and there is no need to keep track of any additional information aside
 from what is already in the encrypted file itself. Think of eCryptfs as a sort
 of "gnupgfs".

 eCryptfs is a native Linux filesystem. The kernel module component of eCryptfs
 is part of the Linux kernel since 2.6.19.

 This package contains the userland utilities.
