# Solicitud QA con evidencia

## FUENTE

REQ-R01
El formulario requiere: nombre completo, email, contraseña y edad. Todos los campos son obligatorios.

## OBJETIVO

Crear los casos de prueba a partir del requisito de la fuente.

## CONTEXTO

- Producto o funcionalidad: Academia online de cursos: https://playground.calidadsinhumo.com/login
- Usuario o rol: usuario de prueba (Email: ana.garcia@ejemplo.com Password: Segura2026!)
- Alcance incluido: Página de registro
- Fuera de alcance: Todas las otras páginas

## SALIDA

- Debe genera cada caso de prueba con base del STQB con un título, descripción, un paso por línea con su número de paso correspondiente, resultado esperado y precondiciones
- Tabla con formato de caso de prueba con base del STQB que incluya Fuente | Afirmación | Duda

## LÍMITES Y GATE

- No presentes como hecho nada que no aparezca en la FUENTE.
- Si algo no tiene respaldo en la FUENTE, escribe `SIN FUENTE` en esa celda. Es una respuesta válida.
- Si haces una inferencia, etiquétala como INFERENCIA.
- Indica qué parte de la FUENTE respalda cada resultado.
- Si un criterio define un límite numérico, diseña casos de valor límite; no repitas el criterio.
- No tomes decisiones de alcance por mí: propón y espera mi validación.