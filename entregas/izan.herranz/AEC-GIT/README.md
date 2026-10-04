# Entrega AEC-GIT - Izan Herranz

## 1. Fork del repositorio

Hago fork del repositorio para tener una copia propia en mi cuenta.

![Fork del repo](1.png)

## 2. Clonado en local

Una vez hecho el fork, cloné el repositorio en mi ordenador:

```bash
git clone https://github.com/izanherranz07/26-27-igps-git
```

![Clonar el repo](2.png)

## 3. Agregar carpetas

Creé la estructura `entregas/izan.herranz/AEC-GIT`.

![Carpetas](3.png)

## 4. Primer commit

Dentro de `AEC-GIT` creé un archivo de texto vacío, `README.txt`. Después lo añadí al área de staging, creé un commit y subí los cambios a mi fork:

```bash
git add .
git commit -m "docs: nuevo archivo"
git push origin main
```

![Commit y Push](4.png)


## 5. Rama docs/modificaciones

Creé una nueva rama y me cambié a ella:

```bash
git checkout -b docs/modificaciones
```

![Rama docs/modificaciones](5.png)
