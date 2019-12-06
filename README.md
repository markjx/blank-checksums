# blank-checksums

There was a post on a mailing list where someone was looking for checksums (sha1 & md5) of various sized blockes of NULL (0x00) bytes.
I created a script to create LOTS (250,000 or so) various sized blocks of NULL's, up to 100MB in size.
I then ran md5sum & sha1sum against each block, and recorded the results.
Finally I uploaded them here in case they can help anyone else.
