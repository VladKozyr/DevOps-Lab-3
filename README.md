# DevOps-Lab-3
 
## Build
```
docker build -t casiopeavk/dev-ops-lab3:1.0 .
```

## Run
```
docker run -p 80:80 --cpus=0.5 --memory=512m casiopeavk/dev-ops-lab3:1.0
```

## Login
```
docker login --username=casiopeavk
```

## Push
```
docker push casiopeavk/dev-ops-lab3:1.0
```