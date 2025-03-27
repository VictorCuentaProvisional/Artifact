# Test de GitHub Actions - Artefactos

Este proyecto es un test mínimo para verificar si la acción `upload-artifact` funciona correctamente
en un entorno limpio (ej. nueva cuenta de GitHub, nuevo repo, `ubuntu-latest`).

## Qué hace

1. Crea un archivo de texto (`saludo.txt`)
2. Lo sube como artefacto usando `actions/upload-artifact@v3`
