# `wslpath`

Path conversion utility in the style of `cygpath` that mounts all drive letters under `/mnt/c`.

```sh
$ wslpath C:\\Code\\
/mnt/c/Code
$ $(wslpath C:\\Windows\\System32\\notepad.exe)
<notepad.exe opens>
```