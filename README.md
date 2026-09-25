# Plataforma Web Colaborativa de Cálculo Integral
## Evaluación Parcial I - UTP 2026-II (CB215 Grupo 403)

![UTP Logo Badge](https://img.shields.io/badge/UTP-2026--II-orange?style=for-the-badge&logo=dragon)
![License](https://img.shields.io/badge/Licencia-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Estado-Fase_1_Completada-brightgreen?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/Despliegue-GitHub_Pages-blue?style=for-the-badge)

---

## 📌 Descripción del Proyecto

Este repositorio contiene la **Plataforma Web Colaborativa e Interactiva de Cálculo Integral**, desarrollada para la primera evaluación parcial de la asignatura **Matemáticas II (CB215 - Grupo 403)** del programa de Desarrollo de Software de la **Universidad Tecnológica de Pereira (UTP)** en modalidad 100% virtual (2026-II).

La plataforma combina el rigor matemático con una interfaz inspirada en el universo de **Dragon Ball Z y Arcade Retro (Pixel Art 8-Bit)**, permitiendo a los estudiantes visualizar, simular y ejercitar métodos numéricos e integrales definidas de manera gamificada.

---

## 🐉 Módulos Desarrollados (Fase 1 - Entregable 1)

| # | Módulo | Método / Tema | Personajes / Tema | Estado |
|---|---|---|---|---|
| **01** | `module-01-riemann.html` | Sumas de Riemann (Ln, Rn, Mn) | Senosama, Sheng Long, Wiz | ✅ Completado |
| **02** | `module-02-trapecio.html` | Regla del Trapecio | Cell, Freezer, Majin Buu | ✅ Completado |
| **03** | `module-03-punto-medio.html` | Regla del Punto Medio | Goku SSJ3, Vegeta God, Gohan Beast | ✅ Completado |
| **04** | `module-04-simpson.html` | Regla de Simpson (1/3) | Bardock, Broly SSJ, Janemba | ✅ Completado |
| **05** | `module-05-area.html` | Integral Definida y Área bajo la Curva | Trunks SSJ, Maestro Roshi, Piccolo | ✅ Completado |
| **06** | `module-06-volumen.html` | Volumen de Sólidos de Revolución (Discos/Arandelas) | Goku Ultra Instinct, Vegeta Ultra Ego, Jiren | ✅ Completado |
| **EXTRA** | `module-extra-dino.html` | Dino Prehistoric Runner Quiz (Trivias + Cámara Lenta) | Prehistoria Pixel Art / Cultura Matemática | ✅ Completado |

*Módulos 07 a 14 estructurados para las Fases 2 y 3 (Parciales II y III).*

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 Semantic**: Estructura modular e interactiva.
- **CSS3 Custom (Pixel Art 8-Bit)**: Diseñado sin librerías pesadas, utilizando sombras `box-shadow` cuadradas, fuentes tipográficas retro y paletas de colores estilo arcade.
- **JavaScript ES6+**: Algoritmos matemáticos numéricos para calcular sumatorio de Riemann, regla del trapecio, fórmula de Simpson 1/3, e integración definida exacta, además del motor gráfico 2D del minijuego.
- **Plotly.js (v2.24.1)**: Motor de renderizado vectorial de curvas f(x), rectángulos, trapecios y superficies 3D de sólidos de revolución.
- **Google Fonts**: Tipografías `'Press Start 2P'` y `'VT323'`.

---

## 📁 Estructura del Repositorio

```text
├── index.html                  # Página principal (Lobby DBZ 14 Módulos + Extra)
├── README.md                   # Documentación técnica y guía del proyecto
├── modules/
│   ├── module-01-riemann.html   # Módulo 1: Sumas de Riemann
│   ├── module-02-trapecio.html  # Módulo 2: Regla del Trapecio
│   ├── module-03-punto-medio.html # Módulo 3: Regla del Punto Medio
│   ├── module-04-simpson.html   # Módulo 4: Regla de Simpson
│   ├── module-05-area.html      # Módulo 5: Integral Definida y Área
│   ├── module-06-volumen.html   # Módulo 6: Volumen de Sólidos
│   └── module-extra-dino.html  # Módulo Extra: Dino Prehistoric Runner Quiz
```

---

## 🚀 Guía de Despliegue en GitHub Pages

1. **Clonar o subir el repositorio a GitHub**:
   ```bash
   git clone https://github.com/TU_USUARIO/calculo-integral-utp-2026.git
   cd calculo-integral-utp-2026
   ```

2. **Subir cambios a GitHub**:
   ```bash
   git add .
   git commit -m "Feat: Finalización de Fase 1 con index.html, README y 7 módulos"
   git push origin main
   ```

3. **Activar GitHub Pages**:
   - Ingresa al repositorio en GitHub.
   - Ve a **Settings** > **Pages**.
   - En **Source**, selecciona la rama `main` y la carpeta `/ (root)`.
   - Haz clic en **Save**.
   - Tu sitio estará disponible públicamente en: `https://TU_USUARIO.github.io/calculo-integral-utp-2026/`

---

## 📝 Componentes de Evaluación Parcial I (UTP)

1. **Plataforma Web Colaborativa (40%)**: Código fuente desplegado con simuladores interactivos, gráficos dinámicos y cuestionarios gamificados.
2. **Taller Manuscrito de 70 Ejercicios (50%)**: Taller resuelto a mano paso a paso con sustento matemático teórico y numérico.
3. **Sustentación en Video (10%)**: Explicación en video (5-10 minutos) demostrando el funcionamiento de la plataforma y la resolución de ejercicios clave.

---

*Desarrollado con pasión para la Universidad Tecnológica de Pereira (UTP) - 2026-II.*
