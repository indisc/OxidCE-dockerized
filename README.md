## Oxid CE docker image

```
$ docker build -t opstack:OxidCE-docker .
```

### Starting this container
```
$ docker run -td -p 44:22 -p 80:80 opstack:OxidCE-docker
```

### Installing OXID

Open <http://localhost> in your browser and follow the installation steps. You
may use following values for the database:

| Field                   | Value          |
| ----------------------- | -------------- |
| Database hostname or IP | localhost      |
| Database name           | oxid_db        |
| Database username       | oxid_user      |
| Database password       | needstobefixed |
