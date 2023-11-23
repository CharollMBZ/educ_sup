## Para ejecutar el siguiente comando debe tener la versión 3.12.0

## Paso:1 Redirigete a la carpeta del proyecto con CD, si está en MacOS debe usar "/"
 
## Paso 2: Cree el ambiente virtual
python -m venv myenv

## Paso 3: Activar el entorno virtual
myenv\Scripts\activate

### Observacion: si tiene problemas con activar el ambiente virtual,Abra PowerShell como administrador y ejecute este comando Set-ExecutionPolicy Bypass

## Observacion: si está en MacOS debe utilizar el siguiente comando para el 
source myenv/bin/activate

## Paso 4: Instalar las librerias del archivo requirements.txt
pip install -r requirements.txt

### Observacion: si está en MacOS y tiene problemas con la instalacion de las librerias de requirements debe ingresar como administrador con el comando sudo su (le pedirá la contraseña de su PC)

## Paso 5: ejecute el archivo python
python prueba.py