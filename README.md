# Prueba Datos ChEMBL

Este proyecto es un ensayo académico que utiliza datos públicos de la base de datos **ChEMBL** - una base de datos de compuestos químicos y bioactividades de libre acceso.

## Contenido

- `data/` - Directorio para almacenar datos de ChEMBL
- `scripts/` - Scripts para descargar y procesar datos
- `analysis/` - Análisis y resultados

## Fuente de Datos

**ChEMBL**: https://www.ebi.ac.uk/chembl/

ChEMBL es una base de datos de libre acceso que contiene:
- Más de 2 millones de compuestos químicos
- Datos de bioactividad
- Información de proteínas objetivo
- Datos de ensayos biológicos

## Formas de Acceder a los Datos de ChEMBL

### 1. API REST de ChEMBL
- Documentación: https://chembl.gitbook.io/chembl-interface-documentation/web-services
- Permite consultas sin autenticación

### 2. Descargas Directas
- FTP: ftp://ftp.ebi.ac.uk/pub/databases/chembl/
- Formatos: MySQL, PostgreSQL, SQLite, CSV

### 3. Python Client
```bash
pip install chembl-webresource-client
```

## Licencia

Los datos de ChEMBL están disponibles bajo licencia CC0 (dominio público).

---

**Proyecto**: Ensayo Académico
**Autor**: Julianhh89
**Fecha**: 2026
