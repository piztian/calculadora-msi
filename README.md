# 💳 Calculadora MSI - Celucenter

Una calculadora web desarrollada para vendedores que permite estimar el total a cobrar a un cliente según la cantidad de meses sin intereses, tipo de tarjeta, institución financiera y operación (crédito, débito, AMEX, contado, etc.).

## 🧮 ¿Qué hace esta calculadora?

- Calcula el **costo real** de cobrar con Pinpeo a diferentes plazos.
- Compara tasas con **BBVA** cuando se selecciona su tarjeta.
- Permite cobrar también **de contado** aplicando la sobretasa correspondiente.
- Incluye opciones para:
  - Crédito y Débito (Pinpeo)
  - AMEX e Internacionales (Pinpeo)
  - Crédito BBVA (con advertencia)
- Agrega un **botón de copiar** para facilitar el envío del monto final.

## 📋 Tasa General Contado
| Tipo                   | Tasa |
|------------------------|------|
| Pinpeo Crédito         | 1.50% |
| Pinpeo Débito          | 1.50% |
| Pinpeo AMEX            | 3.50% |
| Pinpeo Internacional   | 3.50% |
| BBVA Crédito           | 1.50% |

## 🛠 Cómo usarla

1. Elige el tipo de operación (MSI o Contado).
2. Selecciona el tipo de tarjeta y el plazo (en meses o contado).
3. Ingresa el monto del producto.
4. Verás:
   - La tasa aplicada
   - La comisión en pesos
   - El total que deberías cobrar para cubrirla
5. Si eliges BBVA, verás un aviso para considerar cobrar con su propia terminal.

## 📦 Tecnologías utilizadas

- HTML
- CSS (vanilla)
- JavaScript (sin frameworks)

## 🌐 Uso en producción

Puedes acceder directamente a la calculadora en:  
👉 [https://piztian.github.io/calculadora-msi/](https://piztian.github.io/calculadora-msi/)

## 📌 Nota

Esta herramienta fue desarrollada como apoyo operativo para vendedores de Celucenter, con datos proporcionados por el área de finanzas y cobranza. No representa información oficial de las entidades financieras.
