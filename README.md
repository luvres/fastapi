## FastAPI with Python 3.11.3
### Image based entirely on "tiangolo" 
-----
			
#### Pull image
```
docker pull izone/fastapi:3.11-slim
```

#### Run
```
docker run --rm --name fastapi -p 8080:80 -ti izone/fastapi:3.11-slim
```

#### Access Browser
```
http://localhost:8080/
```

#### Build
```
docker build -t izone/fastapi .
```
```
docker build -t izone/fastapi:3.11-slim -f Dockerfile .
```

#### Push image
```
docker push izone/fastapi:3.11-slim
```

-----

### Stegastamp Tensorflow python 3.6
```
docker build -t izone/fastapi:tensorflow -f Dockerfile.tensorflow .
```
#### Run
```
docker run --rm --name fastapi -p 8080:80 -ti izone/fastapi:tensorflow
```
#### Access Browser
```
http://localhost:8080/
```

```
docker build -t izone/fastapi:datamachines -f Dockerfile.datamachines-cpu .

docker build -t izone/fastapi:datamachines-gpu -f Dockerfile.datamachines-gpu .
```



