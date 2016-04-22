# Fuse-File-System-OS_proj<br>
Implemented a custom designed file system in C mounted by FUSE module.<br>
Simulated a unix-like file system related to working with block devices.<br>
#User-Defined Operations<br>
Supported directories, files with various sizes and basic Linux file management operations.<br>
super block format:
{creationTime: 1376483073,   mounted: 50, devId:20, freeStart:1, freeEnd:25, root:26, maxBlocks:10000}
<br>
Maximum number of blocks: 10,000<br>
Maximum file size: 1,638,400 bytes<br>
Block size: 4096 bytes<br>
each directory format:<br>
{size:1033, uid:1000, gid:1000, mode:16877, atime:1323630836, ctime:1323630836, mtime:1323630836, linkcount:4, filename_to_inode_dict: {f:foo:1234, d:.:102, d:..:10, f:bar:2245}}
