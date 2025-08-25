# Custom CodeCarbon

Variación de la librería **CodeCarbon** que registra las emisiones acumuladas en el tiempo en lugar de solo las finales.

Se agrega el atributo `csv_write_interval`, el cual indica cada cuantas mediciones de energía se registran los datos acumulados en el CSV. Por defecto viene con valor -1, caso en donde solo se registra las emisiones finales. Este atributo puede modificarse en la configuración de la librería.

## Instalación

```bash
pip install git+https://github.com/aplaza2/custom_codecarbon
```