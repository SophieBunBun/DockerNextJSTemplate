## Useful commands:

### 1. Build:
```
docker compose build
```
### 2. Run dev:
.bat
```
set NPM_TARGET=dev
set RESTART=no
set WATCHPACK_POLLING=true
docker compose -f docker-compose.yml -f attach-volumes.yml up
```
.sh
```
NPM_TARGET=dev
RESTART=no
WATCHPACK_POLLING=true
docker compose -f docker-compose.yml -f attach-volumes.yml up
```
### 3. Start:
```
docker compose up
```
