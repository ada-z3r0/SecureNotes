# SecureNotes Parser

Herramienta experimental para el análisis de formatos de logs cifrados propietarios. Este script busca patrones de eventos de seguridad dentro de archivos de log sin necesidad de descifrarlos completamente.

## Estado del Proyecto

**ALPHA.** No usar en entornos de producción. 

## Uso

El parser actualmente solo soporta logs de `TIPO-3` y extrae timestamps y IDs de usuario.

```bash
python parser.py <archivo_log>.enc
