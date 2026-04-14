# Prueba Lectiva

Base SvelteKit con arquitectura `feature-first/domain-first` para integrar la API de Rick and Morty.

## Run

```bash
npm install
npm run dev
```

## Check

```bash
npm run check
npm run build
```

## Deploy

El proyecto queda preparado para CI/CD con GitHub Actions y despliegue automatico en GitHub Pages al hacer push a `main`.

Antes de usarlo en GitHub, activa en el repositorio:

```text
Settings > Pages > Build and deployment > Source: GitHub Actions
```

## Estructura

- `src/lib/core`: cliente HTTP, configuracion y adaptadores.
- `src/lib/entities`: tipos y mapeos de dominio.
- `src/lib/features`: features por caso de uso.
- `src/routes`: composicion de rutas y carga de datos.
