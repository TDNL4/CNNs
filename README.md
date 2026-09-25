#Evaluación Comparativa de Arquitecturas CNN en CIFAR-10
Este repositorio ya tiene el checkpoint 3 resuelto, donde se diseñaron y entrenaron varios
CNNs

##Recomendaciones:
Debido a que se usa una versión específica de TensorFlow, lo mejor es que se vayan a crear
un entorno Conda

```bash
# Crear entorno con Conda
conda create -n cnn_env python=3.11 -y
conda activate cnn_env

# Instalar dependencias
pip install -r requirements.txt

# Registrar kernel para Jupyter / VS Code
pip install ipykernel
python -m ipykernel install --user --name=cnn_env --display-name "Python (CNN Env)"
