# Proyecto: Tap Boxing (Nombre Provisorio)

## 📌 Descripción general
Juego de boxeo para dispositivos móviles con jugabilidad inspirada en *Punch-Out!!*.  
El jugador controla a un boxeador que realiza golpes tocando la pantalla.  
Incluye mecánicas de **parry**, mejoras de personaje y desbloqueo de contenido mediante juego o microtransacciones.

---

##  Objetivos del prototipo (MVP)
- Golpe básico al tocar la pantalla (animación + daño).
- Un oponente básico que recibe daño y puede noquearse.
- Sistema de puntos/monedas por golpe acertado.
- Tienda básica para comprar una mejora (+daño o +velocidad).
- Mecánica de parry (bloqueo y contraataque con timing).
- Progresión infinita → siempre hay algo para mejorar.
- Sistema idle → aunque no juegues, progresás (en menor medida).
- Skins y upgrades como incentivo visual.
- Jefes y desafíos temporizados para romper la monotonía.
- Pantallas:
  - Menú principal
  - Combate
  - Tienda
---

Mecánicas principales
1. **Golpe por tap:** cada toque genera un golpe.
2. **Parry con timing:** si el jugador toca en el momento exacto de un ataque enemigo, hace un contraataque crítico.
3. **Sistema idle:** entrenadores que generan monedas o “condición física” mientras no jugás.
4. **Rivales con patrones:** cada uno con ataques y defensa distintos.
5. **Progresión infinita:** cada victoria sube de “rango” y desbloquea rivales más duros.
6. **Eventos y jefes temporizados:** peleas especiales con recompensas altas.
7. **Economía dual:** monedas (mejoras) y gemas (skins, personajes premium).
---

##  Economía y progresión
- **Monedas in-game:** ganadas al golpear o vencer rivales.
- **Entrenadores:** incrementan atributos del jugador.
- **Skins y personajes:**  
  - Gratis → jugando y acumulando monedas.
  - Pago → gacha o pase de batalla.

---

##  Estilo visual
- **Inspiración:** estética retro 2D (Punch-Out!!) con toques modernos.
- **Vista:** 2D frontal del oponente, HUD con vida y monedas.
- **Animaciones:** fluidas, exageradas para impacto visual.

---

##  Tecnologías y herramientas
- **Motor:** Unity (2D).
- **Lenguaje:** C#.
- **Repositorio:** GitHub.
- **Diseño de pantallas y diagramas:** Figma / Draw.io.
- **Control de versiones:** Git.

---

##  Plan de trabajo
### Semana 1-2: Preparación
- Definir mecánicas y flujo de juego (diagramas).
- Crear prototipo con golpe básico y detección de impacto.
- Implementar HUD simple (vida, monedas).

### Semana 3-4: Mecánicas avanzadas
- Agregar sistema de parry.
- Implementar tienda básica.
- Mejorar animaciones.

---

## 📝 Pendientes
- [ ] Motor de desarrollo: Unity
Descargar Unity Hub → gestor para instalar versiones de Unity, abrir proyectos y añadir módulos.
 Descargar Unity Hub

Instalar Unity LTS más reciente (Long Term Support, la más estable).

Al momento de instalar, marcar:

Build Support for Android (para exportar a celulares Android).

Build Support for iOS (solo si planean en el futuro probar en iPhone y tienen Mac).

Microsoft Visual Studio (opcional, pero recomendado para programar en C#).

- [ ] Editor de código
Aunque Unity trae Visual Studio, muchos devs prefieren Visual Studio Code por ser más liviano.
 Descargar VS Code

Instalar extensión C# Dev Kit para autocompletado y depuración.

- [ ] Control de versiones (Git)
Git instalado en tu PC → Descargar Git

Cuenta en GitHub (ya la tenés).

Instalar GitHub Desktop (más visual) o manejarlo desde terminal.

- [ ] Diseño gráfico y mockups
Al inicio no hace falta hacer arte definitivo, pero sí maquetas de pantallas:

Figma (gratis y online) → ideal para dibujar la UI y diagramas.
 Figma

Piskel (gratis) → para sprites 2D rápidos.
 Piskel

- [ ]Organización de ideas y tareas
Usar Trello o GitHub Projects para asignarse tareas y llevar el avance.

Columna Por hacer

Columna En progreso

Columna Hecho

- [ ]Assets iniciales (temporales)
Unity Asset Store → buscá “free 2D sprites” para usar como placeholder.

Esto permite probar mecánicas sin esperar a que el arte esté listo.

- [ ] Definir nombre final del juego.
- [ ] Diseñar personajes iniciales.
- [ ] Crear assets temporales para pruebas.
- [ ] Implementar sistema de guardado.
- [ ] Definir economía in-game (precios, recompensas).


---

## 👥 Equipo
- **Ezequiel Palladino: ** UI, arte, animaciones y diseño de niveles.
- **Uriel Sosa:** Programación principal, estructura del proyecto, monetización.

---

## 📂 Estructura de carpetas (propuesta)
