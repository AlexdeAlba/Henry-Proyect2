
# Funciones importantes de inicio

## Entorno Virtual

### Creando un entorno virtual
```bash
virtualenv nombre_entorno
```
### Instalando un proyecto en un environment
```bash
pip install -r requirements.txt
```

### Algunos comandos de Virtualenv
| Comando | Descripción|
|---|---|
| `virtualenv nombre_entorno` | Crea un nuevo entorno virtual con el nombre especificado. |
| `source nombre_entorno/bin/activate` | Activa un entorno virtual en sistemas basados en Unix (Linux/macOS).|
| `nombre_entorno\Scripts\activate` | Activa un entorno virtual en sistemas Windows.|
| `deactivate` | Desactiva el entorno virtual actual y vuelve al entorno global del sistema. |
| `virtualenv -p ruta_a_python nombre_entorno` | Crea un entorno virtual utilizando una versión específica de Python. |
| `virtualenv --system-site-packages nombre_entorno` | Crea un entorno virtual que incluye las bibliotecas del sistema. |
| `pip install paquete` | Instala un paquete en el entorno virtual activo. |
| `pip freeze > requirements.txt` | Guarda una lista de paquetes instalados en un archivo `requirements.txt`. |
| `pip install -r requirements.txt` | Instala paquetes desde un archivo `requirements.txt` en el entorno virtual. |
| `virtualenv --help`   | Muestra la ayuda y la lista de opciones disponibles para `virtualenv`.    |

## Github
**Pasos para iniciar un nuevo repositorio:**
1. Navegar a la carpeta donde deseas iniciar el nuevo repositorio Git.
2. Ejecuta el siguiente comando para iniciar un nuevo repositorio Git:

```shell
git init
```
3. Agrega tus archivos al nuevo repositorio y realiza un commit inicial:

```shell
git add -A -f -- $(cat ProyectFiles.txt)
git commit -m "Primer commit"
```
4. Configurar el control remoto (si es necesario):
    * Si ya tienes un repositorio en GitHub y deseas asociar este repositorio local con él, puedes configurar el control remoto.

```shell
git remote add origin https://github.com/AlexdeAlba/proyecto-x.git
```
Asegúrate de reemplazar la URL con la URL de tu repositorio de GitHub.

5. Empujar los cambios (si es necesario):
    * Si ya tienes archivos en tu repositorio local y deseas enviarlos a GitHub, puedes hacerlo con el siguiente comando.

```shell
git push -u origin master
```
* Nuevamente, reemplaza "master" con el nombre de tu rama principal si es diferente.


### Comando para hacer un git add de todos los archivos
En el archivo ProyectFile.txt se encuentran los archivos que seran compartidos en el github.

```bash
#Archivo sin comentarios
git add -A -f -- $(cat ProyectFiles.txt)

# Para no incluir comentarios enmarcados con /*
Get-Content ProyectFiles.txt | Where-Object { $_ -notmatch '^\/\*' } | ForEach-Object { git add $_ }


git commit -m "Proyecto 1 Individual Henry"

git push
# o
git push -u origin main
```



## FastAPI

### Inicio de FastAPI
```bash
# Inicio Normal
uvicorn main:app --host 0.0.0.0 --port 8000

# Modo depuración
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```


## Definiciones importantes

### Diferencia entre KPI y Metrica

Los KPI (Key Performance Indicators) y las métricas son dos conceptos relacionados pero distintos en el ámbito empresarial. Aquí tienes una explicación de la diferencia entre ellos:

**1.  KPI (Key Performance Indicator):** Los KPI son indicadores clave de rendimiento que se utilizan para medir el progreso hacia los objetivos y metas de una organización. Son medidas cuantitativas que reflejan el desempeño de una empresa en áreas específicas y se seleccionan porque tienen una alta relevancia para el éxito del negocio. Los KPI son métricas que se consideran críticas y se utilizan para evaluar el rendimiento general de una empresa o departamento. Los KPI están vinculados directamente a los objetivos estratégicos y se utilizan para tomar decisiones y realizar mejoras en el desempeño.

Ejemplo: Si una empresa tiene como objetivo aumentar las ventas en un 10% en el próximo trimestre, un KPI relacionado podría ser el porcentaje de crecimiento de las ventas en ese periodo.

**2.  Métrica:** Las métricas son medidas cuantitativas o cualitativas que se utilizan para cuantificar o evaluar diferentes aspectos del desempeño de una empresa o proceso. Las métricas proporcionan información específica sobre una determinada actividad o área y se utilizan para realizar un seguimiento y una comparación en el tiempo. Las métricas pueden ser utilizadas para medir el rendimiento de un departamento, una campaña de marketing, un proceso de producción, entre otros.

Ejemplo: Si una empresa quiere medir el rendimiento de su sitio web, podría utilizar métricas como el tiempo promedio de carga de página, el número de visitantes únicos o la tasa de conversión.

En resumen, la principal diferencia entre un KPI y una métrica es que los KPI son indicadores clave de rendimiento que se utilizan para medir el progreso hacia los objetivos estratégicos, mientras que las métricas son medidas cuantitativas o cualitativas utilizadas para evaluar diferentes aspectos del desempeño sin necesariamente estar vinculadas a objetivos estratégicos específicos. Las métricas pueden ser utilizadas para calcular los KPI y proporcionar información más detallada para la toma de decisiones.

**Insights**: Se refiere a percepciones, comprensiones o entendimientos profundos y significativos que se obtienen a partir del análisis de datos o información. En el contexto de análisis de datos empresariales, un insight es una observación o conclusión que proporciona una nueva comprensión, revela patrones, tendencias o relaciones no evidentes a primera vista, y que puede ser útil para tomar decisiones informadas.

Los insights suelen surgir al examinar datos de manera más detallada, al identificar conexiones entre diferentes conjuntos de datos o al interpretar patrones que podrían no ser obvios inicialmente. Estos pueden ser cruciales para la toma de decisiones estratégicas, ya que ofrecen una visión más profunda de la situación o del rendimiento de una empresa.

Ejemplos de insights podrían ser:

1.  **Cambios estacionales en la demanda:** Observar que la demanda de servicios de Internet tiende a aumentar en ciertos trimestres del año, lo que podría influir en estrategias de marketing y recursos.
    
2.  **Correlación entre la velocidad de Internet y la satisfacción del cliente:** Descubrir que los clientes que tienen acceso a velocidades de Internet más altas tienden a estar más satisfechos, lo que podría indicar la importancia de mejorar la infraestructura de alta velocidad.
    
3.  **Impacto de la tecnología dominante en ingresos:** Notar que los ingresos generados por tecnologías específicas, como la fibra óptica, son significativamente mayores, lo que podría orientar la inversión y desarrollo en esa dirección.
    
4.  **Variación en la penetración del mercado por provincia:** Identificar que ciertas provincias muestran una mayor penetración del mercado, lo que podría influir en la expansión geográfica de la empresa.
    

En resumen, los insights son percepciones valiosas que se extraen a partir del análisis de datos, proporcionando una base más sólida para la toma de decisiones estratégicas en una organización.

