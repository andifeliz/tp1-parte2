## 💻 Instrucciones por sistema operativo

### 🔽 1. Clonar el repositorio

```bash
git clone https://github.com/andifeliz/tp1-parte2.git
cd tp1-parte2
```

### 🔽 2. Crear entorno virtual
✅ En Linux / macOS
```bash
python3 -m venv .venv
source .venv/bin/activate
```

✅ En Windows (CMD o PowerShell)
```bash
python -m venv .venv
.venv\Scripts\activate
```
### 🔽 3. Instalar las dependencias con pip
```bash
pip install -r requirements.txt
```

### 🔽 4. Registrar el entorno como kernel de Jupyter
```bash
pip install ipykernel
python -m ipykernel install --user --name ai-topicos --display-name "Python 3.12 (ai-topicos)"
```

### 🔽 5. Iniciar Jupyter Notebook
```bash
jupyter notebook
```