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

# **[Día 1 ​Blockchain concepts and Wallets](https://www.youtube.com/watch?v=1SNmVktaagU)**
- Creación de billeteras en MetaMask, Cuenta1 y Cuenta2
- Obtenga Sepolia ETH del faucet para la Cuenta 1
- Transferencia de Cuenta1 a Cuenta2 0.1 Sepolia ETH

# **[​Día 2 ​Solidity Fundamentals](https://www.youtube.com/watch?v=aPc_jJvPhxw)**
### Creación del contrato inteligente Register.sol
 Este contrato es muy básico que permite obtener y establecer una única cadena de información.

### Creando el contrato inteligente RegisterAccess.sol
 Este contrato es un sistema de control de acceso simple que permite al propietario administrar una lista de información, controlar el acceso a ciertas funciones y monitorear cambios a través de eventos.

# **[​Día 3 ​ ​ERC20 Tokens and Chainlink Data Feeds](https://www.youtube.com/watch?v=prf1SS1t2hc)**
### Creación del contrato inteligente Token.sol

Este contrato crea el token. Amplía los contratos OpenZeppelin ERC20 y AccessControl.

Este contrato de token introduce un mecanismo de control de acceso basado en roles, que permite que ciertas direcciones con MINTER_ROLE creen (acuñan) nuevos tokens.

El suministro total, los saldos y las transferencias de tokens siguen el comportamiento estándar ERC-20 heredado del contrato OpenZeppelin ERC20.

### Creación del contrato inteligente TokenShop.sol

De aquí proviene el token creado: es una dApp (aplicación descentralizada) simple que actúa como un almacén de tokens, lo que permite a los usuarios comprar tokens enviando ETH al contrato.

Este contrato se basa en un oráculo Chainlink externo para obtener el precio ETH/USD.

# **[​Día 4 ​Cross Chain Tokens using Chainlink CCIP](https://www.youtube.com/watch?v=6KtafiSU65g)**
### CCIP de enlace de cadena

Creación del contrato inteligente CCIPTokenSenderFujiSepolia.sol

Aquí utilizamos el protocolo de interoperabilidad entre cadenas para transferir mensajes Chainlink CCIP desde la red de prueba AVAX Fuji a la red de prueba Sepolia Ethereum.

Implica crear y enviar un mensaje CCIP, administrar las tarifas de los tokens LINK y permitir que el propietario del contrato retire los tokens restantes.

El selector de cadena de destino (destinationChainSelector) está configurado en la red de prueba de Sepolia.

**[CCIP de enlace de cadena](https://docs.chain.link/ccip)**

**[Testnet AVAX Fuji](https://testnet.snowtrace.io/)**

**[Redes compatibles con CCIP](https://docs.chain.link/ccip/supported-networks)**



# **[​Día 5 ​Mentoring session with the Chainlink community](https://www.youtube.com/watch?v=24Ii_0HjiWo)**
- Mentoria con algunos miembros de la comunidad en español de Chainlink.

# **[​Día 6 ​NFTs and Chainlink Automation](https://www.youtube.com/watch?v=I0J7BiznF_k)**
NFTs (Non-Fungible Token)

Images in NFTs

IPFS: Piñata, Infura, Quicknode NFT.storage, Web3.storage, Thirdweb storage

Metadata - Json
```
{
    "name": "NFT item name",
    "description": "NFT item description",
    "image": "https://...",
    "attributes": [...]
}
```

Creating a NTF collection with OpenZeppelin wizard
https://wizard.openzeppelin.com/#erc721

Listing in OpenSea marketplace
https://testnets.opensea.io/

Creating Dynamic NFT

Metadata - On-chain upgrade
    - Metadata URL
    - URL image
    - Json

- Los contratos inteligentes NO son autoejecutables
- No pueden por sí solos iniciar un proceso o llamar a sus funciones de vez en cuando o bajo ciertas condiciones.
- Los cambios en el estado de un contrato inteligente solo ocurren cuando otra cuenta inicia una transacción
- Ejemplos: un usuario, oráculo u otro contrato inteligente

Actualización de NTF con Blockchain Oracles

Chainlink Automation: automatización descentralizada de contratos inteligentes

Red descentralizada de nodos. Los cuales son recompensados por ejecutar procesos registrados (trabajos), llamados Mantenimientos.

Se pueden utilizar para verificar condiciones y enviar transacciones a contratos inteligentes según reglas preestablecidas. Es el agente activo el que interactuará con un contrato inteligente.

[Chainlink Automation](https://chain.link/automation)

[Docs Chainlink Automation](https://docs.chain.link/chainlink-automation)

[Register new Upkeep](https://automation.chain.link/)

# **[​Día 7 ​Chainlink CCIP in cross-chain dApps](https://www.youtube.com/watch?v=y_iOxra1oLc)**
### Cross-chain NFTs

Arbitrary Messaging

Programmable Token Transfers

**[Chainlink CCIP](https://docs.chain.link/ccip)**

[Price Feed Contract Addresses](https://docs.chain.link/data-feeds/price-feeds/addresses)

# **[​Día 8 ​Random Numbers using Chainlink VRF](https://www.youtube.com/watch?v=J5uH0fOzTTQ)**
### Chainlink VRF
**Chainlink VRF (función aleatoria verificable)** es un generador de números aleatorios (RNG) demostrablemente justo y verificable que permite que los contratos inteligentes accedan a valores aleatorios sin comprometer la seguridad o la usabilidad.

Crea un juego Runners usando Chainlink VRF.

**[Recurso VRF](https://dev.chain.link/products/vrf)**

# **[​Día 9 ​Chainlink Functions to access off-chain data](https://www.youtube.com/watch?v=RVTWeJn3LNw)**
### Chainlink Functions
Chainlink Functions permite a cualquiera escribir código sin servidor para recuperar datos de cualquier API y ejecutar cálculos personalizados en la red de Chainlink.
**[usechainlinkfunctions.com](https://usechainlinkfunctions.com/)**

**[Docs Chainlink Functions](https://dev.chain.link/products/functions)**

[](https://functions.chain.link/)

**[Run-functions](https://www.run-functions.app/)**

**[NPM package @chainlink/functions-toolkit](https://www.npmjs.com/package/@chainlink/functions-toolkit)**

**[Ways To Use Chainlink Functions in Your Decentralized Applications](https://blog.chain.link/ways-to-use-chainlink-functions/)**

# **[​Día 10 ​Connecting the world using the Chainlink platform](https://www.youtube.com/watch?v=Y2BaK8AX_E8)**
### Chainlink Proof of Reserve (PoR)
- Obtenga datos en sus contratos inteligentes de fuentes externas
- Cualquier activo dentro de la cadena respaldado por reservas fuera de la cadena o entre cadenas.
- Proporciona contratos inteligentes con los datos necesarios para calcular la verdadera colateralización.
- Operado por una red descentralizada de oráculos
- Reducir los riesgos de insolvencia con auditorías automatizadas y basadas en la verdad.
- Mejorar la transparencia para los usuarios.
- Prevenir fallas sistémicas en DeFi

Para: activos digitalizados, frenos de circuito, tokenización entre cadenas, nuevos productos financieros, activos entre cadenas, activos envueltos, monedas estables respaldadas por Fiat, prueba de reserva para Bitcoin
**[Chainlink Proof-of-Reserve](https://chain.link/proof-of-reserve)**

**[Docs: Chainlink Market and Data Feeds](https://docs.chain.link/data-feeds/proof-of-reserve)**

**[Article: What Are Proof of Reserves?](https://chain.link/education-hub/proof-of-reserves)**

**[Article: Verify Stablecoin Collateral With Chainlink Proof of Reserve](https://blog.chain.link/verify-stablecoin-collateral-with-chainlink-proof-of-reserve/)**


### Data Streams
Con Data Streams, las dApps tienen acceso bajo demanda a datos de mercado de alta frecuencia respaldados por una infraestructura descentralizada y transparente.
**[Docs: Data Streams](https://docs.chain.link/data-streams)**
