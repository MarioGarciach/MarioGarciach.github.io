# MarioGarciach.github.io
# 🌍 Terra Guardian - Planetary Defense

![Estado del Proyecto](https://img.shields.io/badge/Estado-En_Desarrollo-yellow)
![Lenguaje](https://img.shields.io/badge/JavaScript-ES6-blue)
![Motor](https://img.shields.io/badge/HTML5-Canvas-orange)

Un juego de estrategia tipo **Tower Defense** desarrollado completamente en Vanilla JavaScript, HTML5 y CSS3. El objetivo es proteger el planeta Tierra de oleadas infinitas de invasores alienígenas construyendo una red defensiva estratégica.

## 🎮 Características Principales

* **Defensa Planetaria:** La acción ocurre en 360 grados alrededor de la Tierra.
* **Sistema de Oleadas Infinito:** La dificultad escala progresivamente.
* **Jefes Finales:** Cada **10 niveles**, aparece un jefe con estadísticas mejoradas y habilidades especiales.
* **Arsenal Variado:** (En desarrollo) Sistema planeado de **20 armas únicas**.
* **Sistema de Tipos:** Las armas tienen bonificaciones de daño contra tipos específicos de enemigos (Ej: Fuego vs Hielo).
* **Motor Ligero:** Renderizado de alto rendimiento usando **HTML5 Canvas**, capaz de manejar cientos de proyectiles sin lag.

## 🛠️ Tecnologías Utilizadas

Este proyecto no utiliza librerías externas ni motores pesados. Todo está hecho desde cero ("from scratch") para maximizar el aprendizaje y el control sobre el código.

* **HTML5:** Estructura y contenedor Canvas.
* **CSS3:** Estilizado de la interfaz de usuario (UI) y menús.
* **JavaScript (ES6+):**
    * Lógica del Game Loop.
    * Programación Orientada a Objetos (Clases para Enemigos, Torres, Proyectiles).
    * Manejo de colisiones y matemáticas vectoriales.

## 🚀 Instalación y Uso

No necesitas instalar nada (como Node.js o Python) para jugar, ya que es una aplicación web estática.

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/tu-usuario/terra-guardian.git](https://github.com/tu-usuario/terra-guardian.git)
    ```
2.  **Abrir el juego:**
    * Navega a la carpeta del proyecto.
    * Haz doble clic en el archivo `index.html` para abrirlo en tu navegador favorito (Chrome, Firefox, Edge).

> **Nota:** Para una mejor experiencia de desarrollo, se recomienda usar una extensión como "Live Server" en VS Code.

## 🕹️ Cómo Jugar

1.  **Objetivo:** Evitar que la vida de la Tierra llegue a 0.
2.  **Economía:** Ganas **Oro** al eliminar enemigos.
3.  **Construcción:**
    * Selecciona un arma del menú inferior (haz clic en el botón del arma).
    * Haz clic en cualquier parte del espacio vacío para colocar la torre.
    * *No puedes construir encima de la Tierra ni sobre otras torres.*
4.  **Estrategia:** Presta atención a los diferentes tipos de enemigos y coloca las torres que tengan ventaja contra ellos.

## 🗺️ Roadmap (Próximos Pasos)

- [x] Motor básico y bucle de juego.
- [x] Sistema de construcción (Drag & Click).
- [x] Generación de enemigos y Jefes cada 10 niveles.
- [ ] Implementar las 20 armas con sus estadísticas únicas.
- [ ] Agregar efectos visuales (partículas al explotar).
- [ ] Sistema de guardado local (LocalStorage) para no perder el progreso.
- [ ] Menú de inicio y "Game Over" pantalla.

## 🤝 Contribución

Las contribuciones son bienvenidas. Si tienes ideas para nuevos tipos de armas o enemigos:

1.  Haz un Fork del proyecto.
2.  Crea una rama (`git checkout -b feature/NuevaArma`).
3.  Haz Commit de tus cambios (`git commit -m 'Agregada arma de Hielo'`).
4.  Haz Push a la rama (`git push origin feature/NuevaArma`).
5.  Abre un Pull Request.

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

---
*Desarrollado con ❤️ y mucho Café.*
