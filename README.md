sass/
|
|– base/
|   |- _typography.scss          // Estilos para tipografías
|   |- _reset.scss               // Reset de estilos básicos
|   |- _utilities.scss           // Clases de utilidad y variables globales
|   └- _global.scss              // Estilos globales del sitio
|
|– components/
|   |- _buttons.scss             // Estilos para botones
|   |- _cards.scss               // Estilos para tarjetas
|   |- _forms.scss               // Estilos para formularios
|   └- _header.scss              // Estilos para el encabezado
|
|– layout/
|   |- _grid.scss                // Estilos para el sistema de rejilla
|   |- _navigation.scss          // Estilos para la barra de navegación
|   |- _sidebar.scss             // Estilos para la barra lateral
|   |- _main.scss                // Estilos para el contenido principal
|   └- _footer.scss              // Estilos para el pie de página
|
|– pages/
|   |- _home.scss                // Estilos para la página de inicio
|   |- _about.scss               // Estilos para la página "Acerca de"
|   |- _contact.scss             // Estilos para la página de contacto
|   └- _blog.scss                // Estilos para la página de blog
|
|– themes/
|   |- _theme-default.scss       // Estilos para el tema por defecto
|   |- _theme-dark.scss          // Estilos para el tema oscuro
|   └- _theme-light.scss         // Estilos para el tema claro
|
|– utils/
|   |- _variables.scss           // Variables globales
|   |- _functions.scss           // Funciones útiles
|   └- _mixins.scss              // Mixins útiles
|
|– vendors/
|   |- _bootstrap.scss           // Estilos de Bootstrap
|   └- _jquery-ui.scss           // Estilos de jQuery UI
|
`– style.scss                    // Archivo principal que importa todos los demás archivos de Sass




// Variables y mixins globales
@import 'utils/variables';
@import 'utils/mixins';

// Estilos base
@import 'base/typography';
@import 'base/reset';
@import 'base/utilities';
@import 'base/global';

// Componentes
@import 'components/buttons';
@import 'components/cards';
@import 'components/forms';
@import 'components/header';

// Diseño
@import 'layout/grid';
@import 'layout/navigation';
@import 'layout/sidebar';
@import 'layout/main';
@import 'layout/footer';

// Estilos de página
@import 'pages/home';
@import 'pages/about';
@import 'pages/contact';
@import 'pages/blog';

// Temas
@import 'themes/theme-default';
@import 'themes/theme-dark';
@import 'themes/theme-light';

// Librerías de terceros
@import 'vendors/bootstrap';
@import 'vendors/jquery-ui';
