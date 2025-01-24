# InterPlanetary File System

```
git clone https://github.com/mclitos/ipfs
```

```
cd ipfs
```

```
 docker compose up -d
```

```
 docker compose logs
```

Ver en "http://localhost:5001/webui" ó IP:5001/webui

Una Vez en el WEB UI hay que hacer varios pasos 

En la consola 
Buscamos la Id del Contenedor
```
 docker ps -a
```
si no estas root , poner root
```
sudo su
```
 En el WebUI aparecera varios paso ubicarse en el paso 2 
```
Docker exec (id del contenedor) o ipfs (y la primera Linea del paso 2 que sale en el WebUI
```

```
Docker exec (id del contenedor) o ipfs (y la segunda Linea del paso 2 que sale en el WebUI
```
Reiniciamos el contenedor 
```
Docker restart ipfs
```


