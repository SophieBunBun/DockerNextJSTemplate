<h2>Useful commands:<h2>

<ol>
<li><h3>Build:<h3>
```
docker compose build
```<li>
<li><h3>Run dev:<h3>
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
```<li>
<li><h3>Start:<h3>
```
docker compose up
```<li>
<ol>
