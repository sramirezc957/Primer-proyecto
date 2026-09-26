# Primer-proyecto
Repo de prueba de claude code

## Calculadora de IMC (`calculadora-imc.html`)

Página web simple, en un solo archivo HTML, para calcular el Índice de Masa Corporal (IMC).

### Qué hace

- Pide peso (kg), estatura (cm), edad y sexo.
- Al presionar **"Calcular mi IMC"**, calcula el IMC (`peso / estatura²`) y muestra:
  - El valor numérico del IMC.
  - La categoría correspondiente: bajo peso, peso normal, sobrepeso u obesidad.
  - Un breve comentario explicando qué significa ese resultado.
  - Dos recomendaciones de acción para el día de hoy, útiles especialmente si el resultado sugiere que conviene actuar pronto.
- Incluye un aviso de que la herramienta es informativa y no reemplaza una valoración médica profesional.

### Diseño

Interfaz oscura y minimalista pensada para verse profesional en escritorio y en móvil:

- Fondo `#0D0D0D`
- Acentos dorados `#C9A84C`
- Texto claro `#E8D5A0`
- Botón principal llamativo con degradado dorado y efecto hover/press.

### Uso

No requiere instalación ni backend: basta con abrir `calculadora-imc.html` en cualquier navegador.
