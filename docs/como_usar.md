# Cómo usar las plantillas

Guía paso a paso para reutilizar las plantillas en un proyecto nuevo.

---

## Escenario 1: Empiezas un proyecto nuevo

1. **Crea el repositorio del proyecto** en GitHub.
2. **Abre el cuaderno de setup** desde `notebooks/00_setup_plantilla.ipynb`.
3. **Modifica la configuración** con los datos del nuevo proyecto.
4. **Ejecuta todas las celdas** de arriba a abajo.

---

## Escenario 2: Vuelves a un proyecto existente

1. **Abre el cuaderno de setup** en Colab.
2. **Ejecuta todas las celdas sin cambiar nada**.

---

## Escenario 3: Colab se reinicia mientras trabajas

Cuando Colab se reinicie:
- `!pwd` mostrará `/content` en lugar de tu repo.
- Los comandos `git` fallarán con `fatal: not a git repository`.
- **Solución:** vuelve a ejecutar el cuaderno de setup.

---

## Errores comunes

Consulta la sección "Solución de errores comunes" dentro del cuaderno de setup.

1. `fatal: not a git repository`
2. `fatal: destination path 'X' already exists`
3. `metadata-generation-failed` con pandas
4. `ERROR: pip's dependency resolver...` (aviso, no error)
5. `fatal: could not read Username/Password`
6. `No such file or directory: '/content/X'`
7. Carpetas anidadas (`X/X/X/`)

---

## Contacto

Repositorio mantenido por **AguCS231**.
