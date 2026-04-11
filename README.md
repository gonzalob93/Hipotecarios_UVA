# Calculadora Hipotecaria UVA

Simulador de crédito hipotecario UVA desarrollado en HTML, CSS y JavaScript puro. Permite calcular el flujo de fondos completo en UVA, ARS y USD, con tabla de amortización y gráfico de composición de cuota.

## Demo

Abrí el archivo `calculadora-uva-v3.html` directamente en tu navegador, o publicalo en cualquier servicio de hosting estático.

## Funcionalidades

- Cálculo de cuota por sistema francés en UVA
- Flujo de fondos expresado en UVA, ARS y USD
- Tabla de amortización completa (hasta 360 cuotas)
- Gráfico de composición de cuota: capital, interés y seguro de incendio
- Parámetros configurables:
  - Valor del inmueble (USD)
  - TNA
  - Anticipo y gastos operativos (%)
  - Plazo en meses
  - Valor UVA y tipo de cambio USD/ARS
  - Primera vivienda (exento o grava IVA 21%)
  - Ajuste CVS (+1,5% mensual)
  - Relación cuota/ingreso → calcula ingresos netos mínimos
  - Seguro de incendio (% anual sobre valor del inmueble)

## Cómo usar

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/calculadora-uva.git
   ```
2. Abrí `calculadora-uva-v3.html` en tu navegador. No requiere servidor ni dependencias adicionales.

## Publicación

Podés publicar la calculadora de forma gratuita en:

- **Netlify Drop**: arrastrá el archivo en [netlify.com/drop](https://netlify.com/drop)
- **GitHub Pages**: activalo en Settings → Pages → Branch: main
- **Vercel**: importá el repositorio desde [vercel.com/new](https://vercel.com/new)

## Tecnologías

- HTML5 / CSS3 / JavaScript vanilla
- [Chart.js 4.4.1](https://www.chartjs.org/) para el gráfico de composición
- [DM Sans + DM Mono](https://fonts.google.com/) (Google Fonts)

## Origen

Basado en una planilla Excel de elaboración propia, convertida a aplicación web interactiva.

## Aviso

Los valores calculados son estimativos y no constituyen una oferta crediticia oficial.
