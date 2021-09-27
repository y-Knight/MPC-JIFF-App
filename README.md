# MPC-JIFF-App

## Enviroment

docker
Node.js v16.3

## Get Started

### Docker Setting

```
docker-compose build --no-cache
```

```
docker-compose up -d
```

```
docker exec -it mpcdev_container sh
```

## Container setting

```
mv /tmp/jiff /mpc_dev
cd /mpc_dev/jiff
```

```
npm install or yarn install
```

Edit a packege.json file

```:/package.json
scripts {
    "sum": "node index.js demos/sum/server", // add this
}
```

## Start Sample App(sum-server)

```
yarn sum
```

### Access to Local connection(client)

```
http://localhost:18880/demos/sum/client.html.
```
