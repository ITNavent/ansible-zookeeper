Este rol instala desde 1 a N nodos de zookeeper. 
Utiliza el ip de la red privada para conectarlos.

Y por default, busca el grupo "zookeeper" dentro de la metadata de OS.

Espero les sea útil.

Requerimientos:
```
- src: https://tecnologianavent:********@github.com/ITNavent/ansible-java.git
  version: check-java
  name: java

- src: https://tecnologianavent:********@github.com/ITNavent/ansible-navent-folders.git
  version: v1.0.0
  name: folders
```