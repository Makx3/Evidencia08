# Evidencia08: Caso - Tienda Online (e-shop)

# Objetivo: desarrollar un diagrama de clases UML a partir de la descripción de un contexto problema, en particular para un sistema de compras en línea.

# Contexto:

El objetivo es representar los elementos del dominio problema (ej: cliente, usuario web, cuenta, carrito de compras, producto, pedido, pago, etc.) y las relaciones entre ellos. Podría utilizarse como un elemento común entre analistas del negocio, ejecutivos comerciales y desarrolladores de software.

Cada cliente está vinculado exactamente a una cuenta, una cuenta no puede existir sin un cliente asociado.

Un carrito de compras está asociado a una única cuenta, dicho carrito no puede existir sin estar vinculado a una cuenta.

El cliente puede registrarse como usuario de la web para poder comprar artículos en línea. No se requiere que el cliente sea obligatoriamente un usuario de la web para hacer las compras (las compras también se pueden realizar por otros medios, ej: teléfono o mediante pedidos desde catálogos). El usuario web puede estar en uno de los siguientes estados: nuevo, activo, bloqueado temporalmente o prohibido, y estar vinculado a un carrito de compras.

La cuenta también esta compuesta de los pedidos de los clientes. Es posible que el cliente no tenga pedidos. Cada pedido puede referirse a varios medios de pago o posiblemente ninguno. Cada medio pago está relacionado exactamente con una cuenta.


Cada pedido tiene el estado actual del pedido. Dichos estados pueden ser: nuevo, creado, despachado, recibido, cerrado. Tanto el pedido como el carrito de la compra están asociados con familias de productos que estás asociados a un producto específico. Cada familia de productos está relacionado exactamente con un producto. Un producto puede estar asociado a muchas familias de productos o a ninguno.

# Desarrollo 
1.) Identifique las principales clases del contexto descrito.

R: Las clases dentro de la problematica serian: Cliente, Cuenta y Carrito de compras.

2.) Identifique las clases que se relacionen entre sí, y el tipo de relación identificada.

3.) Para las relaciones que se requiera, identifique las multiplicidades asociadas.

4.) Construya una primera versión de su diagrama de clases, usando Visual Paradigm.


##Diagrama:

![image](https://github.com/Makx3/Evidencia08/assets/135442605/1f8759c8-c886-4d91-9c8f-bd93afe5da23)

##Codigo generado:

![image](https://github.com/Makx3/Evidencia08/assets/135442605/e6f75bc4-160a-4683-932d-f56242b0bc74)

![image](https://github.com/Makx3/Evidencia08/assets/135442605/8f241b0c-d9ea-44e3-92d5-533bebfaf498)

![image](https://github.com/Makx3/Evidencia08/assets/135442605/52bd3e9c-dba7-4707-8ee9-f1902a6a06c1)

![image](https://github.com/Makx3/Evidencia08/assets/135442605/2663f17e-7ebc-42eb-b4c5-a0a4ee1756ac)

![image](https://github.com/Makx3/Evidencia08/assets/135442605/e42f3f48-0082-46fd-bb6e-41f9a5afee4d)

![image](https://github.com/Makx3/Evidencia08/assets/135442605/f09f9386-0ef1-4ea1-8d7a-16084ab54b99)

![image](https://github.com/Makx3/Evidencia08/assets/135442605/4fbc7bb6-8259-45fb-94eb-c7e4841c3f1c)

![image](https://github.com/Makx3/Evidencia08/assets/135442605/0075bb25-65e0-4050-a6db-ae6f0dedbd7a)




