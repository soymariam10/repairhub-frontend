# repairhub-frontend
Aplicacion web que permite llevar el registro y control de todos los servicios especializados que el centro de diagnostico y reparacion de vehiculos presta.

Requerimientos:
  1. Diseñar una UI que permita administrar la informacion del taller.
  2. Administrar informacion de cada una de las personas que forman parte de REPAIRHUB (mecanicos, personal admin, proveedores, clientes).
  3. REPAIRHUB desea registrar el ingreso de los vehiculos, al momento del ingreso se debe realizar una inspeccion del vehiculo para registrar el estado fisico (puertas, farolas, cabina).
       INFORMACION DEL FORMATO:
           1. DATOS DEL CLIENTE N° ORDEN
               ID cliente, Nombre, Direccion, Nro fijo, Nro movil, Email
           2. DATOS DEL VEHICULO
               Tipo vehiculo, placa, modelo, color, Km
           3. INSPECCION DEL VEHICULO
               PUERTAS: F izquierda, T izquierda, F derecha, T derecha (descripcion)
               CABINA:
                 RADIO: marca (descripcion), estado
                 TAPICERIA: techo, muebles, tapetes, otros (descripcion)
           4. DIAGNOSTICO CLIENTE (descripcion)
           5. PERSONAL RESPONSABLE
               ID empleado, Nombre empleado, telefono empleado, movil empleado, especialidad
           6. DIAGNOSTICO TALLER (descripcion)
     
  4. El responsable realiza el registro de los hallazgos encontrados en el vehiculo, registrando los repuestos que deben ser cambiados en el siguiente formato:
       INFORMACION DLE FORMATO:
           1. AUTORIZACION DE REPARACION
               estado, observacion, repuesto, marca, cantidad, valor unitario, valor total
               valor total repuestos, valor mano obra, valor total reparacion
              (el valor a facturar dependera de los repuestos que el cliente seleccione/autorice)
  5. Entrega vehiculo => cuando se le hace entrega de vehiculo al cliente se debe hacer un cierre de orden de reparacion donde se registra la fecha y hora de entrega
  6. el sistema debe contar con un sistema de seguimiento donde el cliente consulte el estado de la reparacion
  7. el sistema debe proporcionar un historial mecanic del vehiculo
