Proyecto desarrollado para el curso de Front-End.

___________________________________________________

Sobre el uso de Formspree:

¿Cómo configuré Formspree?
Luego de haber creado el código HTML para el formulario con la etiqueta <form> y de agregar los campos de contacto usando <label>, creé en la página web de Formspree un formulario mediante la opción Add New --> New Form. Luego copié la URL del Form Endpoint y volví a mi código. Dentro de la etiqueta de apertura <form>, agregué el atributo action y pegué allí la URL de Formspree. Junto a este, agregué method="post" que permite enviar el formulario de forma invisible para el usuario, sin que los datos del formulario aparezcan en la URL.

¿Por qué es útil?
Formspree es útil porque permite recibir los datos de un formulario HTML (como nombre, correo y mensaje) directamente por email, sin necesidad de crear ni configurar un servidor backend que procese y envíe esa información. Esto simplifica mucho el desarrollo, especialmente en proyectos simples o estáticos donde no se cuenta con un backend propio.