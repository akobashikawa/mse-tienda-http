# mseTienda HTTP

- Frontend simple para mseTienda.
- Vue3 usando importmap (sin builder) [Quick Start | Vue.js](https://vuejs.org/guide/quick-start.html#using-vue-from-cdn)
- Macha.css [matcha.css | Drop-in semantic styling library in pure CSS](https://matcha.mizu.sh/)


## Install con docker

- Levantará un web server nginx en el puerto 3000

```sh
docker build -t tienda-http .

docker run \
    --name tienda-http \
    -p 3000:80 \
    tienda-http

# test
curl http://localhost:3000/
```


## Run con docker

```sh
docker start tienda-http

# test
curl http://localhost:3000/
```

## Run con docker-compose

- Levantará un web server nginx en el puerto 3000

```sh
docker-compose up --build

# test
curl http://localhost:3000/
```
