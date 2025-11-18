# Cluster utilizando o Neo4J

## Instalação

- Clone o repositorio
```
    git clone git@github.com:phplemos/neo4j-sistemas-distribuido.git
    cd neo4j-sistemas-distribuido
```

- De permissao para o arquivo "neo4j.conf" dentro da pasta correspondente aos servers "conf/server*/neo4j.conf"
```
    chmod 640 neo4j.conf
```

- Suba o container 
```
    docker compose up -d
```
