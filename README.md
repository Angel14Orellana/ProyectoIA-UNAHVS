# ProyectoFinal-IA

## Requisitos para correr correctamente

- Internet requerido
- Tener instalado python (versiones 3.7-3.10)
- Tener instalado git
- Eliminar limite de rutas de 260 caracteres (Windows) + R -> regedit -> y cambiar el valor de Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\FileSystem\LongPathsEnabled de 0 a 1

## Ejecutar en consola (Administrador) - Instalacion de dependencias

- curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py (Si no dispone de PIP, si tiene PIP Saltar)
- python get-pip.py (Si no dispone de PIP, si tiene PIP Saltar)
- pip install opencv-python
- pip install tensorflow
- pip install mediapipe
- pip install msvc-runtime
- pip install -U scikit-learn

## Correr el proyecto

- python app.py
