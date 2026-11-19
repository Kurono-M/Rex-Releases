# Rex · Descargas y actualizaciones

Rex es un asistente de escritorio para Windows con mascotas virtuales, accesos rápidos, notas, capturas de imagen y video y música.

## Descargar Rex 0.9.1

- [Instalador para Windows x64](https://github.com/Kurono-M/Rex-Releases/releases/download/v0.9.1/Rex.0.9.1.exe)
- [Novedades e instrucciones](https://github.com/Kurono-M/Rex-Releases/releases/tag/v0.9.1)
- [Todas las versiones y paquetes](https://github.com/Kurono-M/Rex-Releases/releases)

Cerrá Rex desde el icono junto al reloj antes de instalar. Requiere Windows 10 (1809 o posterior) o Windows 11, Intel/AMD de 64 bits. El instalador incluye .NET. Los servicios musicales web necesitan Microsoft Edge WebView2 Runtime y dependen de las condiciones y compatibilidad del proveedor.

## Mascotas virtuales

T-Rex y T-Rexa 1.1.0 están incluidos en Rex 0.9.1. También se distribuyen como paquetes independientes:

- [T-Rex y T-Rexa 1.1.0](https://github.com/Kurono-M/Rex-Releases/releases/tag/mascotas-1.1.0): fotogramas musicales integrados y diseño propio de T-Rexa. Requieren Rex 0.9.1.
- [T-Rex Océano 1.0.0](https://github.com/Kurono-M/Rex-Releases/releases/tag/mascota-oceano-1.0.0): variante de color, compatible con Rex 0.9.0. No incluye los nuevos fotogramas musicales.

Importar los archivos `.rexpet` desde **Ajustes → Mascotas virtuales**.

## Canal de actualizaciones

Rex consulta `updates/stable.json` y `mascotas/catalog.json` en la rama `main`. Cada entrada incluye versión, novedades, URL de descarga, tamaño y SHA-256. La mascota avisa de las novedades; el usuario decide si instalar o continuar con su versión.

Las distribuciones no incluyen notas, capturas, claves de IA, archivos personales ni sesiones de otros usuarios. Las licencias se incluyen en el instalador. Este repositorio se destina a instaladores, mascotas, catálogos y novedades; las descargas automáticas «Source code» de GitHub corresponden al contenido de este repositorio.

SHA-256 de `Rex.0.9.1.exe`:

```
7747c58df51e7f6ff874abca1c64875b56fcc48a14bf221c3ce624a68a5d0012
```
