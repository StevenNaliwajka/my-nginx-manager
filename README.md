# frontend-gateway
Reverse Proxy + HTTPS cert provider

### Install:
1) Cannot be installed directly onto root (~). Nginx Dies if so...   
'/opt/frontend-gateway' is default.  

```angular2html
sudo git clone https://github.com/StevenNaliwajka/frontend-gateway /opt/frontend-gateway
```
TAKE NOTE: 
- If installed under ANY different name or path. YOU MUST change the path to match in:
```angular2html
/Codebase/Config/path.txt
```

-----
### Setup:
1) Run setup script
```angular2html
bash setup.sh
```

2) Start website or re-starts website.
```angular2html
bash start-nginx.sh
```
----

### Other CMDs:
- Status: Checks the nginx instance to see if its running.
```angular2html
bash status-nginx.sh
```
- Stop: Stops the nginx instance
```angular2html
bash stop-nginx.sh
```