# Examen_Moviles

Esta aplicación móvil fue creada para digitalizar la toma de lecturas de medidores de agua en el Distrito Metropolitano de Quito. La idea es que los encargados de registrar las lecturas puedan hacerlo directamente desde su teléfono, de forma rápida, confiable y con evidencia visual, sin depender de formularios en papel. Para esto usamos Ionic + Angular en el frontend y Supabase en el backend.

# Qué hace la app
## Captura de evidencia

Permite tomar fotos del medidor y de la fachada de la vivienda.

Todas las imágenes se guardan en Supabase Storage para que queden registradas de manera segura.

## Ubicación automática

Obtiene la ubicación del dispositivo vía GPS (latitud y longitud).

Genera un enlace directo a Google Maps para poder revisar dónde se tomó la lectura.

## Información de la medición

Valor actual del medidor.

Observaciones adicionales si el usuario quiere anotarlas.

Identificación del usuario que realizó la medición.

# Perfiles de usuario
## Medidor

Puede registrar nuevas lecturas con fotos y ubicación.

Solo ve sus propios registros gracias a las políticas RLS de Supabase.

## Administrador

Puede ver todos los registros de todos los medidores.

Accede a fotos, coordenadas y enlaces de Google Maps.
