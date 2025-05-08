# 🎭 Automatización Sauce Demo con Playwright

## 📋 Descripción
Proyecto de automatización E2E para la aplicación Sauce Demo implementando:
- Page Object Model
- Fixtures para datos de prueba
- Reportes automáticos
- Múltiples flujos de prueba

## 🚀 Instalación
```bash
# Instalar dependencias
npm install

# Instalar navegadores
npx playwright install
```

## ⚡ Ejecución de Pruebas
```bash
# Ejecutar todas las pruebas
npx playwright test

# Ejecutar pruebas específicas
npx playwright test tests/loginrestrictions.spec.js --headed

# Ver reporte HTML
npx playwright show-report
```

## 📁 Estructura del Proyecto
```
├── fixtures/          # Datos de prueba
│   └── fixtures.js
├── pages/            # Page Objects
│   ├── LoginPage.js
│   └── StorePage.js
└── tests/            # Archivos de prueba
    ├── e2e.purchase.spec.js
    ├── login.spec.js
    └── loginrestrictions.spec.js
```

## 🧪 Casos de Prueba
- Login y validaciones
- Flujo de compra E2E
- Escenarios alternos
