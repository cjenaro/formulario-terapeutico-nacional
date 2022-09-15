# formulario-terapeutico-nacional
POC - Data del formulario terapéutico nacional de Argentina

# Objetivo del repositorio

El objectivo de este repositorio es centralizar la información del formulario terapéutico nacional en una única base de datos a ser consumida por una aplicación oficial del COMRA.

# Como agregar un nuevo medicamento?

Agregar el medicamento en `listado.json` de tal modo que la clave sea única, sin tildes e irrepetida, es decir

```json
  ...
  "medicamento-1": { ... },
  "medicamento-1": { ... }
  ...
```

no es válido, siendo la clave en este caso "medicamento-1".

Una vez agregada, deberá ser agregado un archivo dentro del directorio "detalles" con el nombre de la clave.
