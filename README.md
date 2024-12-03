# FisiqAI Backend

## 🛠️ Instalación

> [!CAUTION]
> Como requisito se debe tener `python` y `pip` instalados.

- Clonar el proyecto
- Dentro del proyecto clonado abrir una terminal:

  1.  Instalar y cargar el entorno virtual para usar Python y otras dependencias.
      ```bash:
      pip install virtualenv
      python -m venv venv
      ```
  2.  Iniciar el entorno virtual, para el caso de Windows:
      ```bash:
      & ./venv/Scripts/Activate.ps1
      ```
  3.  Instalar las dependencias o librerias desde el archivo **"requirements.txt"**.
      ```bash:
      pip install -r ./requirements.txt
      ```
  4.  Iniciar el servidor.
      ```bash:
      uvicorn main:app --reload
      ```
      Normalmente se inicia en el puerto 8000, asi que vas a tu navegador y en la barra de direcciones debes colocar: **localhost:8000**
