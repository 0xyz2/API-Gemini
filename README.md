# Proyecto Gemini API – Desarrollo de aplicaciones con IA

Este proyecto demuestra la configuración de un entorno virtual en Python y una primera conexión exitosa con la API de **Google Gemini**, siguiendo los pasos del curso *Desarrollo de aplicaciones con IA*.

## 📁 Estructura del proyecto

```

gemini-api/
│
├── venv/                # Entorno virtual de Python
├── .env                 # Variables de entorno (API Key)
├── prueba_entorno.py    # Script de verificación del entorno
├── app_gemini.py        # Script de prueba con la API de Gemini
└── README.md            # Instrucciones del proyecto

```

## ⚙️ Requisitos previos

- Python 3.10 o superior  
- VS Code (recomendado)  
- Cuenta de Google con acceso a Google AI Studio  
- Una API Key de Gemini  

## 🚀 Pasos para ejecutar el proyecto

### 1️⃣ Clonar o crear el proyecto

Crea una carpeta llamada `gemini-api` y ábrela en VS Code:

```

Archivo → Abrir carpeta → gemini-api

````

### 2️⃣ Crear el entorno virtual

En la terminal integrada de VS Code:

**Windows**
```bash
python -m venv venv
````

**macOS / Linux**

```bash
python3 -m venv venv
```

### 3️⃣ Activar el entorno virtual

**Windows**

```bash
.\venv\Scripts\Activate
```

**macOS / Linux**

```bash
source venv/bin/activate
```

Si está activo, la terminal mostrará:

```bash
(venv)
```

### 4️⃣ Instalar dependencias

Con el entorno virtual activo, ejecuta:

```bash
pip install requests google-genai python-dotenv
```

### 5️⃣ Configurar variables de entorno

Crea un archivo llamado `.env` en la raíz del proyecto y agrega:

```env
GEMINI_API_KEY=TU_API_KEY_AQUI
```

⚠️ **No compartas esta clave ni la subas a repositorios públicos.**

## 🧪 Prueba del entorno virtual

Ejecuta el script de verificación:

```bash
python prueba_entorno.py
```

**Salida esperada:**

* Entorno virtual activo
* Ruta correcta de Python
* Conexión a internet exitosa

## 🤖 Prueba con la API de Gemini

Ejecuta el script principal:

```bash
python app_gemini.py
```

**Salida esperada:**

* Mensaje de conexión
* Respuesta generada por Gemini

## ❗ Posibles errores comunes

* **API Key no válida** → revisa el archivo `.env`
* **Módulo no encontrado** → asegúrate de que el `venv` esté activo
* **Modelo no disponible** → revisa el nombre del modelo en el código

## 📌 Notas finales

* Este proyecto es con fines educativos
* El código fue adaptado para evitar errores de sintaxis e indentación
* Se recomienda activar *Format on Save* en VS Code

## 🖼️ Evidencia de ejecución del script

![Evidencia de ejecución]**(images/evidencia.png**)

✅ Proyecto listo para ejecutarse y continuar con el curso




