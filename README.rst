GDataCopier 2
=============

GDataCopier provides comprehensive set of tools for System Administrators (mostly on Unix like platforms) to list, manage, backup and synchronise documents stored on Google's Document Service. Some major features are:

- scp like syntax to list and copy documents
- filter documents based on folders, file names
- supports hosted and gmail accounts
- syncs date stamps with server
- download updated files only (great for offsite backup implementations)
- warn on overwrite (can override with parameters)
- summary of operations
- update document content using gcp
- move, remove, or make directories and organise your documents
- choose export format using command line parameter (defaults to OpenDocument formats)

GDataCopier is currently considered stable and is an active project. Please report any issues to us by emailing the authors or posting it on the Google group or issue tracker.

GDataCopier is NOT affiliated with Google in anyway.

Requirements:

- Python 2.6 and above
- GData Python Client Library 2.0.16 and above
- Ability to establish HTTPS connections to Google's servers (check with your sys admin if you use proxies)
- Python Keyring library

About the Developers
^^^^^^^^^^^^^^^^^^^^

GDataCopier was developed and is maintained by Devraj Mukherjee. Devraj spends most of his time running Eternity Technologies a high end Web / Mobile technology company.

A large part of the development over time has been funded by De Bortoli Wines.
