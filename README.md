# Examen_Moviles

Esta aplicación móvil fue creada para digitalizar la toma de lecturas de medidores de agua en el Distrito Metropolitano de Quito. La idea es que los encargados de registrar las lecturas puedan hacerlo directamente desde su teléfono, de forma rápida, confiable y con evidencia visual, sin depender de formularios en papel. Para esto usamos Ionic + Angular en el frontend y Supabase en el backend.

# Qué hace la app
## Captura de evidencia

Permite tomar fotos del medidor y de la fachada de la vivienda.

Todas las imágenes se guardan en Supabase Storage para que queden registradas de manera segura.

<img width="929" height="397" alt="image" src="https://github.com/user-attachments/assets/34e381fc-9f09-4bc3-a53e-f9ff2cecbecf" />


## Ubicación automática

Obtiene la ubicación del dispositivo vía GPS (latitud y longitud).

Genera un enlace directo a Google Maps para poder revisar dónde se tomó la lectura.

<img width="924" height="386" alt="image" src="https://github.com/user-attachments/assets/cf5dfbe9-8db1-4dd3-9502-fd9868a0af48" />
--
<img width="952" height="536" alt="image" src="https://github.com/user-attachments/assets/82e842da-2987-4217-9349-721a39ae9ba6" />


## Información de la medición

Valor actual del medidor.

Observaciones adicionales si el usuario quiere anotarlas.

Identificación del usuario que realizó la medición.

<img width="919" height="318" alt="image" src="https://github.com/user-attachments/assets/1a3a0800-302d-46d0-89ef-282a218f003d" />


# Perfiles de usuario
## Medidor

Puede registrar nuevas lecturas con fotos y ubicación.

Solo ve sus propios registros gracias a las políticas RLS de Supabase.

<img width="926" height="917" alt="image" src="https://github.com/user-attachments/assets/df8ba8eb-2c20-42a3-8b52-0356a94093c3" />


## Administrador

Puede ver todos los registros de todos los medidores.

Accede a fotos, coordenadas y enlaces de Google Maps.
