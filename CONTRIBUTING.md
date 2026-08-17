# 🤝 Guía de contribución — IntegraFlow AI

Esta guía describe el flujo general para contribuir a **IntegraFlow AI** sin asumir tecnologías que todavía no han sido seleccionadas.

## Principios de trabajo

- Mantener una comunicación respetuosa, clara y profesional.
- Evitar cambios no relacionados con el objetivo de cada tarea.
- Mantener la documentación alineada con el estado real del proyecto.

## Clonar el repositorio

```bash
git clone https://github.com/gmarin63/IntegraFlow-AI.git
cd IntegraFlow-AI
```

## Crear una rama

```bash
git checkout -b tipo/descripcion-corta
```

Nombres recomendados:

- `feature/nueva-funcionalidad`
- `fix/correccion`
- `docs/mejora-documentacion`
- `test/nuevos-casos-prueba`
- `refactor/reorganizacion`

## Antes de guardar cambios

Revisar el estado y las diferencias:

```bash
git status
git diff
```

## Crear un commit

```bash
git add .
git commit -m "tipo(alcance): descripción breve"
```

Tipos recomendados:

- `feat:` nueva funcionalidad.
- `fix:` corrección.
- `docs:` documentación.
- `test:` pruebas.
- `refactor:` reorganización.
- `chore:` mantenimiento.

## Enviar una rama

```bash
git push origin nombre-de-la-rama
```

Cuando corresponda, se puede abrir un Pull Request hacia `main`, describiendo los cambios realizados y su relación con el trabajo del proyecto.

## Estándares actuales

### Código

Los estándares específicos de formato, herramientas de análisis y pruebas se definirán cuando el proyecto seleccione formalmente su stack tecnológico.

Mientras tanto:

- Usar nombres descriptivos.
- Evitar duplicación innecesaria.
- Mantener funciones y componentes con responsabilidades claras.
- Documentar las decisiones técnicas relevantes.

### Documentación

- Mantener los archivos Markdown actualizados.
- Utilizar la estructura existente de `docs/`.
- Guardar las evidencias SENA relacionadas con el proyecto en `docs/evidencias-sena/`.
- Evitar crear carpetas duplicadas para el mismo propósito.

### Pruebas

Actualmente existen casos de prueba documentales en `tests/casos-prueba/`.

Las herramientas de pruebas automatizadas, comandos de ejecución y objetivos de cobertura se definirán cuando exista una implementación y un stack tecnológico seleccionado.

## Estado del documento

Esta guía evolucionará junto con IntegraFlow AI. Cuando se seleccione el stack tecnológico, se agregarán los estándares reales de desarrollo, ejecución y pruebas.
