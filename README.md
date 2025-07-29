 Gestor de Predios y Propietarios

Una aplicación web en FastAPI (con Jinja2) para gestionar **Predios**, **Propietarios** y subir/extraer datos de folios JSON de matrícula inmobiliaria.

---

## 📦 Contenido

- **app/** – código fuente  
  - **main.py** – punto de entrada de FastAPI  
  - **database.py** – configuración de SQLAlchemy + PostgreSQL  
  - **models.py**, **schemas.py**, **crud.py** – capa de datos y validaciones  
  - **views/** – routers y plantillas (Predios, Propietarios, Folios)  
  - **templates/** – Jinja2 HTML  
  - **static/** – CSS, imágenes (json-file.png, favicon.ico, style.css)  
- **folios/** – carpeta donde se guardan los JSON subidos  
- **requirements.txt** – dependencias de Python  
- **README.md** – esta documentación  

---

## 🚀 Requisitos

- Python 3.10+  
- PostgreSQL funcionando y accesible  
- Git  

---

## 🔧 Configuración

1. **Clona el repositorio**  
   ```bash
   git clone https://github.com/Kevz0n/gestor-predios.git
   cd gestor-predios
