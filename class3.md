
# Class 3 Reading notes

### Intro to Git

#### Version Control

Version control is a system that allows you to revisit various versions of a file or set of files by recording changes

There are differnent types of Version Control Systems (VCS):

- **Local Version control**, which entails one database on your hard disk that stores changes to files
- **Centralized Version Control** (CVCS), which entails a single server storing all changes and file versions, which can be accessed by various clients
- **Distributed Version Control** (DVCS), which addresses a major vulnerability of CVCS: that the server is a single point of failure. DVCS allows clients to create mirroed repositories, backing up the data on the server

#### Git

Git is a DVCS that stores data in a file system made up of snapshots created every time you save a changed version of the project,known as commit

Git relies mostly on local operations, eliminating the need to fetch information from the server

Every single change is tracked, and it is extremely difficult for a snapshot that is committed to be lost

Files in Git can reside in three main states:

- Committed - data is securely stored in a local database
- Modified - file has been changed but not committed
- Staged - flagged a file's changed version to be committed in the next snapshot

