📌 Overview

Este repositorio contiene los contratos principales que componen la infraestructura on-chain de Nummora, el protocolo P2P de préstamos y créditos accesibles.
Cada contrato cumple un rol específico dentro del ecosistema: manejo del token interno, operaciones del core.

📜 Contracts
### 1. NCOP

📍 Address: 0x31b7C966ac4585220E94fA0Ba64434e5B32e0173

2. NummusToken

📍 Address: 0x77aeD92b57eEC1feD19EBf0D99B3400774900D7F
Este contrato define el token nativo del protocolo, Nummus (NUM), que se usa para ciertas funciones dentro del sistema, como rewards, gobernanza o futuras integraciones.

Características típicas:

ERC-20 estándar.

Funciones de minting / burning según la implementación.

Se usa como token utilitario dentro del protocolo.

3. NummoraCore

📍 Address: 0xaa28E8abfD7e8c172791b47825F33a8B2fff7a3E
Es el contrato principal del sistema y coordina toda la lógica del protocolo.

Responsabilidades clave:

Manejo de solicitudes de préstamos.

Validación de usuarios y parámetros crediticios.

Conexión entre NCOP y NummusToken.

Administración de fondos, flujos y eventos del protocolo.
