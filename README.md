# Práctica de Análisis de Situación Financiera

Herramienta web interactiva para practicar ejercicios de análisis financiero de corto y largo plazo. Genera estados contables aleatorios con el formato de la cátedra de Costos e Información Contable (ISCE / CaCEC).

**[Abrir herramienta](https://crissebastian.github.io/costos-practica/)**

---

## Qué hace

- Genera aleatoriamente un **Estado de Situación Patrimonial** completo (balance, estado de resultados, costo de ventas y notas)
- Incluye un **formulario de verificación** con 25 campos para practicar todos los indicadores:
  - Índices de liquidez (ILC, ILS)
  - Rotaciones (ABC, ACV, PCV, AP, PPC)
  - Ciclos operativos (COB, CON)
  - Capital de trabajo
  - PPPRAC y PPPEPC (tablas ponderadas)
  - Liquidez necesaria
  - Endeudamiento e inmovilización (IE, II, FI)
  - Rentabilidad (ROV, ROE, ROA, Du Pont)
- Validación automática con tilde verde / cruz roja
- Sistema de **seeds** para compartir ejercicios idénticos entre compañeros
- Botón de impresión optimizado para A4

## Cómo usar

1. Hacé clic en **Iniciar**
2. Revisá el estado contable generado y calculá los indicadores (en papel, Excel, calculadora)
3. Bajá al formulario de verificación con el menú lateral
4. Cargá tus resultados (4 decimales, acepta coma o punto)
5. Hacé clic en **Verificar**

Para compartir un ejercicio: copiá la **seed** del encabezado y pasásela a un compañero.

## Ejecutar localmente

Cero dependencias. Abrí `Herramienta Practica Costos/practica.html` en cualquier navegador.

## Tecnología

HTML + CSS + JavaScript vanilla. Sin frameworks, sin build, sin backend.
