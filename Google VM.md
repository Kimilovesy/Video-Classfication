# Tips Using Google VM
## Start my VM

```shell
ssh kimi@timovm
```
## Uplaod Files 
### Upload single file to VM
```shell
scp /path/to/file kimi@timovm:~
```

### Upload the whole directory
```shell
scp -r /path/to/file kimi@timovm:/path/to/file
```

## Remove files
```shell
rm -r /path/to/file
```
