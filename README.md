# RandomExpansion

Maquinas y utilidades variadas para ampliar Slimefun.

Adaptación de DrakesCraft para **Paper/Purpur 1.21.11** y Java 21.

## Qué es

Maquinas y utilidades variadas para ampliar Slimefun.

Aporta **9 objetos** repartidos en 10 clases.

## Qué cambiamos

Este repositorio **no es un fork**: es el código original integrado en el ecosistema de
DrakesCraft. Los cambios son de compatibilidad, no de contenido:

- Los paquetes de Slimefun pasan de `io.github.thebusybiscuit` a `com.github.drakescraft_labs`,
  que es como está repaquetado nuestro core. Sin eso, el addon no encuentra ni una clase.
- Compila contra Java 21 y `paper-api` 1.21.1, en vez de las versiones de su época.
- Se actualizan dependencias que vivían en repositorios de Maven que ya no responden.

El paquete propio del addon y sus nombres de clase **se dejan intactos**, para que las
actualizaciones de arriba sigan siendo legibles y se pueda comparar con el original.

## Instalación

Necesita Slimefun de DrakesCraft (`Slimefun4-Drake`). Se pone el jar en `plugins/` y listo.

## Crédito

El trabajo de fondo es de los autores originales. Nosotros solo lo hemos adaptado.

- Origen: https://github.com/SlimefunGuguProject/RandomExpansion.git
- Licencia: **MIT**

La licencia original se conserva sin tocar en este repositorio. Si eres el autor y prefieres
que retiremos esta adaptación, escríbenos y se quita.
