# 🤝 Guía de Contribución — IntegraFlow AI

Gracias por tu interés en contribuir a IntegraFlow AI. Esta guía te ayudará a entender cómo participar en el proyecto.

## Código de conducta

- Sé respetuoso y constructivo.
- Mantén una comunicación clara y profesional.
- Respeta los derechos de autor y la propiedad intelectual.

## Cómo empezar

### 1. Fork el repositorio

Haz un fork del repositorio en GitHub.

### 2. Clonar tu fork

```bash
git clone https://github.com/tu-usuario/IntegraFlow-AI.git
cd IntegraFlow-AI
```

### 3. Crear una rama

```bash
git checkout -b feature/descripcion-corta
```

Nomenclatura recomendada:
- `feature/nueva-funcionalidad`
- `bugfix/descripcion-del-bug`
- `docs/mejora-documentacion`
- `test/nuevos-casos-prueba`

## Proceso de contribución

### 1. Realizar cambios

- Sigue los estándares de código del proyecto.
- Escribe código limpio, documentado y testeable.
- Actualiza la documentación si es necesario.

### 2. Commit y Push

```bash
git add .
git commit -m "Descripción clara: qué cambió y por qué"
git push origin feature/descripcion-corta
```

Formato recomendado de commit:

```
tipo(alcance): descripción breve

Descripción más detallada si es necesaria.

Relacionado con: #issue-number
```

Tipos:
- `feat:` Nueva funcionalidad
- `fix:` Corrección de bug
- `docs:` Cambios en documentación
- `test:` Nuevos tests
- `refactor:` Reorganización de código

### 3. Crear Pull Request

1. Ve a GitHub y abre un Pull Request desde tu rama.
2. Describe claramente qué cambios incluye.
3. Referencia el issue relacionado: `Cierra #123`
4. Espera revisión de los mantenedores.

### 4. Revisión y merge

Los mantenedores revisarán tu PR. Pueden solicitar cambios. Una vez aprobado, se hará merge a `main`.

## Estándares

### Código

- Código legible y bien documentado.
- Seguir convenciones del lenguaje (PEP8 para Python, prettier para JavaScript).
- Evitar código duplicado.

### Documentación

- Actualizar README.md si cambias funcionalidades.
- Agregar comentarios en código complejo.
- Incluir ejemplos de uso cuando sea relevante.

### Tests

- Agregar tests para nuevas funcionalidades.
- Asegurar que todos los tests pasen: `npm test` o `pytest`.
- Mantener cobertura de tests > 80%.

## Reportar bugs

1. Verifica que el bug no haya sido reportado.
2. Abre un Issue con:
   - Título descriptivo.
   - Descripción del problema.
   - Pasos para reproducir.
   - Resultado esperado vs resultado actual.
   - Entorno (SO, versiones).

## Sugerencias de mejora

Abre un Issue con la etiqueta `enhancement` describiendo tu idea.

## Preguntas

Usa las Discussions en GitHub o crea un Issue con la etiqueta `question`.

## Licencia

Al contribuir, aceptas que tu código se licencie bajo la misma licencia del proyecto.

---

¡Gracias por tu contribución! 🎉
