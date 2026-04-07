# Matrices[README.md](https://github.com/user-attachments/files/26542130/README.md)
# 🧮 Matrices en PSeInt

<div align="center">

![PSeInt](https://img.shields.io/badge/PSeInt-2.0-blue?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0tMSAxNEg5VjhoMnY4em00IDBoLTJWOGgydjh6Ii8+PC9zdmc+)
![Algoritmos](https://img.shields.io/badge/Materia-Algoritmos%20y%20Programaci%C3%B3n-purple?style=for-the-badge)
![Tema](https://img.shields.io/badge/Tema-Matrices-orange?style=for-the-badge)
![Estado](https://img.shields.io/badge/Estado-Completado-success?style=for-the-badge)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green?style=for-the-badge)

</div>

---

## 📋 Descripción

Repositorio de ejercicios introductorios sobre **matrices** desarrollados en **PSeInt** como parte de la materia de *Algoritmos y Programación*. Se implementan las operaciones fundamentales: ingreso, visualización, suma, promedio, y búsqueda del mayor y menor elemento en una matriz de 3×3.

---

## 📁 Estructura del Proyecto

```
matrices-pseint/
│
├── 📄 matrices.psc          # Pseudocódigo principal en PSeInt
├── 📊 diagrama_flujo.png    # Diagrama de flujo del algoritmo
└── 📖 README.md             # Este archivo
```

---

## 🔍 ¿Qué hace el algoritmo?

El programa realiza las siguientes operaciones sobre una matriz de **3 × 3**:

| Paso | Operación | Descripción |
|------|-----------|-------------|
| 1️⃣ | **Ingreso** | Solicita los 9 elementos de la matriz al usuario |
| 2️⃣ | **Visualización** | Muestra la matriz en formato de tabla |
| 3️⃣ | **Suma** | Acumula la suma de todos los elementos |
| 4️⃣ | **Promedio** | Calcula el promedio general |
| 5️⃣ | **Mayor / Menor** | Encuentra el valor máximo y mínimo |

---

## 🗺️ Diagrama de Flujo

> El diagrama de flujo muestra la lógica del algoritmo con sus dos ciclos anidados (`Para i` y `Para j`) para recorrer filas y columnas.

![Diagrama de Flujo](diagrama_flujo.png)

---

## 💻 Pseudocódigo (fragmento principal)

```pseint
Algoritmo Matrices_Basico

    Definir M Como Real
    Dimension M[3, 3]
    Definir i, j, filas, columnas Como Entero
    Definir suma, promedio Como Real

    filas    <- 3
    columnas <- 3
    suma     <- 0

    // Ingreso de datos con ciclos anidados
    Para i <- 1 Hasta filas Con Paso 1 Hacer
        Para j <- 1 Hasta columnas Con Paso 1 Hacer
            Leer M[i, j]
        FinPara
    FinPara

    // Cálculo de suma
    Para i <- 1 Hasta filas Con Paso 1 Hacer
        Para j <- 1 Hasta columnas Con Paso 1 Hacer
            suma <- suma + M[i, j]
        FinPara
    FinPara

    promedio <- suma / (filas * columnas)
    Escribir "Suma: ", suma
    Escribir "Promedio: ", promedio

FinAlgoritmo
```

---

## 🚀 ¿Cómo ejecutarlo?

### Requisitos

- Tener instalado **PSeInt** → [Descargar aquí](http://pseint.sourceforge.net/)

### Pasos

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/matrices-pseint.git
   ```
2. Abre **PSeInt**.
3. Carga el archivo `matrices.psc` desde `Archivo → Abrir`.
4. Presiona **F9** o el botón ▶️ para ejecutar.
5. Ingresa los 9 valores numéricos que solicita el programa.

---

## 📚 Conceptos Clave

- **Matriz**: Estructura de datos bidimensional de filas × columnas.
- **Índices**: En PSeInt los índices comienzan en `1`.
- **Ciclos anidados**: Se usan dos `Para` (uno para filas, uno para columnas) para recorrer todos los elementos.
- **`Dimension`**: Palabra reservada de PSeInt para declarar arreglos y matrices.

---

## 🛠️ Herramientas Utilizadas

<div align="center">

| Herramienta | Uso |
|-------------|-----|
| ![PSeInt Badge](https://img.shields.io/badge/PSeInt-Pseudoc%C3%B3digo-blue?logo=none) | Escritura y ejecución del algoritmo |
| ![Draw.io Badge](https://img.shields.io/badge/Draw.io-Diagrama%20de%20Flujo-orange) | Diseño del diagrama de flujo |
| ![Git Badge](https://img.shields.io/badge/Git-Control%20de%20versiones-f05032?logo=git&logoColor=white) | Control de versiones |
| ![GitHub Badge](https://img.shields.io/badge/GitHub-Repositorio-181717?logo=github&logoColor=white) | Alojamiento del proyecto |

</div>

---

## 👤 Autor

**Salomon Lanziano Montoya**
- Materia: Algoritmos y Programación
- Institución: Unilasallista


---

## 📝 Licencia

Este proyecto está bajo la licencia **MIT** — úsalo libremente para aprender y enseñar.

---

<div align="center">
  <sub>Hecho con ❤️ para la clase de Algoritmos y Programación</sub>
</div>
