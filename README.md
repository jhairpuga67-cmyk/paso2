# Piedra-Papel-o-Tijera: Proyecto Final

**Link al Video Explicativo:** https://drive.google.com/file/d/1b_I56653NYrUPZIIVz4_RnywusHh3Ln-/view?usp=sharing

---

## 1. Análisis y Posición del Estudiante (Fase 1)

### Posición del Estudiante
La posición adoptada es que el proyecto es una **síntesis algorítmica** de las reglas del juego. El objetivo principal fue modelar la **lógica de repetición** (el bucle `while True`), lo cual se demuestra en el código y se verifica en el **Diagrama de Flujo** inicial.

### Conclusiones y Logros Relacionados
El Diagrama de Flujo confirma la **destreza de ordenar por prioridades la evidencia**, ya que se priorizó la lógica de control del juego (la decisión de terminar o continuar) sobre la secuencia de acciones.

---

## 2. Competencias y Reflexión Técnica (Fase 1)

### Adquiriendo Competencias
Se usó Python. El código demuestra la competencia en el uso de **estructuras de control** (`if/elif/else`) y el **bucle de control** para gestionar las rondas de juego.

### Aceptando Contradicciones
El uso inicial del módulo `random` para la IA representa la **limitación (contradicción)** del diseño, ya que no ofrece un desafío estratégico real al jugador.

---

## 3. Avance Fase 2: Programación Orientada a Objetos (POO)

### Implementación de Clases
El código fue reestructurado para implementar **Programación Orientada a Objetos (POO)**. Se crearon dos clases principales, como se detalla en el **Diagrama de Clases UML** cargado en `Diagramas/`:
1.  **Clase `Jugador`:** Encapsula el nombre y la variable clave `puntaje`.
2.  **Clase `JuegoRPS`:** Actúa como controlador, manejando la lógica central y las interacciones entre los objetos `Jugador`.

### Puntuación y Modularidad
La aplicación de POO permitió agregar fácilmente la funcionalidad de **conteo de puntaje**. Gracias a la encapsulación, cada **objeto** (`jugador_humano` y `jugador_ia`) es responsable de gestionar su propia puntuación. Esto resulta en un código más modular, robusto y fácil de mantener.
