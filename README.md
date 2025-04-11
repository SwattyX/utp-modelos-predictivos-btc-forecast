# Modelo Predictivo para el Pronóstico del Precio del Bitcoin

## Introducción

Desde sus inicios, Bitcoin ha sido una de las criptomonedas más conocidas del mundo. Su precio cambia mucho a corto plazo, lo que ha atraído el interés y el análisis de las personas tanto para invertir como entender su comportamiento. Muchas personas quieren encontrar formas de predecir su valor para tomar mejores decisiones.

El propósito de este trabajo es crear un modelo que pueda pronosticar el precio del Bitcoin utilizando datos históricos y herramientas como las series de tiempo y algunos métodos básicos de aprendizaje automático. Según los últimos años, cada vez son más las personas, empresas y gobiernos que invierten y utilizan el Bitcoin.

---

## Justificación

El uso de criptomonedas como Bitcoin en los últimos años ha crecido no solo entre los inversores sino también en las personas que buscan nuevas formas de manejar su dinero. Este crecimiento ha creado la necesidad de comprender mejor cómo se comporta el precio de Bitcoin, ya que su valor puede aumentar o bajar muy rápidamente.

Hacer un pronóstico de precios le permite conocer posibles escenarios futuros y prepararse para decisiones más seguras. Si bien no se puede saber exactamente qué sucederá, los modelos estadísticos pueden ofrecer una guía útil basada en datos reales.

---

## Antecedentes

### Origen y evolución del Bitcoin
Bitcoin fue creado por Satoshi Nakamoto, una persona o un equipo bajo seudónimo que describió la tecnología en un white paper titulado *Bitcoin: A Peer-to-Peer Electronic Cash System* en 2008. La primera transacción de Bitcoin tuvo lugar en enero de 2009. Desde entonces, la tecnología blockchain ha revolucionado las finanzas y ha dado origen a nuevos conceptos como DeFi (finanzas descentralizadas) y DEX (exchange descentralizado).


### Comportamiento del precio

A partir de 2011, algunas organizaciones comenzaron a aceptar donaciones en Bitcoin y comerciantes en línea empezaron a usarlo como medio de pago. Esto impulsó su adopción y su precio, pero también incrementó su volatilidad.

Por ejemplo:
- En diciembre de 2024, Bitcoin alcanzó un máximo histórico de ~$109,000.
- Para marzo de 2025, su valor cayó un 30%.
- En abril de 2025, noticias económicas provocaron una caída por debajo de los $82,000.

Estos cambios abruptos reflejan la influencia de factores como la oferta limitada, la confianza del mercado, la regulación y eventos macroeconómicos.


### Importancia

Bitcoin es una moneda digital sin restricciones físicas, que permite transferencias directas y seguras sin intermediarios.  
Algunas de sus ventajas clave:
- Bajas comisiones por transacción
- Protección de privacidad
- Operación 24/7 sin importar la ubicación
- No está sujeta a la inflación o control de gobiernos

Esto lo convierte en una alternativa atractiva para personas y empresas en entornos económicos inestables.

---

## Definición del problema

El principal problema del Bitcoin es su alta volatilidad, que dificulta su predicción tanto a corto como a largo plazo.

Esto presenta un reto para:
- Inversores
- Empresas
- Analistas financieros

El objetivo de este proyecto es desarrollar un modelo predictivo que, a partir de datos históricos, permita pronosticar el valor futuro del Bitcoin. Para ello, se exploran modelos estadísticos como ARIMA y otros modelos de series de tiempo.

---

## Conclusiones

Durante el desarrollo de este proyecto:
- Se analizó el comportamiento semanal del precio de Bitcoin desde 2020 hasta 2024.
- Se identificaron patrones estacionales y tendencias mediante técnicas como la descomposición estacional y pruebas de estacionariedad.
- Se compararon distintos modelos de predicción, y ARIMA fue el que presentó mejores resultados, aunque con márgenes de error considerables.

Este proyecto permitió:
- Entender mejor el modelado de series temporales
- Aplicar conocimientos teóricos a un caso real
- Identificar oportunidades de mejora para modelos futuros

Aunque el resultado no fue el esperado, la experiencia fue enriquecedora tanto a nivel técnico como analítico.

---

## Recomendaciones y futuros estudios

- Optimizar los hiperparámetros del modelo, especialmente los componentes estacionales en ARIMA.
- Incluir más variables explicativas, como noticias del mercado, eventos macroeconómicos o métricas sociales (sentiment analysis).
- Probar técnicas avanzadas como LSTM o Prophet de Facebook.
- Extender el análisis a otras criptomonedas para comparar patrones de comportamiento.

---

