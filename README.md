# AgroVista — GitHub Pages

Página estática para explorar imágenes aéreas agrícolas y calcular mapas de índice en el navegador.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub, por ejemplo `agrovista`.
2. Sube `index.html` a la raíz del repositorio.
3. Entra en **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que GitHub publique el sitio y abre la URL que muestre Pages.

## Uso
- **VARI:** carga una imagen RGB JPG/PNG.
- **NDVI:** carga la banda roja y la NIR, ambas como imágenes de escala de grises alineadas.
- **NDRE:** carga la banda red edge y la NIR, ambas como imágenes de escala de grises alineadas.
- El botón **Ver demostración** dibuja un mapa sintético para probar la interfaz.
- Puedes descargar el mapa como PNG y una ficha de análisis en TXT.

## Límites importantes
Esta herramienta es un prototipo educativo. No realiza calibración radiométrica ni corrección atmosférica, y no sustituye un flujo fotogramétrico o un diagnóstico agronómico. Las bandas deben estar alineadas y usar valores comparables. El promedio se calcula sobre los píxeles procesados, no representa directamente el estado de salud de todo el lote. Los datos de demostración son ficticios.
