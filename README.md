## solidity-ide-modulo1

### **Actividad 1** - Ejercicio para la comprobación de que el entorno ha sido correctamente instalado.

#### Tutorial Truffle Pet Shop

Se indican los pasos del tutorial más interesantes:

  1. Se crea el proyecto con el comando `truffle unbox pet-shop`
  ![Captura 1](screenshots/screen001.png "Captura 1")
  2. Se crea el contrato Adoption con las funciones correspondientes
  3. Hemos compilado el contrato con el comando `truffle compile`
  4. Se crea el fichero para migrar el contrato de Adoption y se ejecuta `truffle migrate`
  5. Previo al paso anterior, se ha tenido que ejecutar la aplicación Ganache en el sistema para simular una red Ethereum.
  ![Captura 2](screenshots/screen002.png "Captura 2")
  6. Se crea un contrato de test llamado `TestAdoption.sol` para validar nuestro contrato.
  7. Se ejecutan los test con el comando `truffle test`
  8. Se abre los recursos web que utilizan `web3.js` y se completa el fichero `src/js/app.js` con los pasos que indica el tutorial
  9.  Nos logeamos con la extensión `MetaMask` apuntando a la dirección y puerto local de Ganache
  11. Levantamos los recursos web a través del servidor de desarrollo con el comando `npm run dev`
  12. Ya podemos acceder desde el navegador a nuestra Dapp e interactuar con ella, adoptando así a los animales que se deseen.
  ![Captura 3](screenshots/screen003.png "Captura 3")


#### Preguntas relacionadas

+ Comprobar que existe conexión a un nodo
+ Comprobar si está o no sincronizando nuevos bloques. ¿Por qué?
+ Balance de la cuenta que ha desplegado el contrato en la blockchain
+ Address de la cuenta número 3 de Ganache o ganache-cli
+ Numero de bloque nel que se encuentra blockchain en ese instante. ¿Por qué?
+ Dirección del host de la blockchain
+ Acceda a ethgassstation y convierta del gas en ese instante a Ether.



### **Actividad 2** - Ejercicios de Solidity

+ 5 preguntas (la ultima extra)


### Autor
- Javier Gasso


