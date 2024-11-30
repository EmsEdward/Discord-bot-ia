# Bot de Clasificación de Imágenes con Discord y Keras

Este proyecto es un bot para Discord que clasifica imágenes enviadas al servidor en diferentes categorías utilizando un modelo de aprendizaje automático entrenado en Keras.  

## Características
- **Comandos básicos**:
  - `$hello`: El bot responde con un mensaje de bienvenida.
  - `$heh <n>`: Envía un mensaje con "he" repetido `n` veces (por defecto 5).
- **Clasificación de imágenes**:
  - Comando `$check`: Permite analizar imágenes enviadas como adjuntos y las clasifica en categorías predefinidas como "Naturaleza", "Comida" o "Gaming".  

## Requisitos
### Librerías necesarias:
- Python 3.8 o superior.
- [discord.py](https://pypi.org/project/discord.py/) versión 2.0 o superior.
- [TensorFlow](https://pypi.org/project/tensorflow/) (para usar Keras).
- [Pillow](https://pypi.org/project/Pillow/) (para manejar imágenes).

Puedes instalar estas dependencias usando el siguiente comando:
```bash
pip install discord.py tensorflow pillow
