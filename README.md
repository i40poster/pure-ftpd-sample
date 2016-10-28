# pure-ftpd-sample

Running:
```bash
docker run -d --name FTP -p 21:21 -p 30000-30009:30000-30009 -v /some/path/to/share:/srv/ftp -e USER=ftpuser1 -e PASSWORD=qaz123 i40poster/pure-ftpd-sample
```
