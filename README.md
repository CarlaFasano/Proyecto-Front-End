Proyecto desarrollado para el curso de Front-End. Se trata de una tienda de libros que contiene varias secciones orientadas a una página de compras básica, tales como: un header con enlaces útiles para navegación, compras, contacto y cuenta de usuario; una sección hero con una presentación simple; un main con una sección de productos destacados, una para navegar por los productos por categoría, y otra con reseñas de clientes; un footer que contiene algunos enlaces de utilidad para la interacción del usuario con el emprendimiento.

___________________________________________________

Sobre el uso de Formspree:

¿Cómo configuré Formspree?
Luego de haber creado el código HTML para el formulario con la etiqueta <form> y de agregar los campos de contacto usando <label>, creé en la página web de Formspree un formulario mediante la opción Add New --> New Form. Luego copié la URL del Form Endpoint y volví a mi código. Dentro de la etiqueta de apertura <form>, agregué el atributo action y pegué allí la URL de Formspree. Junto a este, agregué method="post" que permite enviar el formulario de forma invisible para el usuario, sin que los datos del formulario aparezcan en la URL.

¿Por qué es útil?
Formspree es útil porque permite recibir los datos de un formulario HTML (como nombre, correo y mensaje) directamente por email, sin necesidad de crear ni configurar un servidor backend que procese y envíe esa información. Esto simplifica mucho el desarrollo, especialmente en proyectos simples o estáticos donde no se cuenta con un back-end propio.
