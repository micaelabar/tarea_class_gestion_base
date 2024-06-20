# Tarea 
## 1. Crear la lista
 - Sentencia:
  
CREATE VIEW invoice_view AS
SELECT i.id, i.code, i.created_at, i.total, c.full_name
FROM invoice i
JOIN clients c ON c.id = i.client_id;

  

## 2. 
 - Sentencia:
  
  SSELECT * FROM invoice_view ....
  
-Captura.

![image]![Imagen de WhatsApp 2024-06-20 a las 15 53 43_90a0da9c](https://github.com/micaelabar/tarea_class_gestion_base/assets/148156209/80ca4c78-17d7-4d7e-821a-c02e3be9bd39)
