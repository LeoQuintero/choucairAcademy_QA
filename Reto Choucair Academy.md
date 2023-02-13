# Reto Choucair Academy

> Ejercicio práctico para Analista QA
📍 Se puede visualizar en formato MD o HTML
📎 link de pruebas :  [Choucair Academy](https://operacion.choucairtesting.com/academy/my/)
> 

### Tabla de Contenido

# 1. Historia de Usuario

| Clave | Consultar cursos existentes |
| --- | --- |
| Quien: | Analista de pruebas |
| Que: | pueda consultar los cursos existentes |
| Para que: | conocer el detalle del curso como la posibilidad de matricularme de acuerto a mis intereses |
| #Criterios | Condiciones Criterios de Aceptación |
| 1 | se debe proporcionar una lista de cursos acorde a la categoria seleccionada |
| 2 | visualizar contenido del curso mínimo nobre y profesor que lo imparte |
| 3  | la lista de cursos de verse por cuadricula de forma ordenada |
| 4 | debe ser responsive durante todo el proceso de busqueda permitidiendo visualizar la información desde dispositivos móviles |
| 5 | se debe proporcionar una ruta de navegacion que permita regresar a una pagina anterior, ejemplo: me encuentro en un curso y quiero regresar a la categoria |
| 6 | el buscador debe permitir busqueda por el texto ingresado, proporcionando la lista de cursos |

# 2. Plan de pruebas

## Información general

| Cliente | Choucair |
| --- | --- |
| Tipo de Proyecto | Nuevo |
| Triada | Responsable del Cliente |
| Lider de Pruebas (TPL) | Didier Gerardo |
| Responsable de Desarrollo | Pepito Dev |
| Linea de Negocio (UEN) | Enterprise |
| Nombre de la Aplicación o proyecto | Choucair Academy |

## Contexto

> Se realizaron unos cambios en la plataforma WEB que pudieran haber afectado en las funcionalidades de consulta, matrículas y realización de cursos. Las modificaciones realizadas no deberían de afectar su funcionalidad ya que fueron netamente de usabilidad y experiencia de usuario
> 

## Análisis de Riesgo

## Restricciones

|  | Descripcion | Fijo | Ajustable | Elegible |
| --- | --- | --- | --- | --- |
| Fechas: | Sprint 2 semanas |  |  | X |
| Alcance: | HU1. Consultar cursos existentes | X |  |  |
| Recursos | 3 analistas de prueba | X |  |  |

---

## Estrategia de Pruebas

| Estrategia de Pruebas | Responsable / como |
| --- | --- |
| Se realizaran pruebas de humo y pruebas exploratorias para evidenciar que el sistema cumple con las funciones básicas para empezar a ejecutar los casos de prueba. | Analista 1  |
| Se realizaran pruebas funcionales (Caja negra) y se visualizarn en url Git Hub | Analista 1 CP criterio 1 y 2
Analista 2 CP Criterio 4 y 4
Analista 3 CP Criterios 5 y 6 |
| Se realizara una priorización de HU según criticidad y se ejecutaran los casos de prueba de acuerdo a ello. | Prioridad criterios 1 y 2 enfocados en la funcionalidad de poder visualizar los cursos |
| Se realizara el seguimiento de errores/fallos/defectos se subiran al GitHub | Analista 1 |

---

## Alcance de las Pruebas

- se debe proporcionar una lista de cursos acorde a la categoria seleccionada
- visualizar contenido del curso mínimo nobre y profesor que lo imparte
- la lista de cursos de verse por cuadricula de forma ordenada
- debe ser responsive durante todo el proceso de busqueda permitidiendo visualizar la información desde dispositivos móviles
- se debe proporcionar una ruta de navegacion que permita regresar a una pagina anterior, ejemplo: me encuentro en un curso y quiero regresar a la categoria
- el buscador debe permitir busqueda por el texto ingresado, proporcionando la lista de cursos

### Fuera del Alcance de Pruebas

- La funcionalidad de Matricularse en nuevo curso
- La funcionlidad de Realizar el curso

---

## Criterios de Entrada / Supuestos:

- Ambiente de pruebas activo
- Navegadores (Monzilla V47 y Chrome 41.)
- Documentación completa
- Datos de prueba
- Insumos de pruebas (usuarios con credenciales de autenticación)
- Version a probar desplegada en el ambiente de pruebas

---

# 3. Ejecución Casos de Prueba

> **Funcionalidad: Consultar cursos existentes**
> ## URL EVIDENCAI CASOS DE PRUEBA: https://choucairtesting-my.sharepoint.com/:f:/r/personal/equinteroc_choucairtesting_com/Documents/CHOUCAIR/ChoucairAcademy/2023/reto-metodologia/choucairAcademy_QA/evidencias?csf=1&web=1&e=Ed2bqU

## Casos de prueba:

| ID CASO PRUEBA | HISTORIA USUARIO | Criterio o Escenario | Nombre Caso Prueba | Objetivo | Precondiciones | Pasos | Status | Responsable |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CP001 | Consultar cursos existentes | 1. se debe proporcionar una lista de cursos acorde a la categoria seleccionada | Validar que exista la opción de visualizar las categorías | Visualizar las categorias | - usuario contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. Verificar que se vean las categorias | En ejecución | Analista 1 |
| CP002 | Consultar cursos existentes | 1. se debe proporcionar una lista de cursos acorde a la categoria seleccionada | Validar que los cursos escuela técnica sean acorde a la categoría | los curso mostrados de la escuela técnica son acorde a la categoría | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. seleccionar categoría escuela técnica | Nuevo / pendiente | Analista 1 |
| CP003 | Consultar cursos existentes | 1. se debe proporcionar una lista de cursos acorde a la categoria seleccionada | Validar que los cursos escuela corporativa sean acorde a la categoría | los curso mostrados de la escuela coporativa son acorde a la categoría | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. seleccionar escuela corporativa | Nuevo / pendiente | Analista 1 |
| CP004 | Consultar cursos existentes | 2. visualizar contenido del curso mínimo nombre y profesor que lo imparte | Verificar contenido curso nombre profesor y nombre curso categoria escuela técnica | Se visuaizar el nombre curso y nombre profesor en los cursos de la categoria | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. seleccionar escuela corporativa | Nuevo / pendiente | Analista 1 |
| CP005 | Consultar cursos existentes | 2. visualizar contenido del curso mínimo nombre y profesor que lo imparte | Verificar contenido curso nombre profesor y nombre curso categoria escuela de gerencia | Se visuaizar el nombre curso y nombre profesor en los cursos de la categoria | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. seleccionar escuela corporativa | Nuevo / pendiente | Analista 1 |
| CP006 | Consultar cursos existentes | 3. la lista de cursos de verse por cuadricula de forma ordenada | Validar que la lista de cursos mantenga una estructura ordenada por cuadrícula | se visualizar de forma ordenada la lista de cursos manteniendo una estructura por cuadrícula | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. seleccionar escuela corporativa | Nuevo / pendiente | Analista 2 |
| CP007 | Consultar cursos existentes | 3. la lista de cursos de verse por cuadricula de forma ordenada | Validar que la lista de cursos mantenga una estructura ordenada por cuadrícula | se visualizar de forma ordenada la lista de cursos manteniendo una estructura por cuadrícula | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. seleccionar escuela corporativa | Nuevo / pendiente | Analista 2 |
| CP008 | Consultar cursos existentes | 4. debe ser responsive durante todo el proceso de busqueda permitidiendo visualizar la información desde dispositivos móviles | Validar visualización con mas dimensiones de un ¡Phone 12 Pro | se visualizar de forma ordenada la lista de cursos manteniendo una estructura ordenada | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. seleccionar escuela corporativa 4. seleccionar un curso | Nuevo / pendiente | Analista 2 |
| CP009 | Consultar cursos existentes | 5. se debe proporcionar una ruta de navegacion que permita regresar a una pagina anterior, ejemplo: me encuentro en un curso y quiero regresar a la categoria | Validar que se proporcione ruta navegación permitiendo a un estado anterior durante el proceso | permite regregresar a un estado anterior como categoria o pagina inicial | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. seleccionar escuela corporativa 4. seleccionar un curso 5. seleccionar en la ruta navegación pagina anterior categordía | Nuevo / pendiente | Analista 3 |
| CP010 | Consultar cursos existentes | 6. el buscador debe permitir busqueda por el texto ingresado, proporcionando la lista de cursos | Validar busqueda ingresando la palabra completa “Automatización” | permite visualizar cursos relacionados con la palabra ingresada | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. ingresar palabra en el inbox buscar curso | Nuevo / pendiente | Analista 3 |
| CP011 | Consultar cursos existentes | 6. el buscador debe permitir busqueda por el texto ingresado, proporcionando la lista de cursos | Validar caso no exitoso realizando la busqueda dejando vacio el inbox nombre curso | no permite visualizar ningun curso | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. ingresar palabra en el inbox buscar curso | Nuevo / pendiente | Analista 3 |
| CP011 | Consultar cursos existentes | 6. el buscador debe permitir busqueda por el texto ingresado, proporcionando la lista de cursos | Validar caso no exitoso realizando la busqueda con caracteres especiales el inbox nombre curso | no permite visualizar ningun curso | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. ingresar palabra en el inbox buscar curso | Nuevo / pendiente | Analista 3 |
| CP011 | Consultar cursos existentes | 6. el buscador debe permitir busqueda por el texto ingresado, proporcionando la lista de cursos | Validar busqueda curso ingresando parte del texto | permite visualizar cursos relacionados con parte del texto | - usuario - contraseña | 1. ingresar a Choucair Academy con usuario y contraseña 2. seleccionar botón tarjeta Universidad Chouicar 3. ingresar palabra en el inbox buscar curso | Fallido | Analista 3 |
