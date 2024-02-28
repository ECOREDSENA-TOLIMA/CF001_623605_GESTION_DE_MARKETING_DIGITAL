<template lang="pug">
.curso-main-container.pb-3.tema1
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Mercadeo 

    .row.mb-4
      .col-md-9
        p Según Kotler y Keller (2012), el mercadeo busca la identificación y satisfacción de las necesidades del ser humano de forma rentable. La empresa eBay, al reconocer que sus clientes no podían ubicar unos artículos deseados por ellos, se dio a la tarea de crear un foro para atenderlos de manera <em>online.</em> La empresa IKEA, al darse cuenta de que sus clientes deseaban buenos muebles con precios más bajos, ajusto sus costos. Las dos empresas entendieron el mercadeo y la inteligencia de <em>marketing,</em> convirtiendo una necesidad individual o social en una oportunidad empresarial que dio como resultado su rentabilidad.
        p Para ampliar el concepto de mercado, el siguiente video detalla elementos de valor y aporte para este ítem. 

      .col-md-3
        figure
          img(src='@/assets/curso/temas/tema1/img-1.svg', alt='Imagen decorativa')
    
    figure.mb-4
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/lpS6sY69J1E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    p.mb-5 El mercadeo, para definirlo desde el contexto social, muestra una función basada en la sociedad; por ejemplo, el rol del mercadeo es la entrega de un modelo de vida de mejor calidad. Por eso, es un proceso social en el que existen grupos de personas e individuos que logran lo que necesitan y desean a través de la creación, comercio e intercambio de productos de valor para ellos. Los especialistas de mercadeo promocionan 10 tipos principales de artículos, a saber: 

    .BGIMG01.p-4.mb-5
      SlyderB.mb-5(:datos="datosSlyder")

    .row.justify-content-center.align-items-center.mb-3
      .col-10(data-aos="fade-down-right")
        p Por otro lado, también están los que comercializan, o sea, los especialistas en mercadeo, que en realidad son especialistas en búsqueda de respuestas de un cliente potencial, como, por ejemplo, llamar la atención, comprar, votar, donar, suscribirse. 
        p.mb-5 Son estrategas que poseen la capacidad de estimular la compra de los productos, pero esa es una visión limitada de lo que hacen. Por eso, los especialistas en mercadeo se responsabilizan de administrar la demanda, buscando la influencia en el nivel, de coordinar tiempo y componer la demanda para dar cumplimiento a las metas pactadas por la empresa. Los siguientes son los ocho estados de demanda.

    .row.justify-content-center.mt-5
      SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-1.png' alt='AvatarTop')
          p <strong>Demanda negativa</strong> 
          p Producto que no es tenido en cuenta por el consumidor, le desagrada.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-2.png' alt='AvatarTop')
          p <strong>Demanda inexistente</strong> 
          p El consumidor no es consciente o no tiene interés en el producto.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-3.png' alt='AvatarTop')
          p <strong>Demanda latente</strong> 
          p El consumidor compra con una necesidad fuerte que no la satisface ningún otro producto.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-4.png' alt='AvatarTop')
          p <strong>Demanda decreciente</strong> 
          p El consumidor compra el producto, cada vez con menor frecuencia.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-5.png' alt='AvatarTop')
          p <strong>Demanda irregular</strong> 
          p Compras que pueden variar según fechas o eventos especiales.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-6.png' alt='AvatarTop')
          p <strong>Demanda completa</strong> 
          p El consumidor compra de forma adecuada todos los productos que se ofrecen en el mercado.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-7.png' alt='AvatarTop')
          p <strong>Demanda excesiva</strong> 
          p Cuando hay una mayor cantidad de consumidores que quieren adquirir el producto que los que se pueden satisfacer.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-8.png' alt='AvatarTop')
          p <strong>Demanda malsana </strong> 
          p El consumidor se ve atraído por productos que poseen resultados sociales indeseables. 

    Separador 

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 <em>Marketing</em> en entornos digitales 

    p.mb-5 Según Xie y Min (2019), el objetivo del <em>marketing</em> digital es aprovechar internet y demás formas de promoción <em>online</em> para comunicarse con el público objetivo de forma rentable, y permitiendo un trabajo colaborativo con socios empresariales con los que pueda existir un interés en común. Cuando se habla de <em>marketing</em> digital, primero se habla de estrategias y herramientas alojadas en la <em>web,</em> y segundo, se habla también de las pantallas digitales a través de computadores de escritorio, portátiles, celulares, <em>tablets,</em> televisores, consolas de videojuegos y relojes <em>smart.</em> 

    .row.mb-5
      .col-md-4.mb-3
        figure
            img(src='@/assets/curso/temas/tema1/img-3.svg', alt='')
      .col-md-8
        p Es uno de los pilares en los que, por ejemplo, las agencias de turismo deben apoyarse si desean conquistar una parte de las ventas realizadas por una comunidad de turistas 2.0 que están en búsqueda de un viaje a través de internet. En estos entornos digitales se puede buscar información sobre los destinos deseados y tener una asesoría en cuanto a los precios. Esta información y asesoría es presentada por agencias de viajes <em>online</em> u OTA (On Line Travel Agency).
        .row
          .col-lg-12
            .cajon.color-secundario.p-4.mb-4(style="background-color:#FFFBE5")
              p Algo muy importante que tiene la <em>web</em> es que los clientes pueden encontrar una gran cantidad de opciones, desde sitios de destino hasta precios, que pasan desde los costosos hasta los económicos. Por eso, la importancia de promocionarse en entornos digitales.  

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Las 4F del <em>marketing</em> digital

    p.mb-5 El <em>marketing</em> digital se basa en 4F, que vienen siendo variables compuestas por una estrategia de mercadeo efectiva, como lo hace el <em>marketing mix</em> y sus 4P: <strong>precio, producto, plaza e impulsión.</strong> En el caso de las 4F, se incluyen <strong>flujo, funcionalidad, <em>feedback</em> y fidelización,</strong> las cuales se detallan a continuación. 

    .BGIMG01.p-5.mb-5
      SlyderA(tipo="b")
        .row
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 Flujo
            p Tiene que ver con la multiplataforma o transversalidad. El cliente debe sentirse atraído por la interactividad generada en el sitio <em>web</em> de tal manera que le llame y se interese por la marca y sus productos. Actualmente, los sitios <em>web</em> buscan ser lo más precisos posibles para exponer y ordenar los botones de búsqueda (por lo general en la página de Inicio) para que los clientes encuentren fácilmente lo que desean (un producto, un servicio, una ciudad destino, etc.). 

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema1/img-11.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 Funcionalidad
            p La navegación en el sitio <em>web</em> tiene que ser fácil e intuitiva, de lo contrario, el cliente termina abandonándolo.

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema1/img-12.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 <em>Feedback</em>
            p La interacción con los clientes es vital para construir una excelente relación con ellos. La reputación lograda es clave para conseguir confianza y una comunicación bidireccional. Se recomienda ser humildes, humanos, transparentes y sinceros. Para lograr el <em>feedback</em> se puede dar oportunidad a los clientes de dejar comentarios, iniciar un <em>chat online</em> de asesoría, o aceptar una suscripción para recibir el envío de boletines u ofertas por <em>e-mail.</em>

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema1/img-13.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 Fidelización
            p Luego de entablar una relación con los clientes, se deben fidelizar, la idea es que tengan compromiso por la marca y cautivarlos ofreciendo contenidos de interés. Esta variable es de vital importancia para el futuro empresarial. Hoy, el foco es el cliente, y por eso la estrategia digital debe contener espacios selectos en donde él interactúe, optimizando los resultados en motores de búsqueda, influenciando opiniones e incluso <em>influencers,</em> y estudiando la información que los diferentes canales digitales suministren para mejorar el rendimiento de las acciones puestas en marcha. 

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema1/img-14.png', alt='Texto que describa la imagen')

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 El plan de <em>marketing</em>

    p.mb-5 Para Kotler y Keller (2012), el plan de <em>marketing</em> es una herramienta de gestión empresarial que puede garantizar a las compañías la rentabilidad, siempre y cuando su desarrollo y ejecución sea eficiente. Los estrategas de mercadeo deben tener en cuenta que los objetivos comerciales deben ser coherentes con los objetivos generales de la marca. Por eso, en el desarrollo del plan de <em>marketing</em> se deben elegir muy bien las estrategias y el plan de acción que encamine a la empresa a lograr los objetivos pactados. Algunos de los beneficios que suministra un plan de mercadeo son: 

    .row.justify-content-center.align-items-center.mb-3
      .col-10(data-aos="fade-down-right")
        .tarjeta--container.row.mb-5
          .col-md.tarjeta.color-primario.p-4(style="background-color:#E3ECF7")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-9.svg', alt='Texto que describa la imagen')
              
            p Fortalecer la toma de decisiones comerciales y de mercadeo. 

          .col-md.tarjeta.color-acento-botones.p-4(style="background-color:#FFFBE5")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-10.svg', alt='Texto que describa la imagen')
              
            p(style="color:#000") Forjar un programa de acciones para la actividad comercial. 

          .col-md.tarjeta.color-acento-contenido.p-4(style="background-color:#E4FDFB")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-11.svg', alt='Texto que describa la imagen')
              
            p(style="color:#000") Facilitar la realización de las acciones comerciales y de mercadeo. 

        .bloque-texto-f.color-acento-contenido.pt-4.px-5.mb-5
          .bloque-texto-f__comillas
            i.fas.fa-quote-left
            i.fas.fa-quote-right
          h4.text-regular.bloque-texto-f__texto Con base en las ventajas que suministran, las marcas que deseen optimizar su eficacia y competencia deben delinear y tramitar planes de mercadeo que brinden pilares como el análisis, la planeación, la gestión y la revisión de las acciones comerciales, de forma clara y precisa. Si estos cuatro pilares son desarrollados estratégicamente, las marcas pueden hallar la solución a muchos de sus inconvenientes de gestión y obtener la obtención de sus objetivos de rentabilidad.
          .bloque-texto-f__autor.mb-3
            h3.mb-0 - Kotler y Keller, 2012
          .bloque-texto-f__avatar
            .bloque-texto-f__avatar__img
              img(src='@/assets/curso/temas/tema1/retrato.png', alt='Texto que describa la imagen')

        .row.mb-4(data-aos="fade-right")
          .col-4
            img(src='@/assets/curso/temas/tema1/img-15.png')
          .col-8
            p Rivelli (2019) afirma que la elaboración de un plan de mercadeo es el resultado de un minucioso proceso en el que cada fase va a estar directamente conectada con las demás, con el fin de la obtención final del documento. El liderazgo en la preparación de un plan de mercadeo depende de cada marca y de su organización interna. Por lo general, las Pymes se centran en la figura de los responsables de mercadeo o del mismo gerente, si la compañía es pequeña. 
            p En el mercado se pueden encontrar herramientas de <em>software</em> para desarrollar planes de mercadeo. Estas herramientas se diseñan de forma especial para Pymes y pequeños empresarios, que, a corto plazo y de una forma sencilla, podrán aprender a elaborar y revisar sus propios planes de mercadeo efectiva y rentablemente.

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Etapas del plan de <em>marketing online</em>

    p Una vez establecido el plan de mercadeo tradicional, se ponen en marcha actividades que se pueden desarrollar desde internet. Inicialmente, tener presencia en la <em>web</em> es relativamente fácil, analizado desde lo técnico y lo económico. En segunda instancia, ser efectivo con la estrategia de mercadeo digital es más complejo, puesto que el simple hecho de crear una <em>web</em> no es suficiente para lograr visibilidad; se requiere de planear una estrategia, con objetivos delimitados de manera perfecta y con herramientas y vías para hacerlos realidad. 
    p.mb-5 Se desarrollan a continuación las etapas del plan de mercadeo digital.

    .row.justify-content-center.align-items-center.mb-3
      .col-10(data-aos="fade-down-right")
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row(titulo="Etapa 1. Análisis y diagnóstico de la situación")
            .col-md-12.mb-4.mb-md-0
              p Análisis juicioso de los entornos interno y externo de la empresa, que se debe materializar en el DOFA, que es un estudio indefectible en el diagnóstico de la situación empresarial. En esta etapa se lleva a cabo una aguda investigación en las siguientes tres áreas: 
              .tarjeta.tarjeta.p-4.mb-3(style="background-color:#FFFF")
                .row
                  .col-3
                    img(src='@/assets/curso/temas/tema1/img-16.png')
                  .col-9
                    p <strong>Área 1 - Empresa</strong>
                    p Conseguir información sobre la propia estructura interna, examinando:
                    ul.lista-ul.mb-3
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | El DOFA. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | La creación y diseño del sitio <em>web.</em> 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Los objetivos del proyecto digital. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | El talento humano que conformará el proyecto. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | La descripción minuciosa de los contenidos digitales y funciones del sitio <em>web.</em> 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | El valor agregado que brinda el proyecto para el público objetivo. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | El método de análisis con el que puede conseguir información importante sobre el sitio <em>web.</em> 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | El posicionamiento <em>web.</em> 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Los propios valores y la filosofía de la marca digital. 

              .tarjeta.tarjeta.p-4.mb-3(style="background-color:#FFFF")
                .row
                  .col-3
                    img(src='@/assets/curso/temas/tema1/img-17.png')
                  .col-9
                    p <strong>Área 2 - Competencia</strong>
                    p Obtener toda la información posible sobre la competencia en internet: 
                    ul.lista-ul.mb-3
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | El sitio <em>web</em> de la competencia y las diferencias con la marca. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Las formas de promoción y distribución.  
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Los productos o servicios que la competencia ofrece. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | El precio que fija la competencia a sus productos o servicios.  
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | El portafolio digital de productos que ofrecen. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Los métodos de pago que usan. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | La publicidad digital que diseñan. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Las palabras clave usadas por la competencia para posicionarse en motores de búsqueda. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Las fortalezas y debilidades más destacadas. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Los objetivos y estrategias que han planificado.  

              .tarjeta.tarjeta.p-4.mb-3(style="background-color:#FFFF")
                .row
                  .col-3
                    img(src='@/assets/curso/temas/tema1/img-18.png')
                  .col-9
                    p <strong>Área 3 - Mercado</strong>
                    p Delimitar el público objetivo al que se dirigen, para aproximarse mejor a los intereses y expectativas de los clientes potenciales:  
                    ul.lista-ul.mb-3
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Necesidades y deseos del público objetivo de la marca.
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Tamaño del mercado. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Satisfacción de necesidades y deseos de los clientes a través del sitio <em>web.</em>
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Comportamiento digital de los usuarios y otras <em>web</em> que transitan. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Productos o servicios que son buscados o comprados por el público objetivo. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Edad, estatus socioeconómico, lugar de residencia. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Si participan en comunidades virtuales. 

              p De esta forma, se consolidan las tres áreas correspondientes a la etapa 1: análisis y diagnóstico de la situación.

          .row(titulo="Etapa 2. Definición de objetivos a alcanzar")
            .col-md-12.mb-4.mb-md-0
              p Se deben definir los objetivos que guiarán las acciones de todas las áreas de la empresa, por eso, estos objetivos están enmarcados dentro de los objetivos generales determinados por la compañía. Se sugiere que antes exista un análisis que responda: 

              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-10.desktop
                  .titulo-sexto.color-acento-contenido
                    p.titulo.pb-0.mb-0 #[b Figura 1.] <em>Definición de objetivos a alcanzar.</em>
                  figure
                    img(src='@/assets/curso/temas/tema1/img-19-1.svg', alt='Definición de objetivos a alcanzar. Conlleva a realizar un análisis DOFA, áreas relacionadas, dilucida los objetivos a alcanzar, obstáculos y pertinencia de los objetivos definidos.')

              .row.mt-2.mb-3
                .col-10.col-md-10.col-lg-12.movil
                  .titulo-sexto.color-acento-contenido
                    p.titulo.pb-0.mb-0 #[b Figura 1.] <em>Definición de objetivos a alcanzar.</em>
                  figure
                    img(src='@/assets/curso/temas/tema1/img-19-2.svg', alt='Definición de objetivos a alcanzar. Conlleva a realizar un análisis DOFA, áreas relacionadas, dilucida los objetivos a alcanzar, obstáculos y pertinencia de los objetivos definidos.')

              p En el plan de mercadeo digital se deben establecer los objetivos cuantitativos y cualitativos que va a perseguir la marca con la creación del sitio <em>web.</em> Así, cada marca podrá elegir los objetivos más convenientes, con el fin de lograr la rentabilidad esperada en la planeación estratégica. 
              p Estos objetivos dependen de las características del producto ofrecido en la <em>web</em> y, se pueden basar en: 

              .tarjeta.tarjeta.p-4.mb-3(style="background-color:#FFFF")
                .row
                  .col-3
                    img(src='@/assets/curso/temas/tema1/img-20.png')
                  .col-9
                    p <strong>Área 1 - Empresa</strong>
                    p Conseguir información sobre la propia estructura interna, examinando:
                    ul.lista-ul.mb-3
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Creación de marca. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Posicionamiento <em>web.</em> 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Atención al cliente. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Distribución y logística digitales. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Ventajas competitivas. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Rentabilidad.
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Aumento del porcentaje de venta. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Estatus de facturación. 

          .row(titulo="Etapa 3. Elección y desarrollo de las estrategias de <em>marketing</em>")
            .col-md-12.mb-4.mb-md-0
              p Esta etapa sirve para la consecución de los objetivos. Para la definición de las estrategias se deben tener en cuenta las “4P” desde lo digital que, mezcladas de la manera más provechosa, darán como resultado en una estrategia coherente con el producto ofrecido en la <em>web.</em> 
              p El listado de temas para considerar en la formulación de estrategias es el siguiente:
              .tarjeta.tarjeta.p-4.mb-3(style="background-color:#FFFF")
                .row
                  .col-3
                    img(src='@/assets/curso/temas/tema1/img-21.png')
                  .col-9
                    p <strong>Estrategia de producto</strong>
                    ul.lista-ul.mb-3
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Creación del catálogo digital. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Información importante sobre los productos. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Sustitución y modificación de productos inoportunos. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Garantías, servicio y atención posventa. 

      

              .tarjeta.tarjeta.p-4.mb-3(style="background-color:#FFFF")
                .row
                  .col-3
                    img(src='@/assets/curso/temas/tema1/img-22.png')
                  .col-9
                    p <strong>Estrategia de precio</strong>
                    ul.lista-ul.mb-3
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Precios de venta de los productos. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Cambios de los precios respecto al producto digital. 

                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Métodos de pago digitales. 

                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Sistemas seguros de pago. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Descuentos, ofertas, promociones. 


              .tarjeta.tarjeta.p-4.mb-3(style="background-color:#FFFF")
                .row
                  .col-3
                    img(src='@/assets/curso/temas/tema1/img-23.png')
                  .col-9
                    p <strong>Estrategia de distribución</strong>
                    ul.lista-ul.mb-3
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Planeación de ventas.
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Tener la tienda virtual. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Precisar <em>stocks</em> y métodos de almacenamiento. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Costos de almacenamiento y rotura de <em>stocks.</em> 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Técnicas de entrega y distribución de productos. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Distribución del producto justo a tiempo.  

              .tarjeta.tarjeta.p-4.mb-3(style="background-color:#FFFF")
                .row
                  .col-3
                    img(src='@/assets/curso/temas/tema1/img-24.png')
                  .col-9
                    p <strong>Estrategia de distribución</strong>
                    ul.lista-ul.mb-3
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | SEO. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | SEM. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | <em>E-mail marketing.</em>
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Relaciones públicas.
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Publicidad digital. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Mercadeo viral. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Comunidades virtuales. 

          .row(titulo="Etapa 4. Planes de acción")
            .col-md-4
              figure
                img(src='@/assets/curso/temas/tema1/img-25.png', alt='Texto que describa la imagen')

            .col-md-8.mb-4.mb-md-0
              p Una vez desarrolladas las estrategias, se necesitará desplegar los planes de acción con los cuales se van a ejecutar dichas estrategias. Es necesario saber cómo se van a desarrollar las estrategias, en qué momento y quiénes serán los responsables de gestionarlas. Se sugiere usar un cronograma donde se puedan ver claramente las estrategias y sus respectivos planes de acción (con fechas y responsables). 
          
          .row(titulo="Etapa 5. Presupuesto de <em>marketing</em> y control de resultados")
            .col-md-4
              figure
                img(src='@/assets/curso/temas/tema1/img-26.png', alt='Texto que describa la imagen')

            .col-md-8.mb-4.mb-md-0
              p Las fases ya mencionadas deben ir acompañadas de un presupuesto y de medidas de control y seguimiento, de forma que económicamente se tenga claro en dónde se debe invertir dinero y, por otro lado, de manera frecuente, detectar desviaciones o anomalías que se puedan corregir a tiempo. 

        p Las Pymes deben tener en cuenta que, una vez realizado el trabajo anterior, deben contar con recursos económicos con los que pueda llevar a cabo el plan de mercadeo digital. El modelo económico y financiero de este presupuesto debe contener datos importantes como son: 

        .row.justify-content-center.align-items-center.mb-4
          .col-10(data-aos="fade-down-right")
            .tarjeta.tarjeta.p-4.mt-4(style="background: linear-gradient(0deg,#E3ECF7, #EEF5FF)")(data-aos="flip-up")
              .row.justify-content-center.align-items-center 
                .col-lg-5.mb-3
                  figure(data-aos="fade-right")
                    img(src='@/assets/curso/temas/tema1/decorador-12.svg', alt='Texto que describa la imagen')
                .col-lg-6
                  ul.lista-ul.mb-3
                    li.mb-0
                      i.fas.fa-circle(style="color:#33ECE0")
                      | Ingresos previstos a corto y largo plazo. 
                    li.mb-0
                      i.fas.fa-circle(style="color:#33ECE0")
                      | Origen de los ingresos. 
                    li.mb-0
                      i.fas.fa-circle(style="color:#33ECE0")
                      | Previsión de beneficios. 
                    li.mb-0
                      i.fas.fa-circle(style="color:#33ECE0")
                      | Previsión de flujos de tesorería. 
                    li.mb-0
                      i.fas.fa-circle(style="color:#33ECE0")
                      | Financiación necesaria. 
                    li.mb-0
                      i.fas.fa-circle(style="color:#33ECE0")
                      | Amortización de la financiación. 
                    li.mb-0
                      i.fas.fa-circle(style="color:#33ECE0")
                      | Inversiones requeridas. 
                    li.mb-0
                      i.fas.fa-circle(style="color:#33ECE0")
                      | Planes de expansión. 

    p.mb-5 Además, los estrategas de mercadeo deben tener instrumentos de control que enseñarán si el plan de acción ha tenido el resultado esperado o, si se han encontrado desviaciones sobre los resultados previstos; por ello, se deben diseñar planes opcionales que ayuden a superar las posibles anomalías. En el momento en que aparezca una contingencia imprevista, las marcas deben estar dispuestas para dar respuesta a: 

    .row.justify-content-center.align-items-center.mb-3
      .col-10(data-aos="fade-down-right")
        .tarjeta--container.row.mb-5
          .col-md.tarjeta.color-primario.p-4(style="background-color:#E3ECF7")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-13.svg', alt='Texto que describa la imagen')
              
            p.text-center ¿Es un problema o un indicio de posible problema?

          .col-md.tarjeta.color-acento-botones.p-4(style="background-color:#FFFBE5")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-14.svg', alt='Texto que describa la imagen')
              
            p.text-center(style="color:#000") ¿Es un problema de la marca o del mercado al que pertenece? 

          .col-md.tarjeta.color-acento-contenido.p-4(style="background-color:#E4FDFB")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-15.svg', alt='Texto que describa la imagen')
              
            p.text-center(style="color:#000") ¿Es un problema que se puede solucionar? 

    Separador 

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2  Planeación estratégica

    p.mb-5 Kotler y Keller (2012) expresan que las estrategias y los planes creativos son los ingredientes clave del proceso de dirección de mercadeo y, además, son lo que pueden guiar las actividades de <em>marketing</em> de la empresa. El desarrollo correcto de la estrategia demanda tener disciplina y flexibilidad, por lo se recomienda que las marcas se adhieran a una estrategia, y mejorarla constantemente.
    
    .row.justify-content-center.align-items-center.mb-5
      .col-10(data-aos="fade-down-right")
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img-27.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Uno de los objetivos de las marcas es <strong>la entrega de valor para el público objetivo con un beneficio.</strong> En una economía tan competitiva, con públicos cada vez más informados y con muchas opciones, la marca solo puede ganar ajustando el proceso de entrega de valor y elegir, suministrar e informar un valor preferente. 

    p La visión tradicional del mercadeo es que la marca produce algo para venderlo; el mercadeo ocurre exactamente en el proceso de venta. Las marcas que tienen esta visión poseen más oportunidades de éxito en economías que se caracterizan por la escasez de productos, y donde los clientes no exigen por calidad, características o estilo. Pero, esta visión tradicional no funciona en economías donde encuentra distintos tipos de clientes, con deseos, percepciones, predilecciones y juicios de compra personales. La marca que compite de forma inteligente, diseña y entrega ofertas para mercados objetivo bien específicos. 
    p.mb-5 A continuación, se expone la descripción de cada una de las estrategias a implementar en este proceso, plan de mercadeo, planeación estratégica y planeación táctica. 

    .row.justify-content-center.align-items-center.mb-3
      .col-10(data-aos="fade-down-right")
        .tarjeta--container.row.mb-5
          .col-md.tarjeta.color-primario.p-4(style="background-color:#E3ECF7")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-16.svg', alt='Texto que describa la imagen')
              
            p.text-center El plan de mercadeo es la herramienta principal para administrar y coordinar el esfuerzo de <em>marketing;</em> el cual opera en dos niveles: estratégico y táctico. 

          .col-md.tarjeta.color-acento-botones.p-4(style="background-color:#FFFBE5")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-17.svg', alt='Texto que describa la imagen')
              
            p.text-center(style="color:#000") La planeación estratégica de mercadeo establece los mercados objetivos y la propuesta de valor de la marca de acuerdo al estudio de las mejores oportunidades de mercado.  

          .col-md.tarjeta.color-acento-contenido.p-4(style="background-color:#E4FDFB")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-18.svg', alt='Texto que describa la imagen')
              
            p.text-center(style="color:#000") La planeación táctica de mercadeo especifica las tácticas de <em>marketing</em> que contienen las características del producto, publicidad, comercio, adjudicación de precios, distribución y servicio.  
        
        p.mb-5 Como complemento al desarrollo de una adecuada y bien formulada planeación estratégica veamos en la siguiente imagen la secuencia correspondiente a la planificación, implementación y control. 

        .row.justify-content-center.align-items-center.mb-5
          .col-10.col-md-10.col-lg-12.desktop(data-aos="fade-right")
            .titulo-sexto.color-acento-contenido
              p.titulo.pb-0.mb-0 #[b Figura 2.] <em>Grafica planeación estratégica.</em>
            figure
              img.mb-3(src='@/assets/curso/temas/tema1/img-28-1.svg', alt='En la figura 2 se muestran tres pilares de la planeación estratégica, la planificación, la implementación y el control, estos actuan de manera cíclica con el objetivo de establecer la dirección de la organización y adaptarse al entorno.')

        .row.mt-5.mb-2
          .col-10.col-md-10.col-lg-12.movil(data-aos="fade-right")
            .titulo-sexto.color-acento-contenido
              p.titulo.pb-0.mb-0 #[b Figura 2.] <em>Grafica planeación estratégica.</em>
            figure
              img(src='@/assets/curso/temas/tema1/img-28-2.svg', alt='En la figura 2 se muestran tres pilares de la planeación estratégica, la planificación, la implementación y el control, estos actuan de manera cíclica con el objetivo de establecer la dirección de la organización y adaptarse al entorno.') 

        .row.justify-content-center.align-items-center.mb-4
          .col-12(data-aos="fade-down-right")
            .cajon.color-primario.p-4(style="background-color:#E3ECF7")
              p La consolidación de una planeación estratégica implica integrar a toda la organización y hacer énfasis en unos niveles puntuales como lo son la misión corporativa, establecer unidades estratégicas de negocios, asignar recursos a cada unidad estratégica de negocios y evaluar las oportunidades de crecimiento. Estos elementos se describen de forma detallada a continuación.

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Definir la misión corporativa

    p.mb-5 Una marca vive para alcanzar algo: fabricar autos, prestar servicios, construir casas, etc. La misión empresarial puede ir cambiando con el paso del tiempo, de tal forma que se puedan aprovechar nuevas oportunidades o para dar respuesta a nuevos contextos del mercado. Se deben hacer las siguientes preguntas a la hora de definir la misión empresarial: 

    .row.justify-content-center.align-items-center.mb-5
      .col-10.col-md-10.col-lg-12.desktop(data-aos="fade-right")
        figure
          img.mb-3(src='@/assets/curso/temas/tema1/img-29-1.svg', alt='Se revelan 5 preguntas: 1- ¿Qué muestra el análisis DOFA? 2- ¿En qué áreas se encuentra y en qué áreas desea estar la empresa? 3- ¿Hay recursos suficientes para lograr los objetivos trazados? 4- ¿Los objetivos son realistas y se pueden alcanzar? 5- ¿Temporalmente cuál es el límite para alcanzarlos? ')

    .row.mt-5.mb-2
      .col-10.col-md-10.col-lg-12.movil(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/img-29-2.svg', alt='Se revelan 5 preguntas: 1- ¿Qué muestra el análisis DOFA? 2- ¿En qué áreas se encuentra y en qué áreas desea estar la empresa? 3- ¿Hay recursos suficientes para lograr los objetivos trazados? 4- ¿Los objetivos son realistas y se pueden alcanzar? 5- ¿Temporalmente cuál es el límite para alcanzarlos? ')

    .row.justify-content-center.align-items-center.mb-3
      .col-10(data-aos="fade-down-right")
        p Parecen fáciles de responder, pero, en realidad, son las más complicadas que la marca responderá en su historia. 
        p Poseer una misión clara e inteligente suministra un sentido cooperado de propósito, dirección y oportunidad, por lo que debe ser compartida con los empleados e incluso clientes. Una buena misión debe conllevar a una visión que proporcione una dirección empresarial para los siguientes, 5, 10 o 20 años. Sony, por ejemplo, quería ofrecer un equipo de sonido personal y portátil, creando así el walkman y el reproductor de CD portátil.
        p.mb-5 Las mejores declaraciones de misión tienen cinco características principales.

        .row.justify-content-center.align-items-center.mb-4
          .col-lg-6
            .tarjeta-avatar-b.mb-5
              .tarjeta-avatar-b__img
                img(src='@/assets/curso/temas/tema1/decorador-19.svg' alt='')
              .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
                .p-4
                  p Centrarse en un número limitado de metas. No exigir condiciones que no se puedan cumplir. 

          .col-lg-6
            .tarjeta-avatar-b.mb-5
              .tarjeta-avatar-b__img
                img(src='@/assets/curso/temas/tema1/decorador-20.svg' alt='')
              .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
                .p-4
                  p Destacar valores y políticas esenciales de la empresa.  

          .col-lg-6
            .tarjeta-avatar-b.mb-5
              .tarjeta-avatar-b__img
                img(src='@/assets/curso/temas/tema1/decorador-21.svg' alt='')
              .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
                .p-4
                  p Definir las más importantes esferas competitivas dentro de las que maniobrará la marca. 

          .col-lg-6
            .tarjeta-avatar-b.mb-5
              .tarjeta-avatar-b__img
                img(src='@/assets/curso/temas/tema1/decorador-22.svg' alt='')
              .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
                .p-4
                  p Tener una visión de largo plazo. La misión cambia solo cuando deje de ser importante.
          
          .col-lg-6
            .tarjeta-avatar-b.mb-5
              .tarjeta-avatar-b__img
                img(src='@/assets/curso/temas/tema1/decorador-23.svg' alt='')
              .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
                .p-4
                  p Ser corta, memorable y significativa. Más que una declaración de misión, en la actualidad, se recomienda redactar enunciados corporativos con pocas palabras; Por ejemplo, American Express expresa “Proveer la mejor experiencia del usuario cada día”.

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Establecer Unidades Estratégicas de Negocios (UEN)

    p Las empresas hacen parte de un tipo de negocio, “negocio de autos” o “negocio textil”. Por eso el negocio se define como un proceso de satisfacción del cliente. Los productos pueden ser fugaces, pero, las necesidades básicas y los grupos de clientes son eternos. 
    p.mb-5 Transportarse es una necesidad y por eso el caballo, el auto, el taxi, el bus, el camión, el tren, el barco y el avión son productos que satisfacen esa necesidad. 

    .tarjeta.tarjeta.p-4.mt-4.mb-4(style="background:#FFFBE5")(data-aos="flip-up")
      .row.justify-content-center.align-items-center 
        .col-lg-5.mb-3
          figure(data-aos="fade-right")
            img(src='@/assets/curso/temas/tema1/decorador-24.svg', alt='Texto que describa la imagen')
        .col-lg-6
          p Las unidades son divisiones de la empresa que se pueden gestionar de forma individual, con su propia misión y visión, diferentes a las de la marca general. O sea, que una compañía con un grupo diverso de negocios tiene varias unidades estratégicas apartadas, con productos que se dirigen a cierto mercado con una ubicación geográfica específica.
          p Existen tres dimensiones en las que un negocio se puede definir: <strong>grupos de clientes, necesidades de los clientes y tecnología.</strong> Una microempresa que establece su negocio como creación de sistemas de iluminación incandescente para estudios televisivos, tendrá como clientes los estudios de televisión. La necesidad de estos estudios es la iluminación, y la tecnología es que esta sea incandescente. La pequeña empresa, si lo desea, se puede expandir para crear iluminación de viviendas, empresas y locales, o también puede ofrecer a los mismos estudios de televisión, calefacción, aire acondicionado o ventilación. 

    p.mb-4 Para complementar el concepto, en la siguiente figura se consolidan de forma puntual, cada uno de los pasos que se deben gestionar dentro de la estructuración de la planeación estratégica en una unidad de negocio. 

    .row.justify-content-center.align-items-center.mb-5
      .col-10.col-md-10.col-lg-10.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 3.] <em>Grafica planeación estratégica de las unidades de negocio.</em>
        figure
          img.mb-3(src='@/assets/curso/temas/tema1/img-30-1.svg', alt='En la figura 3 se muestra el proceso de la planeación estratégica, que parte de la misión del negocio, incluye entre otros la FODA, la formulación de metas y estrategias, terminando en la retroalimentación y el control.')
          figcaption Nota. Tomada de <a href="https://www.facebook.com/Agenciamonkeyplus/photos/la-planificaci%C3%B3n-estrat%C3%A9gica-en-unidades-estrat%C3%A9gicas-de-negocios-uen-es-un-ejer/2781502485230983/?_rdr">https://www.facebook.com/Agenciamonkeyplus/photos/la-planificaci%C3%B3n-estrat%C3%A9gica-en-unidades-estrat%C3%A9gicas-de-negocios-uen-es-un-ejer/2781502485230983/?_rdr</a>

    .row.mt-5.mb-5
      .col-10.col-md-10.col-lg-10.movil(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 3.] <em>Grafica planeación estratégica de las unidades de negocio.</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-30-2.svg', alt='En la figura 3 se muestra el proceso de la planeación estratégica, que parte de la misión del negocio, incluye entre otros la FODA, la formulación de metas y estrategias, terminando en la retroalimentación y el control.') 
          figcaption Nota. Tomada de <a href="https://www.facebook.com/Agenciamonkeyplus/photos/la-planificaci%C3%B3n-estrat%C3%A9gica-en-unidades-estrat%C3%A9gicas-de-negocios-uen-es-un-ejer/2781502485230983/?_rdr">Agenciamonkeyplus</a>

    .row.mb-4
      .col-md-7
        .row.align-items-center.mb-4
          .col-auto.pe-0(style="z-index:2")
            figure
              img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
          .col-auto.bg-c8(style="z-index:1")
            .p-2
              h3.mb-0.ms-3 Asignar recursos a cada unidad estratégica de negocios

        p Algunos modelos de planeación de carteras suministran los medios para tomar decisiones de inversión. Existen métodos nuevos basados en analizar el valor para el accionista, y en si el valor de mercado de una marca es mejor con o sin una unidad de negocio (incluso si esta se vende o se retira). 
        p Estos cálculos valoran la fortaleza de un negocio con base en sus opciones de crecimiento, teniendo como medidas su capacidad de expansión mundial, de reposicionamiento o redirección, y de subcontratación estratégica.

      .col-md-5
        figure
          img(src='@/assets/curso/temas/tema1/img-31.png', alt='Imagen decorativa')

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Evaluar las oportunidades de crecimiento

    p.mb-5 Esto incluye tanto la planeación de nuevos negocios, como el retiro de negocios antiguos. El proceso de planificación estratégica de las unidades de negocio consta de los siguientes pasos (Kotler y Keller, 2012):

    .row.justify-content-center.align-items-center.mb-3
      .col-10(data-aos="fade-down-right")
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row(titulo="Paso 1. La misión del negocio")
            .col-md-12.mb-4.mb-md-0
              p Cada unidad de negocio define su misión específica dentro del contexto empresarial, para que sea coherente con sus recursos y contexto. 
              
              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-12
                  figure
                    img(src='@/assets/curso/temas/tema1/img-32.png', alt='Texto que describa la imagen')

          .row(titulo="Paso 2. Análisis DOFA")
            .col-md-12.mb-4.mb-md-0
              p Evaluación general de las fortalezas, oportunidades, debilidades y amenazas, que es una forma para estudiar el entorno interno y externo de mercadeo.
              p.mb-4 En el siguiente video se pueden identificar elementos específicos de la matriz DOFA y la forma como se integran a través de este recurso las debilidades, oportunidades, fortalezas y amenazas de una organización. 

              figure.mb-4
                .video
                  iframe(width="560" height="315" src="https://www.youtube.com/embed/84fuGpQeYg0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

              p Cuando se habla del <strong>análisis del entorno externo</strong> (oportunidades y amenazas), se refiere al macro entorno, donde se analiza el Pestel, es decir las variables: política, económica, socio cultural, tecnológica, ecológica y legal, las cuales deben ser estudiadas desde el contexto empresarial. El <strong>análisis del entorno interno (fortalezas y debilidades),</strong> se refiere al micro entorno, donde se evalúan las fortalezas y debilidades de una marca. Las empresas pueden evaluar sus propias fortalezas y debilidades a través de una lista de verificación donde se analice, principalmente, la filosofía empresarial (misión, visión y valores), la diferencia competitiva, los proveedores, los distribuidores, los clientes, los socios (si los hay) y la competencia.

          .row(titulo="Paso 3. Formulación de metas")
            .col-md-12.mb-4.mb-md-0
              p Se refiere a los objetivos específicos que en la mayoría de las unidades de negocio se encuentran la rentabilidad, el aumento en las ventas, el incremento en la participación de mercado, el bloqueo de riesgos, la innovación y la reputación. La unidad de negocio determina estas metas para luego implementar un proceso de Administración por Objetivos (APO); para que un sistema de APO marche, las metas de la unidad de negocio tienen que cumplir los siguientes criterios:

              .tarjeta.tarjeta.p-4.mb-3(style="background-color:#FFFF")
                .row
                  .col-9
                    p <strong>Estrategia de producto</strong>
                    ul.lista-ul.mb-3
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Deben adaptarse por jerarquía de manera descendente, de acuerdo con su importancia. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Las metas deben ser cuantitativas siempre que sea posible. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Las metas deben ser realistas. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | Las metas deben ser consistentes. 

              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-12
                  figure
                    img(src='@/assets/curso/temas/tema1/img-33.png', alt='Texto que describa la imagen')
 

          .row(titulo="Paso 4. Formulación estratégica")
            .col-md-12.mb-4.mb-md-0
              p Las metas muestran lo que quiere conseguir una unidad de negocio; la estrategia es el plan para alcanzar el cumplimiento. Para lograr las metas, cada negocio debe crear una estrategia de mercadeo, una estrategia tecnológica (digital) y una estrategia de aprovisionamiento.

              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-12
                  figure
                    img(src='@/assets/curso/temas/tema1/img-34.png', alt='Texto que describa la imagen')

          .row(titulo="Paso 5. Formulación e implementación de programas")
            .col-md-12.mb-4.mb-md-0
              p Se refiere a programas de mercadeo que permitan que la unidad pueda lograr liderazgo tecnológico, reforzar el departamento I + D (investigación y desarrollo), recopilar inteligencia tecnológica, desarrollar productos innovadores, capacitar la fuerza de ventas o comunicar su liderazgo tecnológico. La implementación de los programas dependerá del contexto empresarial y de sus recursos. Una vez formulados los programas de mercadeo, los especialistas deben calcular los costos, para no pasarse del presupuesto empresarial.

              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-12
                  figure
                    img(src='@/assets/curso/temas/tema1/img-35.png', alt='Texto que describa la imagen')

          .row(titulo="Paso 6. Implementación")
            .col-md-12.mb-4.mb-md-0
              p La estrategia es apenas uno de los 7 ítems que participan en la práctica exitosa de las empresas. Los tres ítems iniciales, estrategia, estructura y sistemas- son el <em>“hardware”</em> del éxito; los otros 4 -estilo, habilidades, personal y valores compartidos- son el <em>“software”.</em>

              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-12
                  figure.mb-3
                    img(src='@/assets/curso/temas/tema1/img-36.png', alt='Texto que describa la imagen')

              p El primer ítem del <em>software,</em> estilo, representa que los empleados comparten una forma de comportarse y pensar. El segundo ítem, habilidades, involucra que los empleados tienen habilidades que sirven para llevar a cabo la estrategia empresarial. El ítem personal describe que la marca ha contratado personas capaces, asignándolas a los trabajos precisos para cada cual. El cuarto ítem, valores compartidos, muestra que los empleados comparten los mismos valores y se guían por ellos. Cuando todos estos ítems están presentes, las empresas pueden tener más éxito a la hora de implementar su estrategia.
          
          .row(titulo="Paso 7. Control y retroalimentación")
            .col-md-12.mb-4.mb-md-0
              p Es hora de realizar un análisis sobre lo realizado hasta el momento y de corregir lo necesario, incluso, presentando planes de mejoramiento. 

              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-12
                  figure
                    img(src='@/assets/curso/temas/tema1/img-37.png', alt='Texto que describa la imagen')

    Separador

    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3  Segmentación 

    p Tal como afirman Rodríguez, Montes y López (2007), en los mercados amplios, grandes y diversos, es una utopía que las marcas se puedan contactar con todos los clientes. Lo que sí se puede hacer es dividir esos mercados en grupos de consumidores homogéneos, o sea, segmentos que se conforman por tener las mismas necesidades y deseos. La marca, entonces, necesita elegir los segmentos de mercado que puede atender con eficacia. 
    p.mb-5 Para ser más competitivos, muchas marcas han adoptado en la actualidad el <em>marketing</em> dirigido, o sea, enfocarse en aquellas clientes que tienen mejor opción de satisfacer. Para ser efectivo, el <em>marketing</em> dirigido exige que los especialistas en mercadeo:

    .row.justify-content-center.align-items-center.mb-3
      .col-10(data-aos="fade-down-right")
        .tarjeta--container.row.mb-5
          .col-md.tarjeta.color-primario.p-4(style="background-color:#E3ECF7")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-25.svg', alt='Texto que describa la imagen')
              
            p.text-center Identifiquen y perfilen diferentes grupos de compradores, cuyas necesidades y deseos son distintos (segmentación del mercado).

          .col-md.tarjeta.color-acento-botones.p-4(style="background-color:#FFFBE5")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-26.svg', alt='Texto que describa la imagen')
              
            p.text-center(style="color:#000") Elijan uno o más segmentos de mercado donde pueda entrar (segmentos meta u objetivo).

          .col-md.tarjeta.color-acento-contenido.p-4(style="background-color:#E4FDFB")
            .row.justify-content-center.mb-4
              .col-4
                figure
                  img(src='@/assets/curso/temas/tema1/decorador-27.svg', alt='Texto que describa la imagen')
              
            p.text-center(style="color:#000") Instauren y notifiquen los beneficios diferenciales de la oferta de la marca para cada segmento objetivo (posicionamiento de mercado).

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Bases para segmentar los mercados de consumo 

    p Segmentar es dividir el mercado en partes homogéneas de acuerdo con los gustos y necesidades de las personas. La labor del especialista en mercadeo radica en identificar el número y naturaleza de los distintos segmentos que pueden conformar el mercado, y en elegir a cuáles se va a dirigir la marca. Los investigadores pretenden definir los segmentos a través del análisis de sus características descriptivas: las variables geográfica, demográfica, psicográfica y conductual. Luego exploran si los clientes de estos segmentos presentan distintas necesidades o respuestas a los productos. Independientemente de qué clase de estilo de segmentación se use, la clave será ajustar el programa de mercadeo para tener en cuenta las diferencias entre los clientes. 
    p.mb-5 La siguiente línea de tiempo tiene como fin ampliar y detallar los conceptos propios de la segmentación y cada una de sus líneas a nivel geográfico, demográfico, psicográfico y conductual.

    .row.justify-content-center.align-items-center.mb-5
      .col-10(data-aos="fade-down-right")
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Segmentación geográfica")
            .col-md-12.mb-4.mb-md-0
              p Permite concebir dónde están localizados de forma geográfica los consumidores potenciales del producto. Trabaja sobre el principio de que la gente que corresponde a esa zona geográfica tiene necesidades, deseos y características culturales parecidas. Con estos datos, las marcas pueden crear sus campañas de manera estratégica, usando el lenguaje correcto y comprendiendo si su oferta es importante para las personas de esa región. Para hacer una segmentación geográfica debes tener en cuenta algunas variables:
              
              .tarjeta.tarjeta.p-4.mb-3(style="background-color:#FFFF")
                .row
                  .col-12
                    p <strong>Estrategia de producto</strong>
                    ul.lista-ul.mb-3
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | <strong>Localización:</strong> puede ir desde un continente hasta un vecindario. 
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | <strong>Clima:</strong> relevancia de los cambios climáticos en la conducta,  incluyendo estaciones.  
                      li.mb-0
                        i.fas.fa-circle(style="color:#33ECE0")
                        | <strong>Cultura:</strong> fundamental para crear campañas exitosas en cualquier parte del mundo. 
                  
            .row.justify-content-center.align-items-center.mb-0
              .col-10.col-md-10.col-lg-12
                figure
                  img(src='@/assets/curso/temas/tema1/img-38.png', alt='Texto que describa la imagen')

          .row(numero="2" titulo="Segmentación demográfica")
            .col-md-12.mb-4.mb-md-0
              p Permite hacer división por variables como edad, familia (tamaño y ciclo de vida), género, nacionalidad, ocupación, ingresos, estrato socioeconómico, educación, religión, raza y generación. La demografía puede estar asociada con las necesidades y deseos de los consumidores (psicografía), por lo que hay que tener coherencia a la hora de describirlas; son fáciles de medir. 
            
            .row.justify-content-center.align-items-center.mb-0
              .col-10.col-md-10.col-lg-12
                figure
                  img(src='@/assets/curso/temas/tema1/img-39.png', alt='Texto que describa la imagen')

          .row(numero="3" titulo="Segmentación psicográfica")
            .col-md-12.mb-4.mb-md-0
              p Permite dividir según la personalidad como los estilos de vida, intereses, deseos, hobbies, gustos, anhelos, inquietudes, sentimientos, opiniones y valores. 

            .row.justify-content-center.align-items-center.mb-0
              .col-10.col-md-10.col-lg-12
                figure
                  img(src='@/assets/curso/temas/tema1/img-40.png', alt='Texto que describa la imagen')
          
          .row(numero="4" titulo="Segmentación conductual ")
            .col-md-12.mb-4.mb-md-0
              p Permite dividir a los compradores en grupos con base en los hábitos de consumo, como la actitud, el modo de uso, nivel de uso, beneficios (calidad, precio, servicio), fidelidad de marca, respuesta a un producto y tipo de usuario, entre otras.

            .row.justify-content-center.align-items-center.mb-0
              .col-10.col-md-10.col-lg-12
                figure
                  img(src='@/assets/curso/temas/tema1/img-41.png', alt='Texto que describa la imagen')

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Bases para segmentar los mercados empresariales

    p.mb-5 Se puede segmentar los mercados de las empresas usando algunas variables empleadas para segmentación de mercados de consumo, como por ejemplo, geografía, beneficios buscados y nivel de utilización, pero los especialistas en mercadeo B2B <em>(Business to Business)</em> tienen en cuenta otras variables como las siguientes:

    .row.justify-content-center.mt-5.mb-5
      SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-28.svg' alt='AvatarTop')
          p Es lo que la empresa hace mejor para sus clientes. 

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-29.svg' alt='AvatarTop')
          p Diferencia competitiva.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-30.svg' alt='AvatarTop')
          p El grupo de productos que generan valor para la marca.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-31.svg' alt='AvatarTop')
          p Resuelve una problemática determinada para un segmento de clientes.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-32.svg' alt='AvatarTop')
          p Novedosa, personalizada, funcional.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-33.svg' alt='AvatarTop')
          p De diseño, estatus, precio, conveniencia, usabilidad, accesible, de confianza.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema1/decorador-34.svg' alt='AvatarTop')
          p Responde a las preguntas: ¿Qué se ofrece a los clientes? ¿Por qué la marca es elegida? ¿Qué diferencia tiene la marca de otras propuestas? 






                  

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    datosSlyder: [
      {
        titulo: 'Bienes',
        texto:
          'Productos tangibles que conforman la mayor parte de la producción. Todos los años, las empresas a nivel internacional promocionan millones de bienes alimenticios frescos, embotellados, congelados o en bolsa; así como también millones de autos, productos refrigerados, celulares, etc.',
        imagen: require('@/assets/curso/temas/tema1/img-1.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Servicios',
        texto:
          'Bienes intangibles que, con la evolución de la economía, están en crecimiento a nivel global. Como ejemplo se pueden mencionar los servicios bancarios, hoteleros o turismo, funerarias, seguros de vida, médicos, etc.',
        imagen: require('@/assets/curso/temas/tema1/img-2.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Eventos',
        texto:
          'Especialistas en mercadeo promocionan eventos que se basan en el tiempo como, por ejemplo, conferencias, muestras artísticas, ferias industriales, conciertos y aniversarios empresariales. <br> El Mundial de Fútbol y los Juegos Olímpicos se promocionan cada cuatro años con un gran impacto publicitario, tanto hacia las compañías, como también hacia la misma sociedad.',
        imagen: require('@/assets/curso/temas/tema1/img-3.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Experiencias',
        texto:
          'Una empresa, al tener varios bienes y servicios, puede crear, ajustar y promocionar experiencias. Por ejemplo, Walt Disney World a través de su parque Magic Kingdom permite a la sociedad disfrutar de un mundo maravilloso e inolvidable. <br> También hay ejemplos con experiencias más personalizadas, tales como vivir unos días en un campamento de fútbol con ídolos retirados del deporte, o vivir la fantasía de ser un músico en un campamento de rock and roll en Las Vegas durante cuatro días.',
        imagen: require('@/assets/curso/temas/tema1/img-4.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Personas',
        texto:
          'Músicos, deportistas, artistas, médicos, odontólogos, psicólogos, arquitectos, ingenieros y otros profesionales de gran trayectoria reciben asesoría de los mejores especialistas en mercadeo. <br> Crear una marca personal es una recomendación que se le hace a este tipo de profesionales.',
        imagen: require('@/assets/curso/temas/tema1/img-5.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Lugares',
        texto:
          'Países, estados, ciudades, barrios y locaciones compiten por visitantes, habitantes, fábricas y compañías. Los especialistas en este tema tienen en cuenta la economía, agencias de bienes raíces, bancos, negocios, agencias publicitarias y asesores en relaciones públicas. <br> Las Vegas Convention & Visitors Authority, creó un eslogan que caló en los clientes, “Lo que sucede en Las Vegas, se queda en Las Vegas”, para representar que en esta gran ciudad los adultos pueden disfrutar de una gran cantidad de juegos infantiles para mayores de edad.',
        imagen: require('@/assets/curso/temas/tema1/img-6.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Propiedades',
        texto:
          'Se refiere a derechos de propiedad intangible, ya sea para bienes raíces, que trabajan para dueños de apartamentos o vendan propiedades, como también para propiedades financieras que promocionan valores a inversiones individuales o institucionales.',
        imagen: require('@/assets/curso/temas/tema1/img-7.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Organizaciones',
        texto:
          'Empresas que laboran para la creación de una imagen impactante, atractiva y única para posicionarse en la mente de su público objetivo.',
        imagen: require('@/assets/curso/temas/tema1/img-8.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Información',
        texto:
          'Conforma una de las principales industrias. La información es, principalmente, lo que los escritores, instituciones y universidades fomentan, promocionan y mercantilizan a las familias, alumnos y comunidades.',
        imagen: require('@/assets/curso/temas/tema1/img-9.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Ideas',
        texto:
          'Cualquier oferta de mercado contiene un concepto. La marca Revlon, que produce en su fábrica cosméticos, vende esperanza a través de su publicidad. Los bienes y servicios pueden ser aprovechados creativamente para ofrecer beneficios de una manera inteligente y atractiva. ',
        imagen: require('@/assets/curso/temas/tema1/img-10.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
    ],
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
