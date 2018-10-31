# Proyecto de Cloud Computing
### Autor: Felipe Peiró Garrido

---

## Título
Estación meteorológica local en Granada

## Descripción
El proyecto a desarrollar trata sobre un servicio por el cual se monitorizan sensores relativos a la climatología. Tiene como fin la realización de previsiones meteorológicas y el análisis del efecto invernadero en Granada, así como la medición de la calidad del aire en sensores repartidos por la capital. Cada día existen mayores normativas a cumplir para paliar el efecto invernadero, así como las referidas a la salud de los vecinos limitando la presencia de determinados gases en el aire. Este contará con las siguientes funcionalidades:

- **Panel de datos:** En este panel se muestran los distintos valores que están calculando los sensores en el momento actual.
- **Histórico de valores:** Aquí se puede echar un vistazo a los valores que ha ido tomando cada uno de los sensores.
- **Administración de los sensores:** En esta parte de la aplicación se permite añadir nuevos sensores, elegir su tipo y los valores que toma, asi como su eliminación o modificación.
- **Gestión de avisos:** Por último aquí se gestiona los avisos que debe mostrar un sistema cuando un determinado sensor alcanza un valor. De esta forma, por ejemplo, si un anemómetro capta ráfagas de viento de más de 130 km/h se lanzará un aviso en el sistema.

# Arquitectura
La realización de este proyecto se elaborará con Node.js utilizando el microframework Express.js. Con ellos se desarrollarán microservicios que usará el cliente de manera dinámica. Estos realizarán las siguientes funcionalidades:

- Conexión con la base de datos (MySQL).
- Identificación y registro.
- Visualización de gráficos.
- Visualización de sensores.
- Creación de sensores.
- Creación de alertas.

# Licencia
Este repositorio se encuentra bajo la GNU General Public License v3.0.