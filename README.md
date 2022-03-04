# sshDump

## About:
* Title: sshDump
* Description: Taking advantage of plain stored ssh private keys in home dir, sshDump grabs them for you.
* AUTHOR: drapl0n
* Version: 1.0
* Category: Credentials
* Target: GNU/Linux
* Attackmodes: HID, Storage

## sshDump is BashBunny payload which takes advantage of unencrypted ssh private keys stored in home directory and loots them.


### Workflow:
1. Prevent storing history.
2. Fetching BashBunny's block device.
3. Mounting BashBunny.
4. Looting ssh keys.
5. Unmounting BashBunny.

#### Support me if you like my work:
* https://twitter.com/drapl0n
