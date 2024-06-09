# Introduction
I've ripped hundreds of CD's with abcde and before I embark on the next few hundred, I want to fix some bugs and have a go at some enhancements.

My ripping objective is to create lossless music tracks (flac) for listening and also to record as much information from the read process as possible for archival posterity, such as cue sheet, CD-TEXT, enhanced CD directory listing, media read progress/status/errors and metadata downloaded.

# Testing
- OS: Ubuntu 22.04.4
- Hardware: x64 with two SATA CDROMs

# Features
- applied many patches from bug reports: https://abcde.einval.com/bugzilla/query.cgi
- applied many patches from the mailing list: https://lists.einval.com/cgi-bin/mailman/listinfo/abcde-users


## Enhancements
- Improved the handling of album art selection. It is now possible to define a default local album art directory/file location
- Improved handling of CD sets (-W). The option is expanded to optionally add the total number of discs in the set. The details are recorded in the metadata and there are some improvements to the workflow, eg create playlist defaults to append instead of erase when the disc number is greater than 1. (IN PROGRESS)

## Todo


# Known issues
- tested only with flac encoding
- one-track flacs: embedded cue sheet does not include track titles
