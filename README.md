# ATLAS · TSP Genetic Telemetry

Aplicación estática del Problema del Vendedor Viajero. El algoritmo genético ahora corre en JavaScript directamente en el navegador, así que no requiere Flask, Python, Node ni un endpoint de servidor.

## Ejecutar localmente

Abre `index.html` en un navegador o sírvelo con VS Code Live Server. El botón **EJECUTAR SOLVER** optimiza la ruta en el navegador.

## Publicar en GitHub Pages

1. Sube el contenido de esta carpeta a la raíz de un repositorio de GitHub. Asegúrate de incluir el `index.html` de la raíz.
2. En GitHub abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**, elige la rama (por ejemplo `main`) y la carpeta **/(root)**; guarda.
4. Cuando termine la publicación, abre la URL de Pages que muestra GitHub.

## Características

- Presets de 20 y 30 ciudades, además de creación de nodos en el mapa.
- Matriz de costos dirigida, editable; importación y exportación JSON/CSV.
- Selección por torneo, cruce OX1, inversión de segmento y elitismo en JavaScript.
- Evolución visible por muestras, pausa/reanudación y curva de convergencia.
- Hasta 100 ciudades; población configurable entre 20 y 600 y hasta 3 000 generaciones desde la interfaz.

