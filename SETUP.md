# 🛠️ Instalación y Configuración — IntegraFlow AI

Guía de configuración del ambiente de desarrollo para IntegraFlow AI.

## Requisitos previos

- **Git** 2.0 o superior
- **Node.js** 16.0+ y **npm** 7.0+ (para frontend)
- **Python** 3.8+ (para backend)
- **Visual Studio Code** recomendado

## Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/gmarin63/IntegraFlow-AI.git
cd IntegraFlow-AI
```

### 2. Configurar variables de entorno

Crear archivo `.env` en la raíz del proyecto:

```env
# Variables privadas — NO COMPARTIR
# Configurar según el ambiente de desarrollo
```

### 3. Frontend

```bash
cd frontend
npm install
npm start
```

### 4. Backend

```bash
cd backend
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py runserver
```

## Estructura del proyecto

- **`frontend/`** — Código de la interfaz de usuario
- **`backend/`** — Código de lógica de negocio y APIs
- **`docs/`** — Documentación técnica y funcional
- **`tests/`** — Casos de prueba y artefactos de validación
- **`assets/`** — Recursos (imágenes, logos, etc.)
- **`prototipos/`** — Prototipos de interfaz

## Desarrollo

### Crear rama de feature

```bash
git checkout -b feature/nombre-funcionalidad
```

### Realizar cambios y commit

```bash
git add .
git commit -m "Descripción clara del cambio"
```

### Crear Pull Request

Ver [CONTRIBUTING.md](CONTRIBUTING.md) para más detalles.

## Troubleshooting

### Port ya en uso

```bash
# Frontend (3000)
lsof -ti:3000 | xargs kill -9

# Backend (8000)
lsof -ti:8000 | xargs kill -9
```

### Limpiar dependencias

```bash
npm cache clean --force
pip cache purge
```

## Contacto

Para dudas o problemas, crear un Issue en GitHub.
