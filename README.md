
# 📈 Análisis de Evasión de Clientes (Churn) en una Empresa de Telecomunicaciones

Este proyecto tiene como objetivo identificar patrones en la evasión de clientes (churn) mediante análisis de datos, limpieza, visualización y generación de insights prácticos. Se desarrolla en un **cuaderno de Google Colab** que acompaña este repositorio.

---

## 📌 Objetivos

- Analizar los factores que influyen en la cancelación del servicio por parte de los clientes.
- Preparar los datos con un proceso completo de ETL (extracción, transformación y carga).
- Visualizar los datos para identificar patrones y posibles áreas de mejora.
- Proponer estrategias basadas en los hallazgos.

---

## 🧰 Herramientas Utilizadas

- Python 3.x
- Google Colab
- Pandas
- Matplotlib
- Seaborn

---

## 📂 Estructura del Proyecto

```bash
.
├── README.md              # Documento actual
├── telecom_churn.ipynb    # Cuaderno con análisis completo
├── data_telecom_x.csv     # Dataset base utilizado
├── visualizaciones/       # Carpeta con los gráficos generados (opcional)
```

---

## 🔎 Análisis Realizado

### ✅ Limpieza y Tratamiento de Datos
- Renombrado de columnas para mayor legibilidad
- Eliminación de valores nulos en campos clave
- Estandarización de valores categóricos (Yes/No a booleanos)
- Cálculo de facturación diaria (nueva columna `Cuentas_Diarias`)

### 📊 Análisis Exploratorio
- Distribución del churn general
- Churn desglosado por género
- Relación entre el churn y la antigüedad del cliente (`tenure`)
- Visualizaciones limpias y personalizadas con estilo unificado

### 🧠 Conclusiones
- Los clientes con menor tiempo de permanencia presentan mayor tasa de abandono
- No hay grandes diferencias entre géneros, aunque vale mantener seguimiento
- Se identificaron oportunidades para mejorar la retención en etapas tempranas

### 💡 Recomendaciones
- Programas de fidelización enfocados en los primeros 6-12 meses
- Monitoreo automático de señales de evasión
- Fortalecer la atención en servicios como soporte y streaming
- Campañas personalizadas basadas en métricas predictivas

---

## 📁 Cómo usar este repositorio

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   ```
2. Abre el archivo `telecom_churn.ipynb` con Google Colab o Jupyter.
3. Asegúrate de subir el archivo `data_telecom_x.csv` si trabajas localmente.
4. Ejecuta cada celda para replicar el análisis y visualizar los resultados.

---

## 🤝 Autor

**Paulosky 314**  
Diseñador gráfico y publicista enfocado en la visualización de datos e inteligencia de negocio.  
Colaboración con ChatGPT (Bonnot) para asistencias técnicas y estructurales.

---

## 📄 Licencia

Este proyecto está bajo licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.
