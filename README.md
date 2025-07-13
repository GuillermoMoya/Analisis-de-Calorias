# Calorie Calculator - Universidad Nacional

Este proyecto permite a los estudiantes y personal universitario subir imágenes de los alimentos servidos en la cafetería de la universidad para analizar de manera automática su balance nutricional y calidad, fomentando hábitos alimenticios saludables y mayor conciencia nutricional.

Utilizando tecnologías de visión por computadora, redes neuronales convolucionales y procesamiento de imágenes, la aplicación reconoce los alimentos presentes en las fotografías y proporciona estimaciones detalladas de su composición nutricional, incluyendo las calorías aproximadas de cada comida.

De esta forma, el proyecto no solo facilita el monitoreo individual de la calidad nutricional de los alimentos consumidos, sino que también apoya a la universidad en mantener un mejor control sobre la calidad y variedad de los alimentos ofrecidos en la cafetería.


## 🚀 Características

 Subida de imágenes de alimentos de forma sencilla y rápida.  
 Análisis nutricional mediante IA y visión por computadora.  
 Visualización clara de alimentos detectados y calorías aproximadas.  
 Herramienta gratuita para promover hábitos alimenticios saludables.

## ⚙️ Configuración inicial

Sigue estos pasos para obtener una copia local del proyecto y ejecutarlo para desarrollo o pruebas.

### 📄 Configuración de variables de entorno

Antes de ejecutar la aplicación, debes configurar las variables de entorno necesarias para el funcionamiento de la API de Google Gemini y Google Analytics.

**Crea un archivo `.env` en la raíz del proyecto con:**

```plaintext
NEXT_PUBLIC_GOOGLE_ANALYTICS_ID="tu_id_de_google_analytics"
NEXT_PUBLIC_GOOGLE_AI_API_KEY="tu_api_key_de_google_ai"
```

Reemplaza `"tu_id_de_google_analytics"` y `"tu_api_key_de_google_ai"` con tus valores reales.

## ▶️ Ejecución del proyecto

Instala las dependencias:

```bash
npm install
```

Ejecuta el servidor de desarrollo en local:

```bash
npm run dev
```

Abre tu navegador y navega a:

```
http://localhost:3000
```

Aquí podrás subir imágenes, analizar los alimentos detectados, y visualizar las calorías aproximadas de tu comida de forma clara y rápida.


### 🍎 Contribuye a una alimentación saludable en la universidad utilizando inteligencia artificial para analizar tus alimentos de forma sencilla y automatizada.
