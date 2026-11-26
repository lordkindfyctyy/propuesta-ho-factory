# Propuesta para HO Factory Pet

Borrador. La web se publica sola con GitHub Pages desde la rama `main`: cada push la actualiza en uno o dos minutos.

| Qué | Archivo | Dirección |
|---|---|---|
| Propuesta (visible en Google) | `propuesta/index.html` | https://lordkindfyctyy.github.io/propuesta-ho-factory/propuesta/ |
| Muestra de la landing (fuera de Google) | `landing/index.html` | https://lordkindfyctyy.github.io/propuesta-ho-factory/landing/ |

En `materiales/` están el PDF, la captura y el mensaje. No se actualizan solos si cambian las páginas.

## Trabajar desde otra PC

La primera vez:

    git clone https://github.com/lordkindfyctyy/propuesta-ho-factory.git
    cd propuesta-ho-factory
    git config user.name lordkindfyctyy
    git config user.email 201158614+lordkindfyctyy@users.noreply.github.com

Cada vez:

    git pull
    # editar el archivo
    git add -A
    git commit -m "qué cambié"
    git push

## Cuidado

- El repositorio es **público**: no subir contraseñas, listas de clientes, precios privados ni capturas de chats.
- No borrar `propuesta/google6c7f92b2cad4a7bb.html` (verificación de Google).
- La landing tiene `noindex` hasta que el dueño de la marca la apruebe.
- Las fotos son de HO Factory Pet.

## Pendiente

Precios por mayor, pedido mínimo, envío, zonas, precio correcto de los Nidos y fotos finales.

Condiciones de socio (en la propuesta): link `register.php?socio=HOFACTORY`, clientes sin plan gratis (pagan desde el día 1), plan Pro desde $15.990/mes, 30 % de lo que queda después de Mercado Pago, pago mensual por transferencia. Falta definir si el 30 % es para siempre o por un plazo.
