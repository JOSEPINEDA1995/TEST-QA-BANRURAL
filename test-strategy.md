1. la funcion no esta llamada correctamente. linea 92 falta ()=>
2. el comando AaddeventListener esta mal escrito addEventListener
3. la clase lowOrHi no esta bien definida debe de ser .lowOrHi liena 48. 
4. el numero ramdon no esta correcto se debe multiplicar por *100 linea 44
5. validacion incorrecta linea 65  debe de ser el siguiente codigo
 if(guessCount == ATTEMPS) {
      lastResult.textContent = '!!!Pérdistes!!!';
      lastResult.style.backgroundColor = 'Red'; // color incorrecto
      // codigo de mas.
      setGameOver();
      // validacion incorrecta debe ser 
6.errores de colores el codigo debe quedar de la siguiente manera
else if(userGuess == Number.parseInt(randomNumber)) {
      lastResult.textContent = 'Felicitaciones! adivinaste el número!';
      lastResult.style.backgroundColor = 'green'; // color incorrecto
      setGameOver();
    } else {
      lastResult.textContent = 'Incorrecto! ';
      lastResult.style.backgroundColor = 'black';// color incorrecto
      if(userGuess < randomNumber) {
        //loworhi no esta declarado de manera correcta no es una clase hace falta el .lowOrHi
        lowOrHi.textContent = 'El número es mayor!';
      } else if(userGuess > randomNumber) {
        lowOrHi.textContent = 'El número es menor!';
      }
7. linea 106 la clase esta mal escrita la "p" esta de mas.
.