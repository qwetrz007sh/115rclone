What's Changed
add support for processing a share link (see usage below)
How to Update
```
curl -fsSL https://raw.githubusercontent.com/wiserain/rclone/mod/install.sh | sudo bash
``` 
Usage for a share link
Config remote for shared file system
`
Using rclone.conf
```
[115]
type = 115
share_code = shareCode
receive_code = receiveCode
uid = 
cid = 
seid = 
```
