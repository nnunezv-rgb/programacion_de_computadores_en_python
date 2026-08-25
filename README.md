# 📚 Programación de Computadores en Python — 2026-I

Repositorio del curso **Programación de Computadores en Python (2026-I)**.  
Incluye **notebooks de Google Colab** y **material complementario** para la clase.

---

## 🔗 Repositorio principal

- URL: [https://github.com/dherreraal/PC_Python_2026I](https://github.com/dherreraal/PC_Python_2026I)
- Rama principal: `main`

---

## 🧭 Contenido

- 📓 **Notebooks en Google Colab** para prácticas y ejemplos.
- 📂 **Material de apoyo** para teoría y ejercicios.
- 📝 Recursos para la asignatura de **Programación de Computadores**.

---

## 🍴 Cómo hacer **fork**

1. Ingresa al repositorio principal:  
   👉 [https://github.com/dherreraal/PC_Python_2026I](https://github.com/dherreraal/PC_Python_2026I)  
2. Haz clic en **Fork** (arriba a la derecha).  
3. Selecciona tu cuenta de GitHub y confirma.  
4. (Opcional) Clona tu fork a tu PC:  
   ```bash
   git clone https://github.com/TU_USUARIO/PC_Python_2026I.git
   cd PC_Python_2026I
   ```

---

## 🔁 Cómo **actualizar tu fork**

### Desde la web (lo más fácil)

1. Ve a tu fork: `https://github.com/TU_USUARIO/PC_Python_2026I`.
2. Haz clic en **Sync fork** o **Fetch upstream**.
3. Pulsa **Update branch / Sync fork**.

### Con Git en tu PC (línea de comandos)

Configura el remoto `upstream` (solo la primera vez):
```bash
git remote add upstream https://github.com/dherreraal/PC_Python_2026I.git
git fetch upstream
```

Actualizar tu rama principal:
```bash
git checkout main
git merge upstream/main
git push origin main
```

---

## 🚀 Cómo **abrir los notebooks en Google Colab**

### Opción 1 — Botón “Abrir en Colab”

Ejemplo (ajusta según la ruta del notebook):

```markdown
[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/dherreraal/PC_Python_2026I/blob/main/notebooks/01_intro.ipynb)
```

> Reemplaza `notebooks/01_intro.ipynb` por la ruta exacta del archivo.

### Opción 2 — Desde la interfaz de Colab

1. Ve a 👉 [Google Colab](https://colab.research.google.com/).
2. Menú **Archivo → Abrir cuaderno**.
3. Pestaña **GitHub** → escribe `dherreraal/PC_Python_2026I`.
4. Selecciona el notebook que quieras abrir.

### Opción 3 — Enlace directo

Usa esta URL como plantilla:  

```
https://colab.research.google.com/github/dherreraal/PC_Python_2026I/blob/main/RUTA/AL/NOTEBOOK.ipynb
```

---

## 💾 Cómo **guardar tus cambios desde Colab a tu fork**

1. Abre el notebook desde tu fork.  
2. En Colab: **Archivo → Guardar una copia en GitHub…**  
3. Selecciona tu repositorio (tu fork) y la rama.  
4. Escribe un mensaje de commit y confirma.  

---

## 🌟 Cómo proponer cambios al repo principal (Pull Request)

1. Asegúrate de que tu fork esté **actualizado** (ver arriba).
2. Crea una nueva rama y guarda tus cambios:
   ```bash
   git checkout -b mi-cambio
   git push -u origin mi-cambio
   ```
3. En tu fork en GitHub, pulsa **Compare & pull request**.
4. Envía el PR hacia `dherreraal/PC_Python_2026I`.

---

## ❓ FAQ

- **¿Por qué no me aparece “Sync fork”?**  
  A veces está en la pestaña **Pull requests** de tu fork.  
- **Colab no me deja guardar en GitHub**  
  Asegúrate de estar logueado y de dar permisos a Colab.  
- **No encuentro el notebook en Colab**  
  Escribe `dherreraal/PC_Python_2026I` en la pestaña GitHub de Colab o usa el enlace directo.  

---

## 📄 Licencia

Este repositorio se comparte con fines académicos y de aprendizaje.  

---
