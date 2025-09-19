# gasfeeconvert
Web that converts Gas Fee to different coins consulting an API

Pagina web que permite al usuario consultar el precio del gas que consume una transacción.

Consiste en que el usuario puede introducir el monto del gas a consumir, se realiza una consulta a una API en Etherscan (mediante una API Key), devuelve el monto mínimo de Gas Fee, luego lo multiplica por el precio actual de Ethereum (realizando otra consulta a una API en Etherscan) y devuelve el precio en dólares y en pesos argentinos.

Actualmente en estado de Prototipo.
