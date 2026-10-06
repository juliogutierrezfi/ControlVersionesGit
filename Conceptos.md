# Conceptos básicos de Git/GitHub

## Repositorio

Un repositorio es como una carpeta donde se encuentran almacenados
los archivos de un proyecto.

Puede contener:

- Código.
- Documentación.
- Ejemplos.
- Archivos del proyecto.

Los repositorios pueden ser:

- Públicos.
- Privados.

## README

El archivo `README.md` contiene las instrucciones e información básica
para utilizar y comprender un repositorio.

Puede incluir:

- Nombre del proyecto.
- Descripción.
- Créditos.
- Índice.
- Uso del proyecto.
- Licencia.

## Rama (Branch)

Una rama es una copia del contenido de un proyecto que permite trabajar
en paralelo sin modificar directamente el proyecto original.

### Rama principal

La rama principal contiene el proyecto original.

### Rama de trabajo

Permite realizar modificaciones de forma independiente.

Si se produce un error en esta rama, no afecta directamente al proyecto
original.

## Clone

`clone` permite realizar una copia del proyecto original para trabajar
con él de forma local.

Ejemplo:

```bash
git clone https://github.com/usuario/proyecto.git
