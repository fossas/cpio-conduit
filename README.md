# cpio-conduit: a Haskell conduit-based CPIO encoder/decoder

This is a native Haskell implementation of the CPIO protocol over the Conduit library. See [GNU's cpio](http://www.gnu.org/software/cpio/).

Only the commonly used CPIO formats are supported (crc and newc).

## Forking notes

This project is potentially unmaintained, and some changes in upstream packages caused this package to become unable to build.  We are setting sane build boundaries so that this does not repeat in the future.
