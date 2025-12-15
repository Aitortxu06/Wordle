# Wordle
Hola soy Aitor y vamos a hacer el Ejercicio1 que nos a mandado Yaiza.

# PRUEBA MARKDOWN: AITOR PEÑA
## Repositorio clonado de Wordle para pruebas de GitHub.
### Esto lo hemos creado

*Hecho por Aitor.*

Mecánica del juego: 
- **Verde:** *letra correcta en la posición correcta.*
- **Amarillo:** *letra correcta en posición incorrecta.*
- **Gris:** *letra no está en la palabra.*

## TABLA EJEMPLO PARA EL QUE NO SEPA UTILIZAR WORDLE
  Tabla:  
  | **Palabra introducida** | **Resultado en pantalla** |
  |-------|-------|
  |CASA|ARVA| 
  |SACO|RVAV|
  |PANTALLA|VVVRRARV|
  |MONEDA|VARRRA|
  |EUSKADI|RRRVARV|

## ENLACE PROPIO DE GITHUB AITOR 
  - Enlace de mi GitHub:
    - [GitHub proyecto de Aitor Peña de Wordle](https://github.com/Aitortxu06/Wordle/tree/main)
## IMAGEN ORIGINAL DEL JUEGO DE WORDLE
  Vamos a añadir una **IMAGEN DEL JUEGO DE WORDLE** original:
  ![Imagen Wordle Original](https://github.com/Aitortxu06/Wordle/blob/main/wordle-art-superJumbo.jpg)
## EJEMPLO CODIGO DE PYTHON, JAVA, HTML Y JAVASCRIPT
***Python:***  
```python
      for i, letra in enumerate(palabra_introducida):
      if letra == palabra_objetivo[i]:
          print("V", end="")
      elif letra in palabra_objetivo:
          print("A", end="")
      else:
          print("R", end="")
```
***Java:***  
```Java
    for (int i = 0; i < palabraIntroducida.length(); i++) {
      char letra = palabraIntroducida.charAt(i);
      if (letra == palabraObjetivo.charAt(i)) {
        System.out.print("V");
      } else if (palabraObjetivo.indexOf(letra) != -1) {
        System.out.print("A");
      } else {
        System.out.print("R");
      }
    }
    System.out.println();
```
***Html:*** 
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo Wordle Básico</title>
</head>
<body>
  <h1>Ejemplo Wordle</h1>

  <h2>Tabla de ejemplo</h2>
  <table border="1">
    <tr>
      <th>Palabra introducida</th>
      <th>Resultado en pantalla</th>
    </tr>
    <tr>
      <td>CASA</td>
      <td>VRRR</td>
    </tr>
    <tr>
      <td>SACO</td>
      <td>AVRR🟩⬜⬜</td>
    </tr>
    <tr>
      <td>CAMA</td>
      <td>VVRV</td>
    </tr>
  </table>

  <h2>Enlace al proyecto original</h2>
  <p>
    <a href="https://github.com/powerlanguage/wordle" target="_blank">
      Proyecto Wordle en GitHub
    </a>
  </p>

  <h2>Imagen del Wordle original</h2>
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Wordle_game.png" alt="Wordle original">
</body>
</html>
```
***JavaScript:***  
```JavaScript
const palabraObjetivo = "CASA";

function comprobar() {
  const entrada = document.getElementById("entrada").value.toUpperCase();
  let salida = "";

  for (let i = 0; i < entrada.length; i++) {
    if (entrada[i] === palabraObjetivo[i]) {
      salida += "🟩";
    } else if (palabraObjetivo.includes(entrada[i])) {
      salida += "🟨";
    } else {
      salida += "⬜";
    }
  }

  document.getElementById("resultado").textContent = salida;
}
```
# EJERCICIO 2
## UN SEPARADOR
### Hola soy Aitor Peña y estoy haciendo un readme del juego de **WORDLE**.
---
## ALINEAR LA TABLA
## Tabla alineada

| Palabra introducida | Resultado en pantalla |
|:-------------------:|:---------------------:|
| CASA                | VRRR                 |
| SACO                | AVRR               |
| CAMA                | VVRV               |

---
## CITA SOBRE WORDLE
> *"Wordle es un juego sencillo que demuestra cómo la lógica y la intuición pueden convertirse en diversión diaria."*
---
## CARÁCTERES ESPECIALES
Aquí un ejemplo con un carácter especial: © 2025 Proyecto Wordle  
También puedes usar otros como →, ★, ☑, ✓ para dar estilo.
## LISTA DE TAREAS DE WORDLE
- [x] Añadir una tabla con ejemplos para explicar cómo funciona Wordle  
- [x] Incluir un enlace al proyecto original en GitHub
- [ ] - [ ] Implementar versión interactiva en HTML + JavaScript  
- [x] Insertar una imagen del Wordle original  
- [x] Mostrar un par de líneas del código implementado (Java / JavaScript)
- [ ] Guardar historial de palabras introducidas
## EJEMPLO CON COMENTARIOS Y DESPLEGABLES

<!-- Esto es un comentario en Markdown, igual que en HTML -->
<!-- Comentario -->
### Desplegable con `<summary>`
<details>
<summary>Haz clic aquí para ver más información</summary>

Este es el contenido oculto dentro del desplegable.  
Puedes poner texto, tablas, imágenes o incluso código.
    


  

    
    


