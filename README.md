# EncFS (Enc rypted FileSystem)

EncFS runs in userspace, using the FUSE library for the filesystem interface.

EncFS encrypts individual files, by translating all requests for the virtual 
filesystem into the equivalent encrypted operations on the raw filesystem.