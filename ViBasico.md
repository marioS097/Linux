# Manual vi

- **Editor de texto presente en todas las distribuciones**

## Formas de abrirlo

- Solo
  > vi
- Directamente el archivo a editar
  > vi [archivo]

## Uso

### Editar y modificar

| Utilizacion | Comando |
| --- | :-: |
| Para Insertar texto antes del cursor | **i** |
| Para Insertar texto después del cursor | **a** |
| Para Insertar texto al principio de la linea | **I** |
| Para Insertar texto al final de la Linea | **A** |

### Copiar y pegar 

| Utilizacion | Comando |
| --- | :-: |
| Para copiar la linea actual | **yy** |
| Para copiar una palabra | **yw** |
| Para copiar 7 lineas | **y7y** |
| ---| ---|
| Para pegar después del cursor (Minuscula)| **p** |
| Para pegar antes del cursor (Mayuscula)| **P** |

### Borrar

| Utilizacion | Comando |
| --- | :-: |
|Para Borrar la linea actual | **dd** |

### Abrir, Grabar y Salir

| Utilizacion | Comando |
| --- | :-: |
| Para abrir un archivo | **:e** *nombre_archivo* |
| Para guardar los cambios y salir | **:wq** |
| Para Salir sin guardar | **:q!** |
| Para guardar con otro nombre de archivo | **:w** *nombre_archivo*

## Informacion adicional

  > man vi