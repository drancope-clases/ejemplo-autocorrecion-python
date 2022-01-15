# Ejemplo de Autocorrección: Python
Este proyecto de ejemplo está escrito en Python, y su comprobación se realiza con pytest.

### La tarea
Las correcciones automáticas están fallando porque el *metodo* no da como resultado una *cadena* de texto (string) correcta. Cuando lo corrijas, los test se pondrán en verde.

### Instrucción de Setup
Usando Anaconda, desde un terminal, si no vemos (base) en la izquierda del *prompt*, escribir:
`conda activate`
Y después:
`conda install pytest`

Desde un terminal sin usar Anaconda:
`sudo -H pip3 install pytest`

### Run command
`pytest`

### Notas
- Quizás la ruta (path) de instalación de pip no esté incluida en la variable de entorno PATH por defecto. De ahí lo de usar `sudo -H` para que sea accesible.
