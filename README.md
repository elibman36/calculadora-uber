# calculadora-uber

Calculadora de cuánto gana por mes un chofer de Uber (valores en pesos argentinos).

Abrí `index.html` en el navegador: no necesita instalación.

## Cómo calcula

1. **Viajes por día** = horas activas × 60 × (1 − tiempo muerto) ÷ duración por viaje
2. **Ingreso bruto** = viajes por mes × precio por viaje
3. **Neto de Uber** = bruto × (1 − comisión)
4. **Costos** = vehículo (alquiler, o cuota + depreciación) + combustible (km ÷ consumo × precio) + seguro + mantenimiento + celular + monotributo
5. **Bolsillo neto** = neto de Uber − costos

Los valores por defecto son orientativos. Ajustalos con los sliders o escribiendo en las casillas (acepta `1.400.000` u `8,5`).
