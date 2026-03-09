# Mr. Tasty – Propuesta Kioscos de Autogestión

Presentación ejecutiva para la implementación de kioscos de autogestión en la cadena de hamburguesería **Mr. Tasty** (60 locales en Argentina).

## Contenido

### `presentacion.html`
Presentación HTML completa con animaciones, gráficos interactivos y prototipo funcional de kiosko.

**17 slides que cubren:**
- El desafío operativo actual
- Investigación sobre Tango Restó (API oficial)
- Arquitectura técnica completa
- Ticket fiscal y ARCA (3 opciones analizadas)
- Medios de pago: Mercado Pago QR, MODO, Payway/tarjeta
- Escáner de cupones estilo McDonald's
- Hardware desde Alibaba (proveedor y precios)
- Presupuesto detallado (~USD 300.000)
- ROI a 24 meses (breakeven ~mes 18)
- Cronograma de 6 meses
- Prototipo interactivo del kiosko

## Resumen Ejecutivo

| Ítem | Detalle |
|------|---------|
| Locales | 60 |
| Kioscos | 120 (2 por local) |
| Inversión única | ~USD 300.000 |
| Costo mensual | USD 16.800 |
| Breakeven | ~Mes 18 |
| Ticket promedio | +18% por upselling |

## Navegación de la Presentación

- **Flechas ↑↓** o **Espacio** para avanzar/retroceder
- **Dots** en el margen derecho para saltar a cualquier slide
- **Prototipo interactivo** en Slide 3: clickeable, simula el flujo completo de pedido

## Integración Técnica

### Tango Restó (hallazgo clave)
- NO tiene módulo nativo de kiosko
- SÍ tiene API oficial: `TangoSoftware/RestoAperturaComandasMostradorDelivery`
- Versión mínima requerida: T25 25.01.000.2377+

### Ticket Fiscal ARCA
- **Opción recomendada**: vía Tango Restó (complejidad BAJA)
- Tango ya está homologado por ARCA
- Impresoras compatibles: Hasar / Epson

### Medios de Pago
- Mercado Pago QR (integración nativa con Tango)
- MODO QR (vía middleware)
- Payway PINpad para tarjetas crédito/débito

## Fuentes

- [Tango Restó – Axoft](https://www.axoft.com/tango/software-para-gastronomia-restaurant/)
- [GitHub API Tango](https://github.com/TangoSoftware/RestoAperturaComandasMostradorDelivery)
- [ARCA Webservices](https://www.afip.gob.ar/ws/documentacion/ws-factura-electronica.asp)
- [Alibaba Kioscos 21.5"](https://www.alibaba.com/product-detail/21-5-inch-Interactive-Self-Service_11000000744643.html)
