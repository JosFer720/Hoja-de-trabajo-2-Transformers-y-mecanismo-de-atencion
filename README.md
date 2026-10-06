# Transformers y mecanismos de atención

Proyecto del curso CC3092 Deep Learning y Sistemas Inteligentes.

El notebook estudia la transición desde redes recurrentes hacia Transformers, implementa atención con PyTorch y analiza los pesos de atención de BERT y GPT-2.

## Contenido

- `Laboratorio_2_Transformers_y_Atencion.ipynb`: investigación, derivaciones, código, resultados y discusión
- `figuras`: mapas de calor y gráficas generadas por el notebook

## Requisitos

- Python 3.10 o superior
- PyTorch
- Transformers 4.56.2
- NumPy
- Matplotlib
- Seaborn
- Jupyter

Instalación sugerida:

```bash
python -m pip install torch transformers==4.56.2 numpy matplotlib seaborn jupyter
```

## Ejecución

Abra el notebook y ejecute las celdas en orden. La primera ejecución descarga `bert-base-uncased` y `gpt2`. Las gráficas se guardan automáticamente en `figuras`.

```bash
jupyter notebook Laboratorio_2_Transformers_y_Atencion.ipynb
```

El notebook selecciona GPU cuando está disponible y usa CPU en caso contrario.
