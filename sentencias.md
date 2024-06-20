# Tarea 
## 1. Crear la lista
 - Sentencia:
  
CREATE VIEW invoice_view AS
SELECT i.id, i.code, i.created_at, i.total, c.full_name
FROM invoice i
JOIN clients c ON c.id = i.client_id;

-Captura.
<imag!![Imagen de WhatsApp 2024-06-20 a las 15 53 43_08dac87c](https://github.com/micaelabar/tarea_class_gestion_base/assets/148156209/64b6a916-39c2-4235-a53d-6b426aff54df)


## 2. 
 - Sentencia:
  
  SSELECT * FROM invoice_view ....
  
-Captura.


