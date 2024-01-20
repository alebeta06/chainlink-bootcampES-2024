![solidity](https://img.shields.io/badge/Solidity-e6e6e6?style=for-the-badge&logo=solidity&logoColor=black)
![ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?logo=ethereum&logoColor=fff&style=for-the-badge)
![openzeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?logo=OpenZeppelin&logoColor=fff&style=for-the-badge)
![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?style=for-the-badge&logo=Chainlink&logoColor=white)

#### Se utilizo el entorno de desarrollo de Remix IDE

## Chainlink Bootcamp 2024 en Español.

- Entender cómo construir contratos inteligentes es una de las habilidades que está teniendo un incremento debido al creciente interes en el mundo de Web3.
- Aprender desde principios básicos de blockchain hasta cómo crear contratos inteligentes en Ethereum.
- Conocerás la plataforma de Chainlink y todos sus servicios.

Link a las sesiones:

**[Día 1 ​Blockchain concepts and Wallets](https://www.youtube.com/watch?v=1SNmVktaagU)**
- Creación de billeteras en MetaMask, Cuenta1 y Cuenta2
- Obtenga Sepolia ETH del faucet para la Cuenta 1
- Transferencia de Cuenta1 a Cuenta2 0.1 Sepolia ETH

**[​Día 2 ​Solidity Fundamentals](https://www.youtube.com/watch?v=aPc_jJvPhxw)**
### Creación del contrato inteligente Register.sol
 Este contrato es muy básico que permite obtener y establecer una única cadena de información.

### Creando el contrato inteligente RegisterAccess.sol
 Este contrato es un sistema de control de acceso simple que permite al propietario administrar una lista de información, controlar el acceso a ciertas funciones y monitorear cambios a través de eventos.

**[​Día 3 ​ ​ERC20 Tokens and Chainlink Data Feeds](https://www.youtube.com/watch?v=prf1SS1t2hc)**
### Creación del contrato inteligente Token.sol

Este contrato crea el token. Amplía los contratos OpenZeppelin ERC20 y AccessControl.

Este contrato de token introduce un mecanismo de control de acceso basado en roles, que permite que ciertas direcciones con MINTER_ROLE creen (acuñan) nuevos tokens.

El suministro total, los saldos y las transferencias de tokens siguen el comportamiento estándar ERC-20 heredado del contrato OpenZeppelin ERC20.

### Creación del contrato inteligente TokenShop.sol

De aquí proviene el token creado: es una dApp (aplicación descentralizada) simple que actúa como un almacén de tokens, lo que permite a los usuarios comprar tokens enviando ETH al contrato.

Este contrato se basa en un oráculo Chainlink externo para obtener el precio ETH/USD.

**[​Día 4 ​Cross Chain Tokens using Chainlink CCIP](https://www.youtube.com/watch?v=6KtafiSU65g)**
### CCIP de enlace de cadena

Creación del contrato inteligente CCIPTokenSenderFujiSepolia.sol

Aquí utilizamos el protocolo de interoperabilidad entre cadenas para transferir mensajes Chainlink CCIP desde la red de prueba AVAX Fuji a la red de prueba Sepolia Ethereum.

Implica crear y enviar un mensaje CCIP, administrar las tarifas de los tokens LINK y permitir que el propietario del contrato retire los tokens restantes.

El selector de cadena de destino (destinationChainSelector) está configurado en la red de prueba de Sepolia.

**[CCIP de enlace de cadena](https://docs.chain.link/ccip)**

**[Testnet AVAX Fuji](https://testnet.snowtrace.io/)**

**[Redes compatibles con CCIP](https://docs.chain.link/ccip/supported-networks)**



**[​Día 5 ​Mentoring session with the Chainlink community](https://www.youtube.com/watch?v=24Ii_0HjiWo)**
- Mentoria con algunos miembros de la comunidad en español de Chainlink.

**[​Día 6 ​NFTs and Chainlink Automation](https://www.youtube.com/watch?v=I0J7BiznF_k)**

**[​Día 7 ​Chainlink CCIP in cross-chain dApps](https://www.youtube.com/watch?v=y_iOxra1oLc)**

**[​Día 8 ​Random Numbers using Chainlink VRF](https://www.youtube.com/watch?v=J5uH0fOzTTQ)**

**[​Día 9 ​Chainlink Functions to access off-chain data](https://www.youtube.com/watch?v=RVTWeJn3LNw)**

**[​Día 10 ​Connecting the world using the Chainlink platform](https://www.youtube.com/watch?v=Y2BaK8AX_E8)**
