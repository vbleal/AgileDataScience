# Metodologías de Gestión y Diseño de Proyectos Big Data


>💡 *Any Scrum without working product at the end of a Sprint, is a failed Scrum.*
―Jeff Sutherland, Scrum Co-Founder

## 📃 Descripción

Las autoridades de una Facultad desean obtener conocimiento a partir de los datos disponibles de los alumnos inscritos durante el ciclo lectivo 2020, siendo el reto principal poder predecir con un margen de confianza considerable la situación de los nuevos alumnos inscritos para el periodo 2022.

Para gestionar este proyecto, se ha tomado como base la ***Metodología CRISP-DM*** que consta de **6 fases**:

1)	Comprensión del Negocio
2)	Comprensión de los Datos
3)	Preparación de los Datos
4)	Modelado
5)	Evaluación
6)	Implementación

Adicionalmente, se han incorporado elementos característicos de la Metodología Ágil ***SCRUM***, mediante el uso de la tecnología ***Azure Boards***.

Las autoridades de una Facultad desean obtener conocimiento a partir de los datos disponibles de los alumnos inscritos durante el ciclo lectivo 2020, principalmente en lo que respecta a su situación como estudiante y su grado de avance en la carrera a la que se hayan inscrito. La situación de cada estudiante podrá ser:
- **Activo**: Continúa cursando la carrera.

- **Pasivo**: Ha abandonado los estudios o al menos no se ha reinscrito para continuar cursando en la actualidad.

El ***objetivo*** final que se persigue es el de poder predecir con un margen de confianza considerable la situación de los nuevos alumnos inscritos para el periodo 2022.

## 📑 Estructura de Ficheros

[ReadMe.txt](https://raw.githubusercontent.com/vbleal/13MBID/main/README.txt)

![](https://raw.githubusercontent.com/vbleal/13MBID/main/Imag/Estructura_Ficheros.jpg)





## 📲 Outputs


### Preparación de Datos

[datos_completos.csv](https://raw.githubusercontent.com/vbleal/13MBID/main/02_Outputs/datos_completos.csv)



### Modelado

#### Adaptación

[datos_completos_filtrados.csv](https://raw.githubusercontent.com/vbleal/13MBID/main/02_Outputs/datos_completos_filtrados.csv)

#### Construcción

[data_procesados.csv](https://raw.githubusercontent.com/vbleal/13MBID/main/02_Outputs/data_procesados.csv)

[data_dummies.csv](https://raw.githubusercontent.com/vbleal/13MBID/main/02_Outputs/data_dummies.csv)




### Despliegue

#### Adaptaciones

[nuevos_codif.csv](https://raw.githubusercontent.com/vbleal/13MBID/main/02_Outputs/nuevos_codif.csv)

[nuevos_codif_matched.csv](https://raw.githubusercontent.com/vbleal/13MBID/main/02_Outputs/nuevos_codif_matched.csv)

[data_despliegue.csv](https://raw.githubusercontent.com/vbleal/13MBID/main/02_Outputs/data_despliegue.csv)

[nuevos_codif_despiegue.csv](https://raw.githubusercontent.com/vbleal/13MBID/main/02_Outputs/nuevos_codif_despliegue.csv)


#### Predicciones

[datos_nuevos_calidad_rndf.csv](https://raw.githubusercontent.com/vbleal/13MBID/main/02_Outputs/datos_nuevos_calidad_rndf.csv)

[datos_nuevos_calidad_gbc.csv](https://raw.githubusercontent.com/vbleal/13MBID/main/02_Outputs/datos_nuevos_calidad_gbc.csv)

[datos_nuevos_calidad_mlp.csv](https://raw.githubusercontent.com/vbleal/13MBID/main/02_Outputs/datos_nuevos_calidad_mlp.csv)








