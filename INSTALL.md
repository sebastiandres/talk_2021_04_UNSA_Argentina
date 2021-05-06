## Instalación

Las librerías necesarias para ejecutar este jupyter notebook se encuentran en `requirements.txt`.

Usando conda (miniconda) puedes crear un nuevo ambiente con todas las librerías necesarias mediante

```bash
conda create --name sin-limites-con-python
conda activate sin-limites-con-python
pip install -r requirements.txt
```
Quizás sea necesario reemplazar `conda` por `source` al activar el ambiente.

Finalmente, lanzar jupyter notebook (no jupyter lab):

```bash
jupyter notebook
```

Desde jupyter notebook, abrir el archivo ipynb.


Nota a mí mismo:
* Para crear el archivo requirements.txt, se usa `pip list --format=freeze > requirements.txt``
* Para eliminar un ambiente, se usa `conda env remove -n sin-limites-con-python`
* Para ver la lista de ambientes, usar `conda info --envs.`
* El archivo rise.css tiene las propiedades de RISE. También hay definiciones en el "Notebook metadata".