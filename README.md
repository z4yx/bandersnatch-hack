```shell
echo tensorflow >packages-to-sync.list
echo requests >>packages-to-sync.list
echo lalsuite >>packages-to-sync.list
./src/main.py -c /path-to/bandersnatch.conf mirror
```
