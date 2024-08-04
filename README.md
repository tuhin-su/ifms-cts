# IFMS-CTS
dotnet(api) and postgresql server only

## SETUP GUID
### clone repo
```bash
    git clone https://github.com/tuhin-su/ifms-cts.git

    cd ifms-cts
```
### install docker or docker-compose
[Official guide by docker](https://docs.docker.com/engine/install/)

### Build dependency
```bash
    git submodule init
    git git submodule update 
```

### start docker
```bash
    docker-compose up -d
```

####
```bash
    docker compose up -d
```

### stop docker
```bash
    docker-compose down -d
```
#### 
```bash
    docker compose down -d
```