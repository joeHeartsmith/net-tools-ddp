# net-tools-ddp
[PATCH] AppleTalk pathnames in /proc/net

This is a patch submission for [net-tools](https://sourceforge.net/projects/net-tools/).  For small projects not requiring a pull request, or where maintainers prefer e-mail patch submissions, I keep copies here for reference/download.

- File: ./lib/ddp.c, ./lib/pathnames.h
- Submission Date: 2021-08-01
- Commit Date: N/A

Summary: Fixes support for AppleTalk when using `ifconfig` or `route` on Linux >= 2.5.41.  Also replaces a hard-coded string in `./lib/pathnames.h` with the correct variable.
