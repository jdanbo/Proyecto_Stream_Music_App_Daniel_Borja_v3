MusicStream

Descripcion del Proyecto
Este proyecto consiste en el desarrollo de una plataforma web para Acme Records. El objetivo es crear una interfaz hibrida que combina las funciones de streaming de musica con una tienda digital tradicional. La aplicacion busca unificar la experiencia del usuario, permitiendo escuchar previas y comprar albumes completos en una misma sesion, todo bajo un sistema de diseño Dark Mode para reducir la fatiga visual.

Vistas Implementadas
El proyecto incluye la maquetacion de las siguientes secciones principales:
1. Storefront & Discovery: La pagina de inicio que invita a la exploracion con banners y listas de novedades.
2. Detalle de Album: Vista de producto que muestra la portada, lista de canciones y opciones de compra.
3. Reproductor Inmersivo: Una interfaz dedicada a la reproduccion con controles y visualizacion del arte del album.
4. Carrito y Checkout: Flujo de compra que incluye el resumen del pedido y formularios de pago y facturacion.
5. Perfil y Confirmacion: Mensaje de exito tras la compra y visualizacion de la biblioteca personal del usuario.

Tecnologias Utilizadas
El desarrollo se realizo cumpliendo las siguientes especificaciones tecnicas:
1. HTML5 Semantico para la estructura del contenido.
2. CSS3 Puro para los estilos, sin uso de preprocesadores.
3. Diseño Responsivo con enfoque Mobile First, adaptable desde pantallas de 375px hasta escritorio.
4. No se utilizaron Frameworks (como Bootstrap o Tailwind) ni JavaScript, toda la logica es visual y estatica.

Estructura del Proyecto
Los archivos estan organizados en carpetas especificas para hojas de estilo (main, layout, components, views), recursos (img, icons) y los archivos HTML correspondientes a cada vista.

-----------------------------------------------------------------------------------------------------------------------

Music Stream App

Structure Needed
css
    main.css #Reset, variables (colores, fuentes), tipografia base
    layout.css #Grid systems, Header, sidebar, footer
    components.css #botones, cards, inputs, tablas
    views #Estilos por pagina
        store.css
        player.css
        checkout.css

assets
    img #portadas de algum, avatares
    icons #iconos SVG (play, pause, cart, search)

index.html #Storefront HOME
album-detail.html #Detalle del producto
player.html #Reproductor inmersivo
cart.html #carrito
checkout.html #pasarela de pago
sucess.html #confirmacion y libreria
README.md #documentacion

-------------------------------------

Elementos Necesarios: 

Iconos
    Player
        Play - assets/icons/P-PLAY.png
        Pause - assets/icons/P-PAUSE.png
        Skip 1 - assets/icons/P-SKIPRIGHT.png
        Skip 2 - assets/icons/P-SKIPLEFT.png
        Randomize - assets/icons/P-RANDOMIZE.png
        Loop - assets/icons/P-LOOP.png
        volume - assets/icons/P-VOLUME.png
        Fullscreen - assets/icons/P-FULLSCREEN.png
        Heart (favorite) - assets/icons/P-HEART.png

    NavBar    
        Search - assets/icons/NAV-SEARCH.png
        Cart - assets/icons/NAV-CART.png
        Notification Bell - assets/icons/NAV-NOTIFICATION.png


    ProductPage
        Share - assets/icons/PROD-SHARE.png
        Wishlist (heart) - assets/icons/PROD-WISHLIST.png
        Tracklist (watch) - assets/icons/PROD-TRACKLIST.png
        

    SideBar
        New Releases - assets/icons/SIDE-NEW.png
        Genres - assets/icons/SIDE-GENRES.png
        Top Charts - assets/icons/SIDE-TOP.png
        Artists - assets/icons/SIDE-ARTIST.png

    Cart/CHeckout
        Trash - assets/icons/CART-TRASH.png
        + - assets/icons/CART-PLUS.png
        - - assets/icons/CART-MINUS.png
        Lock - assets/icons/CART-LOCK.png
        Payment (card) - assets/icons/CART-PAYMENT.png

    My music(Confirmacion)
        Recently - assets/icons/CONFI-RECENTLY.png
        My albums - assets/icons/CONFI-MYALBUMS.png
        Liked (heart) - assets/icons/PROD-WISHLIST.png
        Check (green) - assets/icons/CONFI-CHECK.png

-------------------------------------------

Images
    Album Covers
        New Albums x 5 - assets/img/cover- (1 to 5)
        Top Selling x 5 - assets/img/cover- (6 to 10)
    Editors Pick Album - assets/img/cover-11

    Payment methods
        Visa - assets/img/visa.png
        Mastercard - assets/img/mastercard.png
        Cash - assets/img/cash.jpg

    Profile picture - assets/img/PROFILEPICTURE.png

    Music Stream Logo - assets/img/logoMS.png

Color Palette
    Main #0F172A
    Secondary #81C14B
    Accents #FF3CC7 #9CFFFA