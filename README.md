# EP1 DLY0100 Deep Learning: MLP para el dataset Bank Marketing

Red neuronal multicapa (MLP) en TensorFlow/Keras que predice si un cliente contratará un depósito a plazo.

Autor: Oscar Flores

## Contenido

- `Evaluacion_MLP_Dataset_BankMarketing_resuelto.ipynb`: notebook completo con las salidas guardadas.
- `bank_marketing.csv`: datos entregados por el docente (45.211 filas, 17 columnas).
- `requirements.txt`: librerías necesarias.

## Cómo ejecutarlo

```bash
pip install -r requirements.txt
jupyter notebook Evaluacion_MLP_Dataset_BankMarketing_resuelto.ipynb
```

El CSV debe estar en la misma carpeta que el notebook. Ejecutar las celdas de arriba hacia abajo. El notebook completo tarda cerca de 10 minutos; el modelo base se entrena en unos 15 segundos.

## Resultados (conjunto de prueba)

| Modelo | Accuracy | Precision | Recall | F1 |
|---|---|---|---|---|
| Siempre no | 0,883 | 0,000 | 0,000 | 0,000 |
| Base | 0,894 | 0,603 | 0,277 | 0,380 |
| Final (L2) | 0,895 | 0,618 | 0,264 | 0,370 |
