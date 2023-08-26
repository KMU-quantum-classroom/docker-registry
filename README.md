# docker-registry
docker-registry for our quantum-classroom

## Pull & Run

* qiskit-classroom-converter

```shell
docker pull ghcr.io/kmu-quantum-classroom/qiskit-classroom-converter
docker run -p 8888:8888 ghcr.io/kmu-quantum-classroom/qiskit-classroom-converter
```

## Local build

* qiskit-classroom-converter

```shell
docker compose -f qiskit-classroom-converter/docker-compose.yml up --build
```
