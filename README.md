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
## EJEMPLO CODIGO DE PYTHON Y DE JAVA
  ***Python:***  
    ``` python
    for i, letra in enumerate(palabra_introducida):
    if letra == palabra_objetivo[i]:
        print("🟩", end="")
    elif letra in palabra_objetivo:
        print("🟨", end="")
    else:
        print("⬜", end="")
    ```
  ***Java:***  
    ``` java
    for (int i = 0; i < palabraIntroducida.length(); i++) {
      char letra = palabraIntroducida.charAt(i);
      if (letra == palabraObjetivo.charAt(i)) {
        System.out.print("🟩");
      } else if (palabraObjetivo.indexOf(letra) != -1) {
        System.out.print("🟨");
      } else {
        System.out.print("⬜");
      }
    }
    System.out.println();
    ```
    
    


