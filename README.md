# HashCheck Shell Extension by Kai Liu

HashCheck Shell Extension is a Microsoft Windows extension for the Windows File Explorer.

It offers two options:

 1. Generate checksum
      * In right-click menu
      * In file Properties, a new Checksum tab is available
 2. Checksum/hash verification of a file and sidecar checksum file

Can generate/verify CRC-32, MD4, MD5, and SHA-1 checksums.

For build notes see readme.txt

See index.html for docs.

BSD-style license, see license.txt.

TODO Doc Windows 11 right-click menu notes (and restore previous behavior).

# Alternatives

For example, with additional checksum support.

  * https://github.com/idrassi/HashCheck
      * NOTE larger binary
      * https://github.com/gus33000/hashcheck arm64 port
      * https://github.com/gurnec/HashCheck - old fork (but newer than this one) - NOTE larger binary
      * NOTE both forks missing md4 support, so if you have old checksum files this could be problematic:
          * https://github.com/idrassi/HashCheck/issues/13
          * https://github.com/gurnec/HashCheck/issues/81
  * HashTab - lots of checksum options, integrates a new checksum pane into Windows file explorer properties. No generate checksum file support, no verification from explorer (need to bring Hash tab, then select verify file), not supported for commercial use
  * Command line, cross platform
      * md5deep / hashdeep
      * HashIt
  * ?
