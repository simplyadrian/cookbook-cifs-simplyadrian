cifs-simplyadrian Cookbook
=====================
Just (at least initially) a bare-bones cookbook to install the
"Common Internet File System" (CIFS) (formerly known as
"Server Message Block" (SMB)) system package so that you can connect to volumes
via Windows file sharing protocols.

http://technet.microsoft.com/en-us/library/cc939973.aspx
https://en.wikipedia.org/wiki/CIFS

Usage
-----
Just include `cifs-simplyadrian` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[cifs-simplyadrian]"
  ]
}
```

License and Authors
-------------------
Authors: Adrian Herrera