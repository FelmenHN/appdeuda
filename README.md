# Sistema de Carteras de Mora
### Municipalidad de San Pedro Sula · v1.0 · 2025

Sistema integral de procesamiento, normalización y visualización de carteras de morosidad tributaria.

## Inicio rápido

1. Copie los 7 archivos Excel a la carpeta `/datos/`
2. Doble clic en **MENU.bat**
3. Opción **1** → Instalar dependencias (primera vez)
4. Opción **2** → Procesar carteras y generar BD
5. Opción **7** → Abrir dashboard

## Estructura
```
CARTERA_MORA/
├── datos/              ← Archivos Excel de carteras
├── salida/             ← BD SQLite y logs generados
├── scripts/            ← Scripts Python ETL
├── sql/                ← Vistas SQL del dashboard
├── web/                ← Dashboard HTML5 publicable
├── MENU.bat            ← Menú principal ⭐
└── ejecutar.ps1        ← Lanzador PowerShell
```

## Carteras procesadas
- Bienes Inmuebles
- Servicios Públicos
- Contribución por Mejoras (CPM)
- Letras CPM
- Impuesto Personal
- Industria y Comercio
- Convenios GM (2015-2025)

## Manual completo
Abra `web/help.html` en su navegador o use la opción **9** del menú.

## Tecnologías
- **Python 3.x** + pandas, openpyxl
- **SQLite** con vistas optimizadas
- **HTML5** + JavaScript (sin backend)
- **GitHub Pages** para publicación web
