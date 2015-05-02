The proposed solution advocates embedding ComicBookInfo metadata in the zip comment of CBZ digital comics.

The de facto standard for distributing digital comics has been compressed archives, primarily the CBZ and CBR file formats, which are simply a folder of images, compressed with ZIP or RAR respectively.

RAR's compression algorithm is proprietary and a closed format, making it difficult for software developers to add RAR archive creation and manipulation at low-cost (one needs to apply and pay for a license).  How to embed ComicBookInfo metadata in the comment section of CBR digital comics is unknown and unlikely to be easily implemented.  In contrast, ZIP is an open format, freely available across all major operating systems, with source code available.

Software developers on Mac, Linux, Windows and other platforms are free to add ComicBookInfo support to CBR and PDF comics, as they see fit, although the results may not be cross-platform.

On Mac OS X, ComicBookLover supports metadata for CBZ, CBR and PDF comics by making use of extended attributes, a feature of the system's default HFS+ file-system.  Spotlight can index the metadata stored in the extended attributes, thus allowing users to search digital comics for metadata as easily as text or PDF documents.  However, only CBZ comics will have the metadata embedded in the file itself, allowing the comic's metadata to be examined and updated by other comic reader applications on other operating systems.