# 🎓 CRUD de Control de Estudiantes con Django + Scrum + XP + CI

---

## 📌 Descripción del Proyecto

Este es un mini proyecto integral donde desarrollamos una aplicación CRUD utilizando Django, con el objetivo de gestionar estudiantes. Aplicamos metodologías ágiles como **Scrum** y **Extreme Programming (XP)**, usamos **GitHub** para el control de versiones y colaboración, y configuramos **Integración Continua (CI)** con GitHub Actions para ejecutar pruebas automáticamente en cada push.

---

## 👥 Integrantes del equipo y roles Scrum

| Nombre               | Rol                                  |
|----------------------|---------------------------------------|
| **Jair Urbano**      | Scrum Master & Product Owner          |
| **Dayana Carrion**   | Developer Backend                     |
| **Diego Galiano**    | Developer Backend                     |
| **Fernando Tadeo**   | Developer Frontend                    |

---

## ⚙️ Requisitos del Proyecto

- Python 3.10
- Django 4.x
- Git
- pip
- trello https://trello.com/b/T5FTxlmD/contro-de-estudiantes

---

## 🚀 Instalación y Ejecución del Proyecto

```bash
# Clonar el repositorio
git clone https://github.com/usuario/proyecto-estudiantes.git
cd proyecto-estudiantes

# Crear entorno virtual
python -m venv env
source env/bin/activate        # En Windows: env\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt

# Aplicar migraciones
python manage.py makemigrations
python manage.py migrate

# Ejecutar servidor local
python manage.py runserver