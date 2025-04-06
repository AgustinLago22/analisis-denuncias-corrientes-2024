# 📊 Análisis de Denuncias y Cámaras en Corrientes (2024)

**Autor:** Agustín Lago  
**Año:** 2024  
**Ubicación:** Ciudad de Corrientes, Argentina

---

## 🧠 Descripción del Proyecto

Este proyecto tiene como objetivo analizar la distribución de **denuncias ciudadanas** en distintos barrios de la ciudad de Corrientes durante el año 2024, y compararla con la cantidad de **cámaras de vigilancia** instaladas en cada zona. Se busca detectar patrones de inseguridad y zonas con posible desprotección por parte del sistema de monitoreo urbano.

El análisis se realiza sobre los datos públicos disponibles en el portal oficial de la Municipalidad de Corrientes, correspondientes a los primeros nueve meses del año (enero - septiembre 2024).

---

## 📁 Estructura de Archivos

- `Analisis_Denuncias_Camara.ipynb`: Notebook principal con el análisis completo.
- `csv/`: Carpeta que contiene los archivos `.csv` descargados desde el portal de datos.
  - `atencion_al_ciudadano_2024.csv`
  - `camaras_barrios.csv`

---

## 🌐 Fuentes de Datos

Los datasets provienen del sitio oficial de datos abiertos del gobierno:

- [Atención al Ciudadano 2024](https://datos.ciudaddecorrientes.gov.ar)
- [Listado de cámaras por barrio](https://datos.ciudaddecorrientes.gov.ar)

---

## 🛠️ Tecnologías Utilizadas

- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook
- Visual Studio Code

---

## 📊 Resultados Clave

- El barrio **Centro** presenta la **mayor cantidad de denuncias** (346) y también el **mayor número de cámaras** (23).
- El barrio **Concepción** muestra **150 denuncias** y **0 cámaras**, lo cual representa una **zona crítica de desprotección**.
- Muchos barrios tienen **baja cobertura de cámaras** a pesar de registrar múltiples denuncias.
- Las **horas pico de denuncias** se concentran durante la noche y madrugada, siendo **las 00:00 hs** el horario más crítico.
- **Junio** fue el mes con **más denuncias registradas** en lo que va del año.

---

## 🚧 Limitaciones

- El dataset de denuncias cubre solamente el período de **enero a septiembre de 2024**, por lo que los resultados podrían no representar el total anual.
- No se especifica el tipo de denuncia realizada, lo que impide un análisis más cualitativo del delito.
- La ubicación de las cámaras está asociada al **barrio**, no a coordenadas específicas, lo cual limita el análisis geoespacial.
- No se incluye información histórica para comparar tendencias de seguridad a lo largo de los años.

---

## 🔧 Cómo ejecutar este proyecto

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/tu_usuario/nombre_del_repositorio.git
   cd nombre_del_repositorio

   ```

2. **Crea y activa un entorno virtual**

   ```bash
   python -m venv .venv
   .venv\Scripts\activate # En Windows

   ```

3. **Instala las dependencias necesarias**

   ```bash
   .pip install pandas matplotlib

   ```

## 📄 Licencia

- Este proyecto está licenciado bajo la Licencia MIT, lo que significa que podés usar, modificar y distribuir el código libremente, siempre que mantengas el aviso de derechos de autor y la licencia.
