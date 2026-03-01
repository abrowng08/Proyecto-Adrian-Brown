# SOFT-11-C1-2026

# i. Implementación de sección de eventos para PONADIS

# ii. Convenciones de nomenclatura y formato de código

Se emplearán etiquetas como div que funcionarán como contenedores de varios elementos, como filas y columnas que a su vez tendrán botones, formularios, carruceles, imágenes, entre otras. El código se mostrará siguiendo la estructura lógica de HTML, por ejemplo:

``` html
<div class="row">
    <div class="col-1 caja morado"></div>
    <div class="col-11 caja verde"> </div>
</div>
```

# iii Estrategia de branches y commits 

Los mensajes de commit siguen la convención denominada Commits Convencionales, la cual se utiliza para standarizar el reporte de avances con una lectura sencilla y con sentido. Se realizarán siguiendo la estructura:

```
<tipo>(<alcance opcional>): <descripción breve> 
```
Los commits se realizarán cada vez que se emplee una función importante, como lo sería la implementación de una nueva funcionalidad, actualización visual, correción de bugs, etc., o al final de la jornada cuando no se vaya a trabajar más en el código por ese día.


# iv. Tipos de commit 

Para la realización de commits se especificará el avanze dependiendo del tipo de commit que sea. Para ello se utilizarán los siguientes tipos:

- new → cuando se crea un documento nuevo
- update → para realizar actualizaciones menores
- feat → nueva funcionalidad.
- fix → corrección de errores.
- docs → cambios en documentación.
- style → cambios de formato (espacios, indentación, comas).
- refactor → cambios internos que no afectan funcionalidad.
- test → cambios o adiciones en pruebas.
- chore → tareas de mantenimiento (dependencias, build, etc.).