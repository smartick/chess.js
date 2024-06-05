# Changelog

La librería se sustenta a partir de la versión 0.13.3 de la original (https://github.com/jhlywa/chess.js).
Para cada cambio realizado se debe generar un tag en git y añadir la información en este fichero.

## [0.13.3-smk3] - 2024-06-05
### Added
- ADD Método "smk_attacked" para detectar si una casilla es atacada.
- ADD Métodos para transformar 0x88 en algebraico y viceversa.
- ADD Método "smk_get_pieces" para obtener las piezas de un determinado tipo en una posición.

## [0.13.3-smk2] - 2023-12-13
### Updated
- Tal y cómo se realiza en el original, se incluyen before y after con el fen en cada movimiento.

## [0.13.3-smk1] - Primera versión
### Updated
- Posibilidad de incluir varios reyes del mismo color en una posición.
- Posibilidad de realizar movimientos ilegales.
- Posibilidad de tener posiciones sin reyes.
- Se incluyen métodos particulares útiles para SMK.