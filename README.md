# Proyectos Finales SMALCAD25

Este será el repositorio donde estarán trabajando y deberán subir los avances de sus proyectos.

---

## Instrucciones iniciales

1. **Abrir una terminal nueva en VS Code.**

2. **Verificar si tienen Git instalado:**

   ```bash
   git --version
   ```

   Si todo está bien, verán algo como:
   ```
   git version 2.46.0
   ```

---

## Clonar el repositorio

Clonen el repositorio con el siguiente comando:

```bash
git clone https://github.com/mardischz/ProyectosFinalesSMALCAD25.git --recursive
```

El parámetro `--recursive` permite trabajar de forma más eficiente cuando hay submódulos o dependencias internas.

---

## Crear y cambiar a su branch

Creen una nueva rama (branch) con su nombre o con el nombre de su equipo:

```bash
git checkout -b nombre-del-equipo
```

Por ejemplo:

```bash
git checkout -b equipo-vision
```

Verán que ahora están trabajando dentro de su propia rama.

---

## Subir sus avances

Una vez que tengan cambios listos para subir:

1. Agreguen sus archivos o carpeta (si ya han estado trabajando en algún lugar aparte):

   ```bash
   git add .
   ```

2. Hagan el commit con un comentario claro:

   ```bash
   git commit -m "Agregando avances del proyecto"
   ```

3. Suban sus cambios a su rama en GitHub:

   ```bash
   git push
   ```

---

## Verificar el estado del repositorio

Para ver el estado de su trabajo:

```bash
git status
```

Si Git les indica que hay cambios que no han descargado, actualicen su repositorio con:

```bash
git fetch
git pull
git status
git push
```

---

## Notas finales

- Cada equipo o persona debe trabajar en su **propia rama**.  
- No suban directamente a la rama `main`.  
- Revisen con frecuencia el estado de su rama y actualícenla antes de subir cambios grandes.
