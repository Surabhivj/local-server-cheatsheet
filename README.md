# local-server-cheatsheet

**Get connected to server**

```
ssh username@server_address
```
**upload folder from local machine to server**

```
scp -r folder_name username@server_address:/target_directory
```

**Download folder from local machine to server**

```
scp -r username@server_address:/target_directory /local/dir
```
**Remove directory**
If empty:
```
rm -d dirname 
rmdir dirname
```

non empty
```
rm -r dirname
```
**Remove file**
```
rm filename 
```



