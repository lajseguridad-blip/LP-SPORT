# LP SPORT

Tienda online de indumentaria deportiva femenina y masculina.

## Versión 1
- Diseño responsive premium negro, blanco y lima.
- Catálogo Mujer / Hombre.
- Carrito.
- Checkout demo.
- Gift Card.
- Botón de WhatsApp.
- Seguimiento de pedidos.
- Panel admin en `/admin.html`: productos, precios, proveedores y estados de pedidos.

## Estado técnico
Esta primera versión funciona completamente en front-end con localStorage para validar experiencia, estética y flujo comercial. Para producción real hay que incorporar backend/base de datos, autenticación segura de `/admin`, stock centralizado, almacenamiento de imágenes, integración oficial de Mercado Pago y API logística. Las credenciales privadas nunca deben guardarse en este repositorio público.

## Próxima etapa sugerida
Supabase/Postgres + autenticación de administrador + Mercado Pago Checkout API + servicio de correo/logística + dominio propio.
