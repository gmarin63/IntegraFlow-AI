# 🛠️ Instalación y configuración — IntegraFlow AI

Esta guía documenta la configuración básica disponible actualmente para trabajar con el repositorio de **IntegraFlow AI**.

> **Estado actual:** el stack tecnológico definitivo de frontend, backend y base de datos todavía no ha sido seleccionado. Por esta razón, no se incluyen comandos de instalación de frameworks o dependencias que aún no forman parte del proyecto.

## Requisitos actuales

- **Git** instalado.
- Una cuenta de **GitHub** con acceso al repositorio.
- Un editor de código, preferiblemente **Visual Studio Code** u otro equivalente.

## Clonar el repositorio

```bash
git clone https://github.com/gmarin63/IntegraFlow-AI.git
cd IntegraFlow-AI
```

## Verificar el estado del repositorio

```bash
git status
git branch --show-current
git remote -v
```

## Sincronizar cambios

Antes de empezar a trabajar, se recomienda verificar que no existan cambios locales pendientes y luego actualizar la rama correspondiente:

```bash
git pull origin main
```

## Estructura actual del proyecto

- **`frontend/`** — espacio reservado para la futura interfaz de usuario.
- **`backend/`** — espacio reservado para la futura lógica de negocio y API.
- **`docs/`** — documentación técnica, funcional y evidencias relacionadas con el proyecto.
- **`tests/`** — casos de prueba y futuros artefactos de validación automatizada.
- **`assets/`** — recursos gráficos del proyecto.
- **`prototipos/`** — prototipos de interfaz desarrollados durante el análisis y validación.

## Variables de entorno

El archivo `.gitignore` está configurado para excluir archivos `.env` del repositorio. Las variables de entorno se definirán cuando el stack tecnológico y las integraciones requieran su uso.

## Frontend

**Pendiente de definición técnica.**

No se debe ejecutar `npm install`, `npm start` u otros comandos hasta seleccionar y configurar formalmente la tecnología del frontend.

## Backend

**Pendiente de definición técnica.**

No se debe asumir Python, Node.js, Django, Express u otro framework hasta que la decisión técnica quede documentada en el proyecto.

## Base de datos

**Pendiente de definición técnica.**

El motor y el modelo físico de datos se seleccionarán durante las actividades de diseño correspondientes.

## Próximos pasos

1. Seleccionar el stack tecnológico.
2. Documentar las decisiones de arquitectura.
3. Configurar el ambiente de desarrollo.
4. Actualizar este archivo con los comandos reales de instalación y ejecución.

---

Este documento debe mantenerse alineado con el estado real del repositorio.