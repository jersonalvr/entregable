# Sistema de Generación de Informes Pesqueros - PRODUCE Perú

## Contexto Institucional

Proyecto desarrollado para la **Oficina de Estudios Económicos (OEE)** del **Ministerio de la Producción de Perú**, en el marco del:

- **Programa Presupuestal 095**: "Fortalecimiento de la Pesca Artesanal"
- **Decreto Supremo N° 002-2017-PRODUCE**
- **Objetivo**: Fortalecer el Sistema de Información de Desembarque Artesanal

## Descripción

Esta aplicación web desarrollada con Streamlit permite generar informes detallados sobre desembarques pesqueros de manera automática. Utiliza inteligencia artificial, procesamiento de datos Excel y PDF para crear documentos profesionales que apoyan la toma de decisiones y el análisis en el sector pesquero.

## Objetivo Específico

Recopilar y supervisar información detallada sobre:

- Precios y volúmenes de recursos hidrobiológicos
- Desembarques en la zona de Santa, Áncash
- Periodo: Octubre y Noviembre de 2024

### Variables de Recolección

- Nombre común de especies
- Nombre científico
- Cantidad y volumen (Kg)
- Aparejo de pesca
- Procedencia
- Nombre de embarcación
- Número de matrícula
- Número de tripulantes
- Días y horas de faena
- Hora de descarga
- Tamaños
- Precios
- Destino

## Características Principales

### Funcionalidades

- Generación automática de informes pesqueros
- Extracción de datos desde archivos Excel y PDF
- Recomendaciones generadas por IA
- Procesamiento y análisis de datos de desembarque
- Generación de gráficos y tablas estadísticas
- Exportación a múltiples formatos (Word, PDF, Excel)

### Tecnologías Utilizadas

- **Python**
- **Streamlit**
- **Pandas**
- **API GPT-4**
- **pdfplumber**
- **python-docx**

## Metodología de Recolección

- Encuestas directas a:
  - Pescadores
  - Patrones
  - Armadores
  - Compradores
  - Administradores

### Requisitos Técnicos

- **Python 3.8+**
- **Bibliotecas**:
  - streamlit
  - pandas
  - python-docx
  - pdfplumber
  - openpyxl
  - requests

## Instalación

1. **Clonar el repositorio**

   ```bash
   git clone https://github.com/jersonalvr/entregable.git

2. **Crear entorno virtual**

   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   ```

3. **Instalar dependencias**

   ```bash
   pip install -r requirements.txt
   ```

4. **Configurar variables de entorno**

   Crear un archivo `.env` con tus credenciales de RapidAPI.

## Uso

Ejecuta la aplicación con el siguiente comando:

```bash
streamlit run app.py
```

## Estructura del Proyecto

- `app.py`: Aplicación principal de Streamlit
- `funciones_auxiliares.py`: Funciones de procesamiento de datos
- `Informe.docx`: Plantilla base para informes
- `requirements.txt`: Dependencias del proyecto

## Características Detalladas

### Generación de Informes

- Extracción automática de datos desde PDFs de términos de referencia
- Análisis de archivos Excel con datos de desembarque
- Generación de recomendaciones mediante IA

### Procesamiento de Datos

- Análisis de especies desembarcadas
- Cálculo de volúmenes y precios
- Generación de gráficos estadísticos

## Consideraciones Especiales

### Confidencialidad

- Uso exclusivo de información proporcionada
- No divulgación de datos
- Reserva absoluta de información

## Contribución al Sector

Generar información para:

- Mejora de productividad pesquera
- Toma de decisiones
- Desarrollo de políticas públicas
- Análisis de comercialización

## Contribuciones

Las contribuciones son bienvenidas. Por favor, lee las pautas de contribución antes de enviar un pull request.

## Licencia

[MIT]

## Contacto Oficial

[[Información de contacto del desarrollador](https://wa.me/+51961310789)]
