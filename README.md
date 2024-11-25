# Graficas_Lab3
## Laboratorio 3 de Gráficas por computadora
## Modelo 3D

---

## Demostración por Gif

![]([https://github.com/nel-eleven11/Graficas_Lab3/blob/main/lab3_gif_nel.gif]))

---

## Descripción 

Este proyecto es un renderizador básico de gráficos en 3D escrito en Rust. Está diseñado para renderizar objetos 3D en una ventana interactiva, utilizando transformaciones geométricas, un framebuffer y shaders personalizados.

---

## Características

- Renderizado de objetos 3D: Carga de modelos OBJ y renderizado de triángulos.
- Transformaciones geométricas: Incluye traslación, escalado y rotaciones 3D.
- Sombras básicas: Simula iluminación básica utilizando un vector de luz direccional.
- Interactividad: Control del modelo con el teclado para modificar la posición, escala y rotación en tiempo real.

---

## Requisitos/Dependencias

Antes de compilar y ejecutar el proyecto, asegúrate de tener las siguientes dependencias instaladas:

- Rust y Cargo: Para compilar y ejecutar el proyecto.
Crates:
- nalgebra-glm: Para manejar operaciones matemáticas en 3D.
- minifb: Para crear y gestionar ventanas gráficas.
- tobj: Para cargar modelos 3D en formato OBJ.

---

## Instalar/Compilar/Ejecutar

Clona el repositorio:
```bash
Copy code
git clone <https://github.com/nel-eleven11/Graficas_Lab3>
cd <Graficas_Lab3>
```

Asegúrate de tener un archivo OBJ en assets/models/. Por ejemplo:
```markdown
Copy code
assets/
└── models/
    └── ship6.obj
```

Compila y ejecuta el proyecto:

```bash
Copy code
cargo build --release
```
```bash
Copy code
cargo run --release
```
Controla el modelo con las siguientes teclas:

* Flechas: Mover el modelo en el espacio 2D.
* S/A: Escalar el modelo.
* Q/W/E/R/T/Y: Rotar el modelo en los ejes X, Y y Z.

---

## Licencia

Este proyecto es de código abierto bajo la Licencia MIT. Siéntete libre de usarlo, modificarlo y contribuir.

---
