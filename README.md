BARK: SYNC2TARGET
=========

Automation to copyh files from Ansible host to remote target machine.

Requirements
------------

All roles in the Bitmotive Ansible Role Kit are configuration driven.

Customize this role by providing environment variables in either your
shell environment, host specific in group_vars/, or at the CLI when
prompted at runtime. 

Role Variables
--------------

**SYNC2TARGET_HOST_FILEPATH**:

The filepath on the local ansible machine with the files to be copied.

**SYNC2TARGET_TARGET_FILEPATH**:

The filepath on the remote machine to copy the files.


**SYNC2TARGET_TARGET_FILEPATH_GROUP**

The group on the remote machine that should own the files.

**SYNC2TARGET_TARGET_FILEPATH_USER**

The user on the remote machine that should own the files.

**SYNC2TARGET_TARGET_FILEPATH_PERMS**

The permissions that should be set on the remote machine's files.


Dependencies
------------

Unix/Linux system commands.

License
-------

MIT

Author Information
------------------

A Bitmotive Project: Build. Incubate. Train.
https://bitmotive.com 
