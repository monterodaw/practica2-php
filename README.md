# Práctica 2: Ejercicios de PHP

Colección de **ejercicios básicos de PHP** (arrays, bucles, cadenas, fechas y formularios)
realizados en 2º de *DAW*.

## Ejercicios

### Lista desordenada

- `aleatorios.php`: 10 números aleatorios únicos, mayor, menor y promedio.
- `cumpleanos.php`: días que faltan para cada cumpleaños.
  - Usa `date('z')` para obtener el día del año.
- `factorial.php`: factorial de un número leído por teclado.
- `temperaturas.php`: de Celsius a Fahrenheit y Kelvin.
- `vocales.php`: cuenta las vocales de una cadena.
- `formulario.html` y `ejercicio6.php`: calculadora con formulario.

### Lista ordenada

1. Descarga el proyecto.
2. Abre una terminal en la carpeta.
3. Ejecuta el script que quieras con `php aleatorios.php`.

### Énfasis de texto

Texto en *cursiva*, en **negrita** y ~~tachado~~.

### Enlace

Documentación oficial de [PHP](https://www.php.net).

### Cita

> Los programas deben escribirse para que los lean las personas.

### Tabla de ficheros

| Archivo          | Tipo       | Entrada    |
|:-----------------|:----------:|-----------:|
| `aleatorios.php` | Consola    | Ninguna    |
| `factorial.php`  | Consola    | Teclado    |
| `ejercicio6.php` | Web (POST) | Formulario |

### Código de ejemplo

```php
<?php
$numero = 5;
$resultado = 1;
for ($i = 1; $i <= $numero; $i++) {
    $resultado *= $i;
}
echo $resultado;
```
