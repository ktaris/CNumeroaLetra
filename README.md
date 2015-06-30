# Clase CNumeroaLetra

Clase para convertir números en palabras.

La clase fue desarrollada por Omar Eduardo Ortiz Garza, y se ha creado este repositorio con el único fin de añadirla como dependencia mediante composer.


## Instalación

Añade la dependencia al archivo ```composer.json```:

```json
{
    "require": {
        "ktaris/numeroaletra": "1.0"
    }
}
```

## Uso

```php
$numalet= new CNumeroaLetra;
$numalet->setNumero($total);
echo $numalet->letra();
```