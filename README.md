# ms-untdf
Notas y trabajos prácticos de Modelos y Simulación 

## Instalación y ejecución
### 1. Crear el entorno virtual
Windows
```powershell
python -m venv venv
```

Linux/macOS
```bash
python3 -m venv venv
```

### 2. Activar el entorno virtual
Windows (CMD)
```cmd
venv\Scripts\activate
```

Windows (PowerShell)
```powershell
venv\Scripts\Activate.ps1
```

Linux/macOS
```bash
source venv/bin/activate
```

### 3. Instalar las dependencias

Con el entorno virtual activado:

```bash
pip install -r requirements.txt
```

### 4. Seleccionar el entorno virtual creado

```bash
python -m ipykernel install --user --name=mi_proyecto --display-name "Python (mi_proyecto)"
```

### 5. Iniciar Jupyter Notebook
```bash
jupyter notebook
```

Esto abrirá Jupyter Notebook en el navegador.
