<!DOCTYPE html>
<html lang="es">
<body>
  <h1>🎯 Juego del Número Secreto</h1>
  <p>Un juego interactivo en JavaScript donde el usuario debe adivinar un número secreto generado aleatoriamente.
  Cada número solo puede ser sorteado una vez antes de reiniciar el ciclo completo, evitando repeticiones consecutivas.</p>

  <h2>📌 Descripción</h2>
  <p>Este proyecto fue desarrollado paso a paso siguiendo un enfoque progresivo:</p>

  <h3>Versión inicial</h3>
  <ul>
    <li>Generación aleatoria de un número secreto entre 1 y 10.</li>
    <li>Comparación del intento del usuario con el número secreto.</li>
    <li>Mensajes indicando si el número es mayor o menor.</li>
  </ul>

  <h3>Mejora de reinicio de juego</h3>
  <ul>
    <li>Se implementó la función <code>condicionesIniciales()</code> para establecer el estado inicial del juego.</li>
    <li>Se añadió el botón "Nuevo juego" que reinicia el juego sin recargar la página.</li>
  </ul>

  <h3>Control de repetición de números</h3>
  <ul>
    <li>Se creó la lista <code>listaNumerosSorteados</code> para almacenar los números ya usados.</li>
    <li>La función <code>generarNumeroSecreto()</code> ahora evita repetir números hasta que todos hayan sido sorteados.</li>
    <li>Cuando todos los números han sido sorteados, el juego muestra un mensaje indicando que no hay más números disponibles.</li>
  </ul>

  <h3>Parámetro dinámico de dificultad</h3>
  <ul>
    <li>Se implementó la variable <code>numeroMaximo</code> para definir el rango máximo del número secreto, facilitando cambios de dificultad.</li>
  </ul>

  <h2>🛠️ Tecnologías utilizadas</h2>
  <ul>
    <li>HTML5 — Estructura de la interfaz.</li>
    <li>CSS3 — (opcional para estilos) Estilizado y diseño responsivo.</li>
    <li>JavaScript (ES6) — Lógica del juego y manipulación del DOM.</li>
  </ul>

  <h2>🚀 Cómo jugar</h2>
  <ol>
    <li>Ingresa un número entre 1 y 10 en el campo de entrada.</li>
    <li>Presiona "Intentar" para verificar tu respuesta.</li>
    <li>Recibirás un mensaje indicando si el número secreto es mayor, menor o si acertaste.</li>
    <li>Cuando aciertes, presiona "Nuevo juego" para reiniciar.</li>
    <li>El número secreto no se repetirá hasta que todos los números posibles hayan sido usados.</li>
  </ol>

  <h2>📂 Estructura del proyecto</h2>
  <pre>
.
├── index.html      # Estructura del juego
├── style.css       # Estilos del juego (opcional)
├── app.js          # Lógica del juego en JavaScript
└── img/
    └── ia.png      # Imagen decorativa
  </pre>
  <h2>📄 Licencia</h2>
  <p>Este proyecto está basado en el curso "Lógica de Programación" de Alura Latam y forma parte del programa Oracle Next Education (ONE). 
Todo el contenido y el código original pertenecen a Alura, y este documento se ha creado únicamente con fines educativos como adaptación personal.</p>
</body>
</html>
