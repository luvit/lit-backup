lit-backup
==========

Backup of the lit.luvit.io packages

The lit repo format is a git compatable database, but it doesn't use commits, so the github UI will break if you try to browse the tags.  Hopefully they fix this someday.

Currently this is manually synced from the lit.luvit.io server.

Currently lit can't read packed refs or objects, so if you clone this, you'll need to unpack the git repo before lit can use it. <https://www.kernel.org/pub/software/scm/git/docs/git-unpack-objects.html>

