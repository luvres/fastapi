## FastAPI with Python 3.10.2
### Image based entirely on "tiangolo" with the difference for python 3.9
-----
			
#### Pull image
```
docker pull izone/fastapi:3.10-slim
```

#### Run
```
docker run --rm --name fastapi -p 8080:80 -ti izone/fastapi
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
docker build -t izone/fastapi:3.10-slim .
```

