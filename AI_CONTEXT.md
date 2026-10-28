# Contexto del proyecto

> Última verificación: 2026-10-28

## 1. Propósito del proyecto
Aplicación React mínima para presentar el estado del espacio de trabajo.
Audiencia / uso: portal del equipo.

## 2. Stack tecnológico y arquitectura
Frontend: React 18.3.1 y React DOM 18.3.1.
Backend: servidor HTTP sencillo de Node.js para desarrollo.
Patrones clave: scripts ESM en `scripts/`; los assets se sirven desde `src/`.

## 3. Estructura del proyecto (mapeo)
`src/`: código y estilos de la aplicación.
`scripts/`: servidor de desarrollo, build, inventario y resolución de assets.
`docs/`: documentación generada del inventario del espacio de trabajo.
Nota para IA: no modificar proyectos vecinos del espacio de trabajo.

## 4. Comandos críticos
Inicialización: `npm install`
Desarrollo: `npm run dev`
Testing: N/A (no hay script de tests en `package.json`).
Lint / typecheck: N/A (no hay scripts configurados).
Deploy: N/A; requiere confirmación.

## 5. Reglas y convenciones estrictas
Estilo de código: JavaScript ESM.
Librerías permitidas / prohibidas: dependencias declaradas en `package.json`; no se observan restricciones adicionales.
Manejo de errores: el servidor responde 404 para rutas inexistentes.

## 6. Estado actual y registro de cambios
Completado: estructura React mínima y scripts de desarrollo/build existentes.
En progreso: N/A.
Problemas conocidos: no hay framework de tests, lint ni typecheck configurado.
