### Set proxy for npm:
- `npm config set proxy http://proxy:8080`
- `npm config set https-proxy http://proxy:8080`

### Set proxy for git:
- `git config --global http.proxy http://proxy:8080`
- `git config --global https.proxy http://proxy:8080`


### The command to reset proxy for npm 
- `npm config rm proxy`
- `npm config rm https-proxy`

### reset proxy for git
- `git config --global --unset http.proxy`
- `git config --global --unset https.proxy`

### get proxy setting for git
- `git config --global --list`
- `npm config get list`
- `npm config get proxy`
- `npm config get https-proxy`
