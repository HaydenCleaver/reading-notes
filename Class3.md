# Class 3 Reading Notes

### Version Control

A Version Control System (VCS) allows you to track changes made to a file and revert them to an earlier format/file if necessary.

***

**Local Version Control**

A singular database on a hardisk that stores changes to files for the user alone.

**Centralized Version Control System (CVCS)**

A single server that stores all files versions and changes.  Can be accessed by multiple users, allowing collaborative work and knowledge of others' changes.

**Distributed Version Control System (DVCS)**

Similar idea to CVCS, but it uses mirrored repositories that can be in multiple locations.  This prevents the loss/corruption of data due to being located in one place alone since data can be easily backed up.  Also allows for simultaneous workflow.

***

### Git

Git is a DVCS that stores data in a file system made of snapshots.

***

**ACP**

In order to update and sync the files from your computer to an application like Github, it needs to go through a process known as ACP.

- Add: local changes to the file must be staged to be saved/snapshotted to the file.
- Commit: this saves the changes and a comment can be added to indicate what was changed
- Push: this pushes the altered file out to the application and syncs it with your local file.

***

### Random Notes

Usually, one project = one repository