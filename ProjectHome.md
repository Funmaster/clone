**clone** is a file tree cloning tool which runs 3 threads - a scheduler (main), a reader,
and a writer thread. Reading and writing occurs in parallel. While this is most beneficial
for copying data from one physical disk to another, clone is also very well suited
for cloning a file tree to any place on the same disk.

Cloning includes the whole directory hierarchy, i.e. sub-directories, files, hard links,
symbolic links, attributes (modes, flags, times), extended attributes and access control lists.

**clone** is useful for cloning (thus backing-up) live file systems, and it can also be used in
incremental and synchonization mode.

**clone** works on FreeBSD and Mac OS X.

**clone** is very fast, for example, cloning a whole UFS2 file hierarchy on FreeBSD 9.1 of in total
2.3 TBytes of data from one hard disk to another took 7.5 h, so the average transfer rate
for all kind of files (very small up to very big ones) was about 89 MByte/s.

The downloads had to be moved to the **clone Google Drive**

>      https://drive.google.com/folderview?id=0BzyUSAiURzitVGlOeXFsTW9XOVk

The latest snapshot is clone-1.0.5.tar.gz
(SHA256 = 8504bfe11c3329f6908198641ca5a15dce1965cb71309fe0c52bf85a9990fce2):

>      https://googledrive.com/host/0BzyUSAiURzitVGlOeXFsTW9XOVk/clone-1.0.5.tar.gz


---

On my [BLog](http://blog.obsigna.net/), I posted an article in German language on how to employ **clone** for the [Backup Strategy of a FreeBSD Home Server](http://blog.obsigna.net/?p=475). Please use the [Google Translator](https://translate.google.com/translate?sl=de&tl=en&js=y&prev=_t&hl=de&ie=UTF-8&u=http%3A%2F%2Fblog.obsigna.net%2F%3Fp%3D475&edit-text=) in order to translate this BLog post into your favorite language.