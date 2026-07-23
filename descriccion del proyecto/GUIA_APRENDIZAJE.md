# GUÍA DE APRENDIZAJE COMPLETA
## Instructor: AI · 22 Clases · De cero a proyecto web profesional

---

## PROGRESO GENERAL

| HTML | CSS | JavaScript | JSON | Python | Flask | Java (visión) | Git |
|------|-----|-----------|------|--------|-------|---------------|-----|
| 75%  | 25% | 10%       | 0%   | 0%     | 0%    | 0%            | 0%  |

---

## CLASE 1 — Cómo funciona la web
**Progreso:** ☐ No iniciada

**Conceptos:**
- ¿Qué es internet? Red de computadoras conectadas
- Cliente vs Servidor: quién pide y quién entrega
- El navegador: tu puerta a la web
- URL: partes de una dirección web (protocolo, dominio, ruta)
- HTTP/HTTPS: el idioma en que se comunican cliente y servidor
- Petición GET (pedir) vs POST (enviar)
- Códigos de estado: 200 OK, 404 No encontrado, 500 Error del servidor
- HTML, CSS, JS: qué hace cada uno en una página
- DNS: cómo se traduce google.com a una dirección IP
- Hosting: dónde viven los archivos de una web

---

## CLASE 2 — HTML esencial
**Progreso:** ☐ Completada (visto en clase anterior)

**Conceptos:**
- Estructura base: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`
- Etiquetas de texto: `<h1>`-`<h6>`, `<p>`, `<strong>`, `<em>`, `<br>`
- Listas: `<ul>` (desordenada), `<ol>` (ordenada), `<li>`
- Enlaces: `<a href="">` con atributos target, title
- Imágenes: `<img src="" alt="">` con atributos
- Div: contenedor genérico
- Meta tags: charset, viewport, description
- Comentarios en HTML: `<!-- -->`
- Atributos globales: id, class, style

---

## CLASE 3 — HTML semántico
**Progreso:** ☐ No iniciada

**Conceptos:**
- `<header>`: cabecera del sitio o sección
- `<nav>`: navegación principal
- `<main>`: contenido único por página
- `<section>`: agrupación temática
- `<article>`: contenido independiente
- `<aside>`: contenido complementario
- `<footer>`: pie de página
- `<figure>` y `<figcaption>`: imágenes con leyenda
- Diferencias con `<div>`: cuándo usar cada uno
- Beneficios: SEO, accesibilidad, mantenibilidad

---

## CLASE 4 — CSS desde cero
**Progreso:** ☐ No iniciada

**Conceptos:**
- Formas de aplicar CSS: inline, interno (<style>), externo (.css)
- Selectores: de etiqueta, de clase (.clase), de id (#id)
- Selectores avanzados: descendente, hijo directo >, hermano ~
- Colores: hexadecimal (#ff0000), rgb(), rgba(), nombres
- Fuentes: font-family, font-size, font-weight, font-style
- Texto: text-align, text-decoration, line-height, letter-spacing
- Unidades: px, %, em, rem, vw, vh
- Herencia y cascada: qué gana cuando hay conflictos
- Especificidad: cómo calcular quién gana

---

## CLASE 5 — CSS: Modelo de caja (Box Model)
**Progreso:** ☐ No iniciada

**Conceptos:**
- Toda etiqueta es una caja
- Content: el contenido real
- Padding: espacio interno (relleno)
- Border: el borde visible
- Margin: espacio externo (separación)
- box-sizing: content-box vs border-box
- width y height: cómo se calculan
- Display: block, inline, inline-block, none
- Overflow: visible, hidden, scroll, auto
- Colapso de márgenes: cuándo ocurre

---

## CLASE 6 — CSS: Flexbox
**Progreso:** ☐ No iniciada

**Conceptos:**
- display: flex — activa flexbox en un contenedor
- Eje principal y eje cruzado (main axis / cross axis)
- flex-direction: row, column, row-reverse, column-reverse
- justify-content: alineación en eje principal
- align-items: alineación en eje cruzado
- flex-wrap: nowrap, wrap, wrap-reverse
- gap: espacio entre items
- flex: shorthand para grow, shrink, basis
- align-self: alinear un item individual
- Casos prácticos: centrar un div, navbar, tarjetas

---

## CLASE 7 — CSS: Grid
**Progreso:** ☐ No iniciada

**Conceptos:**
- display: grid — activa CSS Grid
- grid-template-columns: definir columnas
- grid-template-rows: definir filas
- fr: unidad fraccionaria (1fr, 2fr)
- gap: separación entre celdas
- grid-column y grid-row: posicionar items
- grid-template-areas: nombrar áreas
- minmax(): tamaño mínimo y máximo
- auto-fit y auto-fill: grids responsivos
- Flexbox vs Grid: cuándo usar cada uno

---

## CLASE 8 — CSS: Responsive Design
**Progreso:** ☐ No iniciada

**Conceptos:**
- ¿Qué es responsive? Adaptarse a cualquier pantalla
- Viewport meta tag: cómo configurarlo
- Media queries: @media (max-width: 768px)
- Mobile first: diseñar primero para celular
- Breakpoints comunes: 480px, 768px, 1024px, 1440px
- Unidades relativas: %, em, rem, vw, vh
- max-width y min-width: límites responsivos
- Imágenes responsivas: max-width: 100%
- Menú hamburguesa: cómo funciona
- Pruebas: Chrome DevTools modo responsive

---

## CLASE 9 — JavaScript 1: Fundamentos
**Progreso:** ☐ No iniciada

**Conceptos:**
- ¿Qué es JS? Lenguaje que corre en el navegador
- Cómo incluir JS: <script> interno/externo
- console.log(): tu mejor amigo para depurar
- Variables: var, let, const — diferencias
- Tipos de datos: string, number, boolean, null, undefined
- typeof: preguntar el tipo de algo
- Operadores: +, -, *, /, %, **
- Template strings: `Hola ${nombre}`
- prompt() y alert(): entrada y salida básica
- Comentarios: // y /* */

---

## CLASE 10 — JavaScript 2: Control de flujo
**Progreso:** ☐ No iniciada

**Conceptos:**
- if, else if, else — condiciones
- Operadores de comparación: ==, ===, !=, !==, >, <
- Operadores lógicos: && (AND), || (OR), ! (NOT)
- Switch: múltiples condiciones
- Ciclo while: repetir mientras se cumpla
- Ciclo for: repetir un número conocido de veces
- break y continue: control fino de ciclos
- Truthy y falsy: qué valores son true/false
- Operador ternario: condición ? sí : no

---

## CLASE 11 — JavaScript 3: Funciones y objetos
**Progreso:** ☐ No iniciada

**Conceptos:**
- Funciones: declaración, parámetros, retorno
- Arrow functions: () => {}
- Parámetros por defecto
- Objetos: { clave: valor }, propiedades y métodos
- this: qué significa dentro de un objeto
- Arrays: [], push, pop, shift, unshift
- Recorrer arrays: for, forEach, map, filter
- Spread operator: ... (copiar, combinar)
- Destructuring: extraer valores de objetos/arrays
- Métodos útiles: length, includes, indexOf, join

---

## CLASE 12 — JavaScript 4: DOM y Eventos
**Progreso:** ☐ No iniciada

**Conceptos:**
- ¿Qué es el DOM? Representación del HTML como objetos
- document.getElementById()
- document.querySelector() y querySelectorAll()
- Cambiar texto: .textContent, .innerHTML
- Cambiar estilos: .style.propiedad
- Cambiar clases: .classList.add, .remove, .toggle
- Crear elementos: document.createElement()
- Eventos: addEventListener('click', función)
- Eventos comunes: click, mouseover, keydown, submit
- Event object: e.target, e.preventDefault()

---

## CLASE 13 — JavaScript 5: Fetch y APIs
**Progreso:** ☐ No iniciada

**Conceptos:**
- ¿Qué es una API? Interfaz entre programas
- fetch(): hacer peticiones HTTP desde JS
- Promesas: .then() y .catch()
- async / await: escribir promesas más legible
- Consumir una API real (ej: clima, pokemon)
- Manejar errores: try / catch
- JSON.parse() y JSON.stringify()
- localStorage: guardar datos en el navegador
- CRUD: Create, Read, Update, Delete

---

## CLASE 14 — JSON
**Progreso:** ☐ No iniciada

**Conceptos:**
- ¿Qué es JSON? JavaScript Object Notation
- Sintaxis: {} para objetos, [] para arrays
- Tipos de datos en JSON: string, number, boolean, null, object, array
- Diferencias entre JSON y objeto JS
- JSON.parse() — convertir texto JSON a objeto
- JSON.stringify() — convertir objeto a texto JSON
- Anidamiento: objetos dentro de objetos
- JSON en archivos .json
- JSON como formato de intercambio entre frontend y backend
- Ejemplos reales: respuesta de APIs, configuraciones

---

## CLASE 15 — Python 1: Fundamentos
**Progreso:** ☐ No iniciada

**Conceptos:**
- ¿Qué es Python? Lenguaje multipropósito
- Instalación y entorno: cómo ejecutar .py
- print(): mostrar en consola
- input(): leer del teclado
- Variables: sin declarar tipo, snake_case
- Tipos: int, float, str, bool
- Operadores: +, -, *, /, //, %, **
- Strings: comillas, concatenación, f-strings
- Condicionales: if, elif, else
- Comentarios: #

---

## CLASE 16 — Python 2: Estructuras de datos
**Progreso:** ☐ No iniciada

**Conceptos:**
- Listas: [], append, remove, pop, slicing
- Tuplas: (), inmutables
- Diccionarios: {}, {clave: valor}, keys, values, items
- Conjuntos: set(), sin duplicados
- Ciclo for: recorrer listas, diccionarios, strings
- Ciclo while: repetición condicional
- range(): generar secuencias numéricas
- enumerate(): índice y valor
- in: verificar pertenencia
- Comprensión de listas: [x for x in datos]

---

## CLASE 17 — Python 3: Avanzado
**Progreso:** ☐ No iniciada

**Conceptos:**
- Funciones: def, parámetros, return
- Parámetros por defecto y kwargs
- Funciones con *args y **kwargs
- Módulos: import, from, crear módulos propios
- Paquetes: pip, instalar librerías
- Manejo de archivos: open(), read, write, with
- JSON en Python: json.dumps(), json.loads()
- try / except: manejo de errores
- Clases: class, __init__, self, métodos
- List comprehension y lambda

---

## CLASE 18 — Flask 1: Introducción
**Progreso:** ☐ No iniciada

**Conceptos:**
- ¿Qué es Flask? Micro-framework web de Python
- Instalación: pip install flask
- app = Flask(__name__)
- @app.route('/'): definir rutas
- return "HTML" desde una ruta
- debug=True: modo desarrollo
- Variables en rutas: <nombre>
- render_template(): usar archivos HTML
- Carpeta templates/ y static/
- Jinja2: {{ variable }} en HTML

---

## CLASE 19 — Flask 2: Formularios y métodos
**Progreso:** ☐ No iniciada

**Conceptos:**
- Formularios HTML: <form>, <input>, <button>
- Métodos: GET vs POST
- request.form: recibir datos del formulario
- request.args: recibir datos por URL
- Validación básica: datos requeridos, tipos
- Redirecciones: redirect(), url_for()
- Mensajes flash: flash(), get_flashed_messages()
- Sesiones: session['usuario'] = 'Aldrin'
- Cookies: set_cookie(), request.cookies
- Subir archivos: request.files

---

## CLASE 20 — Flask 3: Base de datos
**Progreso:** ☐ No iniciada

**Conceptos:**
- ¿Qué es una base de datos?
- SQLite: base de datos ligera, sin servidor
- Flask-SQLAlchemy: ORM para Flask
- Modelos: class Usuario(db.Model)
- Columnas: Integer, String, Boolean, DateTime
- CRUD: db.session.add(), .commit(), .delete()
- Consultas: .query.all(), .filter_by(), .get()
- Relaciones: uno a muchos, clave foránea
- Migraciones: actualizar BD sin perder datos
- Buenas prácticas: modelos separados

---

## CLASE 21 — Proyecto Final
**Progreso:** ☐ No iniciada

**Conceptos:**
- Integrar todo lo aprendido
- Planificación: diseño, rutas, modelos
- Frontend: HTML semántico + CSS + JS
- Backend: Flask con rutas y BD
- JSON: comunicación frontend-backend
- Usuario: registro, login, sesiones
- CRUD completo: crear, leer, actualizar, eliminar
- Responsive: que funcione en celular
- Buenas prácticas: estructura de carpetas
- Despliegue: preparar para subir a internet

---

## CLASE 22 — Próximos pasos: lenguajes y tecnologías
**Progreso:** ☐ No iniciada

**Conceptos:**
- **Java**: POO pura, apps Android, sistemas empresariales
- **TypeScript**: JS con tipos, más seguro y escalable
- **React**: biblioteca para interfaces de usuario modernas
- **Node.js**: JS en el servidor, backend con JS
- **SQL profundo**: consultas avanzadas, joins, índices
- **APIs REST**: diseño profesional de APIs
- **Autenticación**: JWT, OAuth, sesiones seguras
- **Testing**: pruebas unitarias, de integración
- **Linux**: terminal, comandos, servidores
- **Inteligencia Artificial**: conceptos básicos, APIs de AI

---

> Hecho por Aldrin · Instruido por AI · 2026
