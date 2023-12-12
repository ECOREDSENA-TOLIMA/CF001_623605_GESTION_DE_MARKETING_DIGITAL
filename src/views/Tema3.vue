<template lang="pug">
.curso-main-container.pb-3.tema3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Mapas de empatía, arquetipos y <em>buyer</em> persona

    p.mb-5 Beltrán, Ledesma y Parrales (2019), dicen que, antes de todo, la idea es hacer un análisis sobre el tipo de clientes al que se dirige un futuro negocio. Por eso, se sugiere realizar una segmentación de mercado, dividirlo en partes lo más homogéneas posible; división que se puede realizar según distintas categorías sociodemográficas, socioeconómicas, conductuales y psicográficas. 

    .row.justify-content-center.align-items-center.mb-5
      .col-10(data-aos="fade-down-right")
        .tarjeta.tarjeta.p-4.mt-4.mb-4(style="background:#E3ECF7")(data-aos="flip-up")
          .row.justify-content-center.align-items-center 
            .col-lg-3.mb-3
              figure(data-aos="fade-right")
                img(src='@/assets/curso/temas/tema3/decorador-1.svg', alt='Texto que describa la imagen')
            .col-lg-9
              p Los segmentos son usados con una dirección global y estratégica, de tal forma que se puedan diseñar mapas de empatía más fácil y coherentemente. 
              p El arquetipo, también conocido como “persona”, se refiere a la tipología de cliente a la que se dirige la marca. Se trata de humanizarlo (se le pone nombre y foto), de esta forma se empatiza con el cliente. En el arquetipo de cliente se debe incluir información como nombre, foto, aspectos socio demográficos o socioeconómicos, edad, ocupación, nivel educativo, profesión, motivaciones, objetivos, frustraciones y limitaciones y, sobre todo, si existe relación con el producto de la marca. Por su lado, los <em>buyer</em> persona son el cliente ideal al que la marca quiere dirigirse.  

    Separador 

    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.1  Características de los mapas de empatía

    p El mapa de empatía es un documento que busca relatar cuál es el cliente ideal de una marca a través del análisis de seis elementos relacionados con los sentimientos humanos. 
    p.mb-5 Se puede detallar a partir de preguntas que ayudan a comprender quién es el cliente y cómo interactuar con él. Se debe imaginar cómo ingresar en la mente del cliente, entender lo que desea y sus insatisfacciones, para luego ofrecerle productos con atención más apropiada, y aunque hasta hace algunos años esto no se podía, se puede hacer a través de algunas herramientas, como, por ejemplo, el mapa de empatía que es usado para crear el perfil del cliente ideal según son sus sentimientos.

    .row.justify-content-center.align-items-center.mb-5
      .col-10(data-aos="fade-down-right")
        .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img-1.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 En la actualidad, con tantos conflictos globales, se escucha a menudo la frase “el mundo necesita más empatía”. Esto es debido a que la empatía tiene la habilidad de entender el estado emocional de alguien al ubicarse en su lugar, permitiendo analizar los contextos sobre diferentes perspectivas. Esta herramienta fue diseñada por la empresa Xplane y, a través de ella, se personaliza, caracteriza y establece un enfoque más empático del consumidor. El mapa de empatía ayuda a ahondar en la comprensión del cliente porque se puede conocer su personalidad, visión, entorno, deseos y necesidades.

        p.mb-5 Ahora se debe imaginar cómo estos sentimientos se deben ubicar en categorías divididas por dolores, necesidades y sentimientos, y en cuadrantes que hacen fácil la visualización. Así es como funciona el mapa de empatía, su objetivo es detallar la personalidad del cliente para entenderlo mejor. Se puede diseñar en un tablero, <em>flip chart</em>, cartelera o digitalmente y cuando se hace en papel, su diseño se completa con <em>post-its.</em> Independiente de cuál sea el soporte, el mapa de empatía se debe dividir de la siguiente forma:
        
        .row.justify-content-center.align-items-center.mb-5
          .col-10.col-md-10.col-lg-10.desktop(data-aos="fade-right")
            .titulo-sexto.color-acento-contenido
              p.titulo.pb-0.mb-0 #[b Figura 5.] <em>Grafica mapas de empatía</em>
            figure
              img.mb-3(src='@/assets/curso/temas/tema3/img-2-1.svg', alt='En la figura 5 se detallan las preguntas clave que deben abordarse para construir un mapa de empatía, las cuales son: ¿Qué piensa y siente? ¿Qué escucha? ¿Qué hace? ¿Qué ve? ¿Cuáles son sus dolores? ¿Cuáles son sus necesidades?')
              figcaption Nota. Tomada y adaptada de https://rosanarosas.com/mapa-de-empatia-herramienta-para-conocer-tu-cliente/

        .row.mt-5.mb-2
          .col-10.col-md-10.col-lg-10.movil(data-aos="fade-right")
            .titulo-sexto.color-acento-contenido
              p.titulo.pb-0.mb-0 #[b Figura 5.] <em>Grafica mapas de empatía</em>
            figure
              img(src='@/assets/curso/temas/tema3/img-2-2.svg', alt='En la figura 5 se detallan las preguntas clave que deben abordarse para construir un mapa de empatía, las cuales son: ¿Qué piensa y siente? ¿Qué escucha? ¿Qué hace? ¿Qué ve? ¿Cuáles son sus dolores? ¿Cuáles son sus necesidades?') 
              figcaption Nota. Tomada y adaptada de https://rosanarosas.com/mapa-de-empatia-herramienta-para-conocer-tu-cliente/

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Cómo hacer un mapa de empatía en seis pasos

    p.mb-5 Aquí se puede decir que hay una etapa antes de comenzar con los pasos, y donde se estudia, previamente, el comportamiento del consumidor ideal, por lo que se debe crear una persona ficticia construida a partir de datos reales de personas verdaderas, con particularidades psicológicas, que personifica un grupo con cualidades y comportamientos semejantes.

    .tarjeta.tarjeta.p-4.mb-5.mt-0(style="background-color:#E4FDFB")(data-aos="flip-up")
      .row.justify-content-center.align-items-center 
        .col-md-8.mb-3
          p Se sugiere tener, entonces, una mínima audiencia, por ejemplo, fanáticos de la marca en redes sociales que les gusta lo que se publica, o también, aquellos que son clientes actuales. Luego de esto, se pueden compartir los resultados con otros miembros del equipo y realizar una lluvia de ideas para presentar opiniones y recoger recomendaciones, que pueden identificar los segmentos de clientes. Al tener esta información, estará listo el momento de comenzar a desarrollar el mapa de empatía.

        .col-md-4
          figure
            img(src='@/assets/curso/temas/tema3/decorador-2.svg', alt='Imagen decorativa')

    p.mb-5 Para ampliar los conceptos que se deben tener presentes en el momento de diseñar un mapa de empatía y las preguntas orientadoras para la consolidación de este, en los siguientes pasos se podrán identificar estas preguntas fundamentales para identificar el sentir del usuario o cliente. 

    .BGIMG03.p-4
      LineaTiempoC.color-acento-contenido(text-small)
        .row(titulo="Paso 1")
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 ¿Qué escucha? 
            p Cuadrante en donde se debe pensar en lo que la persona oye no solo de manera sonora, sino también de diversas fuentes, como canales de comunicación. Pretende responder estas preguntas: ¿Qué personas e ideas lo motivan? ¿Cuáles son sus ídolos? ¿Cuáles son sus marcas favoritas? ¿Qué medios y programas de comunicación consume?

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema3/img-3.png', alt='Texto que describa la imagen')

        .row(titulo="Paso 2")
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 ¿Qué ve? 
            p Primera sección que identifica los estímulos visuales que la persona recibe. Pretende responder estas preguntas: ¿Cuál es el mundo en donde vive? ¿Cómo son los amigos? ¿Qué es lo más normal en su vida cotidiana?

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema3/img-4.png', alt='Texto que describa la imagen')

        .row(titulo="Paso 3")
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 ¿Qué piensa y siente? 
            p Sección donde se hallan las ideas que el producto estimula en la mente de los clientes. Pretende responder estas preguntas: ¿Cómo se siente en relación con el mundo? ¿Qué le preocupa? ¿Qué sueños tiene?

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema3/img-5.png', alt='Texto que describa la imagen')

        .row(titulo="Paso 4")
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 ¿Qué habla y hace? 
            p Esta sección está relacionada con el consumo del producto, desde el momento en que el cliente toma la decisión de compra. Para conocer lo que la persona dice y hace, se debe prestar atención a su conducta: su discurso y sus acciones. Pretende responder estas preguntas: ¿Qué temas acostumbra hablar? ¿Cómo se comporta? ¿Tiene hobbies? ¿Cuáles?

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema3/img-6.png', alt='Texto que describa la imagen')
        
        .row(titulo="Paso 5")
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 ¿Cuáles son sus dolores?  
            p Cuadrante relacionado con las dudas y dificultades que el cliente tiene que superar para consumir el producto. Pretende responder estas preguntas: ¿Tiene miedo de algo? ¿Qué frustraciones tiene? ¿Qué dificultades debe superar para alcanzar lo que desea?

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema3/img-7.png', alt='Texto que describa la imagen')
              
        .row(titulo="Paso 6")
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 ¿Cuáles son sus necesidades? 
            p Cuadrante que se relaciona con lo que se puede poner en práctica para sorprender al cliente, mostrándole posibilidades. Pretende responder estas preguntas: ¿Qué es el éxito para el cliente? ¿A dónde quiere llegar el cliente? ¿Qué terminaría con sus dificultades?

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema3/img-8.png', alt='Texto que describa la imagen')

    Separador 

    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.2  Concepto de arquetipos digitales

    p.mb-5 Los arquetipos de marca son una sucesión de valores, actitudes y procederes que identifican la marca; pueden definir y crear un vínculo emocional con el cliente. Se deben descubrir y aplicar con el fin de implementar la estrategia de mercadeo apropiada para los productos y clientes que se desean seducir.

    .row.justify-content-center.align-items-center.mb-4
      .col-10(data-aos="fade-down-right")
        .cajon.color-secundario.p-4(style="background-color:#FFFBE5")
          p El modelo Canvas sirve para la identificación de los aspectos vitales de un modelo de negocio, mostrándolos de manera ordenada, de forma tal que se puedan encontrar las actividades que son más importante, oportunidades de mejora, alternativas diferentes al modelo existente, entre otros. Es un modelo visual con el que se puede diseñar el lienzo de modelo de negocios con el que se pueden organizar mejor las ideas en el momento de crear un nuevo modelo de negocio. Es preciso para establecer y crear modelos vanguardistas con el fin de forjar valor para el público objetivo.

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Cómo aplicar los arquetipos de Carl Jung en tu estrategia de <em>marketing</em> digital
    
    p Carl Jung planteó su propia forma de comprender las motivaciones de la personalidad del ser humano a través de los arquetipos, definiendo doce prototipos primarios con distintos significados, valores y personalidades que encarnan las más elementales motivaciones del ser humano. Sus 12 arquetipos son: el inocente, el amigo, el héroe, el cuidador, el explorador, el rebelde, el amante, el creador, el bufón, el sabio, el mago y el gobernante. De acuerdo con estos prototipos, se han creado los arquetipos digitales.
    p.mb-5 Los 12 arquetipos de marca de Carl Jung.

    .row.align-items-center.mb-5(data-aos="fade-down-right")
      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-9.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Inocente</strong>
              p Bondad, sencillez, felicidad. Busca un impacto positivo.  

      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-10.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Ciudadano</strong>
              p Aunténtico, empático, sencillo. Busca ser parte de algo.
      
      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-11.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Sabio</strong>
              p Analítico, inteligente, confiable, perfeccionista. 

      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-12.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Amante</strong>
              p Apasionados, sensuales. Transmite amor y deseo.  

      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-13.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Héroe</strong>
              p Valiente, luchador. <br>Nunca se rinde.
      
      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-14.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Bufón</strong>
              p Diversión, humor. Busca contagiar la alegría de vivir.

      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-15.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Rebelde</strong>
              p Rebelde, irreverente, innovador, desafiante. 

      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-16.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Cuidador</strong>
              p Generoso, altruista, protector <br> y cercano.
      
      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-17.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Explorador</strong>
              p Inquieto, aventurero. Busca cosas nuevas.

      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-18.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Creador</strong>
              p Imaginativos, creativos, de espíritu inconformista. 

      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-19.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Mago</strong>
              p Visionario, carismático, inspirador y seguro.
      
      .col-md-4.col-12
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img.p-md-0
            img(src='@/assets/curso/temas/tema3/img-20.png' alt='')
          .tarjeta.tarjeta--azul(style="background-color:#E3ECF7")
            .p-4
              p <strong>Gobernador</strong>
              p Líder, controlador, poderoso, <br> exclusivo.

    .row.justify-content-center.align-items-center.mb-4
      .col-10(data-aos="fade-down-right")
        p En primera instancia, para comenzar a organizar la estrategia de mercadeo se sugiere tener muy presente al tipo de cliente como a la marca, de esta manera se logra generar un conjunto de características y propiedades que hacen única la marca y que se perciba por los clientes como afín y concluyente para decidir una acción de compra por los productos. 
        p.mb-4 Para lograrlo se deben tener presentes los 12 arquetipos y los elementos detallados que se encuentran definidos de una forma precisa aquí:

    .row.justify-content-center.mt-5
      SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-21.png' alt='AvatarTop')
          p Estudiar bien al público objetivo. Analizar sus motivaciones, gustos e intereses para poder dar establecimiento a los arquetipos de cliente apropiados y así hacer que la marca capte a los clientes potenciales.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-22.png' alt='AvatarTop')
          p Examinar de qué forma se enlazan los productos con las expectativas del <em>buyer</em> persona y establecer los conceptos y la comunicación con las que se piensa cautivar a los posibles clientes.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-23.png' alt='AvatarTop')
          p Es vital que una persona sea la imagen de la marca. Puede ser el creador o alguien público con la que el cliente sienta afinidad logrando crear un enlace que lo identifique.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-24.png' alt='AvatarTop')
          p Instaurar con certeza las características importantes y distintivas para los clientes e intentar vincularlas a las emociones humanas. Se puede usar el logo, el nombre y los símbolos representativos de la marca.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-25.png' alt='AvatarTop')
          p Es importante tener clara la historia original de la marca, usando el arquetipo que se considere adecuado para contactar y conquistar a los clientes potenciales.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-26.png' alt='AvatarTop')
          p No demorarse para la generación de contenidos de valor que se vinculen con el arquetipo de marca que se haya seleccionado como con el prototipo de cliente que se persigue.

    Separador 

    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.3  Características de los arquetipos digitales

    p.mb-5 En un estudio realizado por la empresa Pragma, se hizo un análisis sobre 11.000 personas entre los 17 y 70 años, logrando instituir patrones de conducta aplicados a la realidad de hoy y asentados en variables como la ocupación y la edad. A partir de esto, se crearon cinco arquetipos digitales que ayudan a segmentar mejor la población a la que la marca desea conquistar; estos arquetipos digitales son:

    .BGIMG01.p-5.mb-5
      SlyderA(tipo="b")
        .row
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 <em>Entry digital</em> (jóvenes digitales)
            p Individuos sociables, ya sea en persona o digitalmente; en los dos espacios buscan temas de su interés: arte, música y causas sociales, entre otras. Resuelven las dudas en motores de búsqueda (gran aliado). Se adecuan de forma fácil a los cambios digitales o de interfaz, talante que les permite ser amigables con las historias e imágenes instantáneas. Valoran el poder comprar por internet, pero se les dificulta usar los medios de pago. Aproximadamente tienen una edad entre los 18 y 24 años. 

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema3/img-27.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 <em>Adopter</em> (el masivo)
            p El interés por lo digital surgió por la influencia del círculo social; por lo que su conducta digital está basada en <em>chats,</em> compartición de imágenes, memes y videos virales. Acogen el uso de formatos nuevos y plataformas de una manera lenta y poco frecuente. Compran digitalmente en plataformas confiables, cercanas y de credibilidad. Empleados o independientes de áreas técnicas, comerciales y operativas; amas de casa; edad entre los 25 y 45 años.

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema3/img-28.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 <em>High digital</em> (los superdigitales)
            p Incluyen a su vida las nuevas tecnologías que le permiten evitar los trámites presenciales para ahorrar tiempo. Toman excelentes decisiones al usar aplicaciones especialistas en potenciar el rendimiento laboral y personal. Compran de manera regular a través de la <em>web.</em> Son reservados con el uso del social media, pero hacen parte de comunidades virtuales para compartir conocimiento sobre temas sociales o de su área profesional.  Poseen cargos administrativos que les permiten, en algunas situaciones, tomar decisiones relevantes. Tienen una edad entre los 25 y 50 años.

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema3/img-29.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 <em>Mix</em> (mezcla entre superdigitales y tradicionales)
            p Para el uso de la tecnología, dependen de su círculo social más cercano. Aprecian los dispositivos asistenciales de salud, aprendizaje y diversión. Valoran cuando se les brinda información concisa y completa; pueden comprar <em>online</em> siempre y cuando estén seguros del medio por el cual lo hacen. Tienen liderazgo en el momento de tomar decisiones. Son mayores de 50 años de edad.

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema3/img-30.png', alt='Texto que describa la imagen')
        
        .row
          .col-md-6.mb-4.mb-md-0.col-ipad
            h3 Tradicional (abuelo conservador)
            p Tienen más de 55 años de edad. Algunos ya están pensionados, otros laboran de manera independiente. No poseen interés por aprender nuevas tecnologías; pero lo pueden hacer si es realmente necesario. Dependen de otras personas para usar la tecnología porque se les dificulta entender el lenguaje <em>online.</em> Su uso es limitado a conversar, buscar en Google y usar una que otra red social. En pocas ocasiones efectúan transacciones virtuales. 

          .col-md-6.col-ipad
            figure
              img(src='@/assets/curso/temas/tema3/img-31.png', alt='Texto que describa la imagen')

    p Con esta información se puede comprender mejor el comportamiento del consumidor digital y así plantear una correcta estrategia de comunicación que sea dirigida a ellos.

    Separador 

    #t_3_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.4 Concepto de <em>buyer</em> persona

    p.mb-5 El <em>buyer</em> persona es la representación ficticia del cliente ideal. Está basada en datos reales relacionados con la conducta y particularidades demográficas de los clientes, así como en el diseño de las historias personales, desafíos, metas, motivaciones e inquietudes.

    .row.justify-content-center.align-items-center.mb-4
      .col-10(data-aos="fade-down-right")
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img-32.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 El tener una base de clientes es la situación perfecta para comenzar las investigaciones y creación del <em>buyer</em> persona. Aunque se pueden tener perfiles distintos de personas que consumen el producto, algunos de ellos pueden tender a ser ejemplos del <em>buyer</em> persona. 

        p Como sugerencia, se debe analizar clientes satisfechos como insatisfechos. En ambos casos, se puede aprender sobre la percepción del producto y qué desafíos enfrentan los clientes.

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Diferencia entre <em>buyer</em> persona y público objetivo

    p.mb-5 Para comprender esta diferencia es importante destacar que el público objetivo identifica un perfil del posible cliente con detalles generales que lo ubican en segmentos específicos, mientras que el <em>buyer</em> persona describe a una persona ficticia, pero que cumple de manera detallada todo lo que el prospecto de cliente en el perfil, las emociones, expectativas y demás, con el siguiente ejemplo se detalla la diferencia. 

    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-primario.p-5(style="background-color:#E3ECF7")
        .row.justify-content-center.mb-4
          .col-4
            figure
              img(src='@/assets/curso/temas/tema3/img-33.png', alt='Texto que describa la imagen')
          
        h3 Ejemplo de público objetivo
        p Hombres y mujeres, entre 24 y 30 años, solteros, arquitectos, ingresos mensuales promedio de $3.500.000 que desean incrementar su aprendizaje profesional y les fascina viajar.
        
      .col-md.tarjeta.color-acento-botones.p-5(style="background-color:#FFFBE5")
        .row.justify-content-center.mb-4
          .col-4
            figure
              img(src='@/assets/curso/temas/tema3/img-34.png', alt='Texto que describa la imagen')
          
        h3(style="color:#000") Ejemplo de <i style="color:#000">buyer</i> persona
        p(style="color:#000") Carlos tiene 26 años de edad, es profesional en arquitectura, está recién graduado y trabaja independientemente. Piensa estudiar una maestría en el exterior (le encanta viajar) para desarrollarse profesionalmente, siempre quiso obtener un intercambio, por eso busca una agencia que lo asesore para hallar universidades europeas que avalen estudiantes del exterior. No está casado.

    .row.justify-content-center.align-items-center.mb-4
      .col-10(data-aos="fade-down-right")
        p Como se puede apreciar, el público objetivo abarca una parte de la sociedad a la cual se dirigen los productos de la marca. Por su lado el <em>buyer</em> persona representa al cliente ideal, de manera más humanizada y personalizada. Inicialmente pueden ser muy parecidos, pero es diferente pensar una estrategia de <em>marketing</em> digital que se direcciona a Carlos, en vez de un público objetivo bastante amplio. 
        p.mb-5 Por otro lado, si se piensa que se ha segmentado muy a fondo, no es necesario limitarse a un solo <em>buyer</em> persona. Es normal que las marcas tengan más de un <em>buyer</em> persona determinada, pero siempre y cuando no se exagere en la cantidad a la hora de elegirlas.

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Cuestiones que le ayudarán a definir el <em>buyer</em> persona
    
    p.mb-5 Es hora de orientarse por el perfil del cliente típico, o sea, dejarse llevar por la mayoría para dar respuesta a algunas preguntas que ayudarán a definir el perfil de la conducta del <em>buyer</em> persona; los siguientes interrogantes permiten dar mayor claridad sobre el concepto definido:

    .row.justify-content-center.mt-5
      SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-35.png' alt='AvatarTop')
          p ¿Quién es el cliente potencial? Particularidades físicas y psicológicas del responsable de la compra.

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-36.png' alt='AvatarTop')
          p ¿Qué tipo de cuestión le interesaría sobre el sector?

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-37.png' alt='AvatarTop')
          p ¿Cuáles son las acciones que con mayor frecuencia ejecuta personal y profesionalmente?

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-38.png' alt='AvatarTop')
          p ¿Cuál es su nivel de educación? 

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#E3ECF7")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-39.png' alt='AvatarTop')
          p ¿Cuáles son sus metas y dificultades?

        .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFBE5")
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema3/img-40.png' alt='AvatarTop')
          p ¿Qué tipo de datos consume y en qué canales o medios?

    .row.justify-content-center.align-items-center.mb-4
      .col-10(data-aos="fade-down-right")
        p.mb-5 Para productos B2B (empresa a empresa) se hace necesario reflexionar sobre las siguientes preguntas orientadoras que permiten focalizar el perfil esperado. 
        
        .row.justify-content-center.align-items-center.mb-5
          .col-10.col-md-10.col-lg-12.desktop(data-aos="fade-right")
            figure
              img.mb-3(src='@/assets/curso/temas/tema3/img-43-1.svg', alt='Se revelan 3 preguntas: 1- ¿Qué tipo de empresa es el que compra el producto? 2- ¿Cuál es el cargo del que elige la compra? 3- ¿Quién influye en sus decisiones?')
             
        .row.mt-5.mb-2
          .col-10.col-md-10.col-lg-12.movil(data-aos="fade-right")
            figure
              img(src='@/assets/curso/temas/tema3/img-43-2.svg', alt='Se revelan 3 preguntas: 1- ¿Qué tipo de empresa es el que compra el producto? 2- ¿Cuál es el cargo del que elige la compra? 3- ¿Quién influye en sus decisiones?') 
             
        figure
          img.mb-3(src='@/assets/curso/temas/tema3/img-44.png', alt='')
      
    p Por otro lado, se requiere tener en mente lo que el directivo responsable de comprar el producto busca en el área de acción de la marca. Se debe pensar en lo que le puede interesar, como, por ejemplo, las dificultades que enfrenta a diario y que se relacionan con el sector en que se mueve la marca. 
    p.mb-5 Al terminar este proceso, se tiene una excelente cantidad de información bruta sobre los clientes potenciales.

    .row.align-items-center.mb-4
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/icono.svg', style="width: 30px" ,alt='').m-auto
      .col-auto.bg-c8(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 Cómo crear el <em>buyer</em> persona

    p El siguiente paso es crear el perfil del cliente de acuerdo con las respuestas conseguidas. Con eso, se pueden agrupar los datos y crear el personaje en un documento que se pone a disposición de todo el equipo de trabajo, para tener un aval final, y si es del caso, hacer alguna corrección.
    p.mb-5 Algunas particularidades que se usan para crear los <em>buyer</em> persona son:

    .tarjeta.tarjeta.p-4.mt-4.mb-4(style="background:#E3ECF7")(data-aos="flip-up")
      .row.justify-content-center.align-items-center 
        .col-lg-5
          SlyderF.mb-4(columnas="col-lg-6 col-xl-12")
            .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFF")
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/tema3/img-45.png' alt='AvatarTop')
              p <strong>Perfil</strong>
              ul.lista-ul.mb-3
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Auxiliar de producción.
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Graduada en comunicación audiovisual.
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Madre primeriza de un bebé de un año. 
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Vive en pareja pero no está casada.

            .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFF")
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/tema3/img-46.png' alt='AvatarTop')
              p <strong>Datos demográficos</strong>
              ul.lista-ul.mb-3
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Mujer, 34 años.
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Vive de alquiler en Suba (Bogotá).
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Autónoma con ingresos mensuales de alrededor de 2.000.000 de pesos.

            .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFF")
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/tema3/img-47.png' alt='AvatarTop')
              p <strong>Hábitos</strong>
              ul.lista-ul.mb-3
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Compra mucho online, pero no le gusta Amazon.
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Última compra: ropa para su hijo.

            .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFF")
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/tema3/img-48.png' alt='AvatarTop')
              p <strong>Intereses</strong>
              ul.lista-ul.mb-3
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Va dos veces al mes al cine.
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Practica yoga y corre maratones.
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Abonada a Netflix y HBO.
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Pasa una media de dos horas diarias en Instagram.

            .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFF")
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/tema3/img-49.png' alt='AvatarTop')
              p <strong>Retos</strong>
              ul.lista-ul.mb-3
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Incrementar sus ahorros en un 30% durante los próximos 3 años.
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Combinar estabilidad laboral y familiar.

            .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFF")
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/tema3/img-50.png' alt='AvatarTop')
              p <strong>Frustraciones</strong>
              ul.lista-ul.mb-3
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | No obtener el suficiente reconocimiento laboral. Quedarse estancada profesionalmente.
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Pasar poco tiempo con la familia.
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Atravesar problemas económicos.
            
            .tarjeta.color-primario.p-4.col-ipad(style="background-color:#FFFF")
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/tema3/img-50.png' alt='AvatarTop')
              p <strong>Objetivos</strong>
              ul.lista-ul.mb-3
                li.mb-0
                  i.fas.fa-circle(style="color:#E3ECF7")
                  | Montar su propia productora en 4 años.

        .col-lg-5
          ul.lista-ul.mb-3
            li.mb-0
              i.fas.fa-circle(style="color:#000")
              | Nombre (ficticio).
            li.mb-0
              i.fas.fa-circle(style="color:#000")
              | Información demográfica.
            li.mb-0
              i.fas.fa-circle(style="color:#000")
              | Sexo.
            li.mb-0
              i.fas.fa-circle(style="color:#000")
              | Edad.
            li.mb-0
              i.fas.fa-circle(style="color:#000")
              | Ocupación.
            li.mb-0
              i.fas.fa-circle(style="color:#000")
              | Segmento de actividad.
            li.mb-0
              i.fas.fa-circle(style="color:#000")
              | Nivel académico.
            li.mb-0
              i.fas.fa-circle(style="color:#000")
              | Canales de comunicación usados.
            li.mb-0
              i.fas.fa-circle(style="color:#000")
              | Objetivos.
            li.mb-0
              i.fas.fa-circle(style="color:#000")
              | Retos. 
    
    .row.justify-content-center.align-items-center.mb-4
      .col-10(data-aos="fade-down-right")
        p Otra opción es usar un modelo gráfico para su representación. Se puede considerar también que el <em>buyer</em> persona puede ser alguien que no sabe si busca la empresa, sino más bien la solución a un problema. Esto sucede a menudo en sitios de empresas que desarrollan <em>inbound marketing.</em> Entonces, se debe plantear: ¿cómo se puede abordar y exponer el contenido relacionado con el mercado para ese <em>buyer</em> persona?

    Separador 

    #t_3_5.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.5 Características de los <em>buyer</em> persona

    p.mb-5 Mientras que el <em>buyer</em> persona es la representación del cliente ideal, también existe aquel personaje negativo que representa a alguien que la marca no quiere que sea el cliente. 

    .row.justify-content-center.align-items-center.mb-4
      .col-10(data-aos="fade-down-right")
        .tarjeta.tarjeta.p-4.mb-5.mt-0(style="background-color:#E4FDFB")(data-aos="flip-up")
          .row.justify-content-center.align-items-center 
            .col-md-8.mb-3
              p Esto puede requerir de profesionales avanzados para el producto, así como alumnos que consumen la información con el único fin de aprender, e incluso, aquellos clientes potenciales que poseen un costo de adquisición muy alto (bien sea por el precio, la posibilidad de que dejen de usar el producto o de que no ser clientes frecuentes).
              p Existen muchos tipos de <em>buyer</em> persona, los cuales se pueden catalogar en tres categorías principales, especialmente perceptibles hacia el final del proceso de la toma de decisiones. Aunque el <em>buyer</em> persona no siempre es la persona que se encarga de tomar la decisión de compra del producto, sí juega un papel vital motivándolo.

            .col-md-4
              figure
                img(src='@/assets/curso/temas/tema3/img-52.png', alt='Imagen decorativa')

        p En la siguiente línea de tiempo se detallan cuatro de las principales características de este <em>buyer</em> persona.

    .row.mb-4 
      .col-2
        img(src='@/assets/curso/temas/tema3/img-53.svg')
      .col-10
        TabsA.color-acento-botones.mb-5
          .tarjeta(style="background-color:#FFFBE5").p-4(titulo="<em>Buyer</em> persona decisor")
            h3 <em>Buyer</em> persona decisor
            p Persona que toma la decisión final en la adquisición de un producto.

          .tarjeta(style="background-color:#FFFBE5").p-4(titulo="<em>Buyer</em> persona prescriptor")
            h3 <em>Buyer</em> persona prescriptor
            p Persona que recomienda adquirir un producto. Por lo general, tiene alguna capacidad de motivar o influir en la compra.

          .tarjeta(style="background-color:#FFFBE5; max-width:100%").p-4(titulo="<em>Buyer</em> persona influenciador")
            h3 <em>Buyer</em> persona influenciador
            p Persona que tiene una opinión, bien sea positiva o negativa, y que influye directamente en la acción de compra. Es vital saber quién es este tipo de buyer persona, porque ayuda a decidir con quiénes se pueden enfocar los esfuerzos a la hora de ofrecer el producto al interior de una empresa

          .tarjeta(style="background-color:#FFFBE5; max-width:100%").p-4(titulo="<em>Buyer</em> persona negativo")
            h3 <em>Buyer</em> persona negativo
            p Es el cuarto tipo de <em>buyer</em> persona y representa a aquellas personas que no tienen ninguna intención de comprar o usar el producto, pero que podrían demostrar algún interés en las campañas y acciones de mercadeo.

    Separador 

    #t_3_6.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.6  Concepto de prospecto de cliente

    p El prospecto es objetivo del vendedor y el segmento de cliente es objetivo del departamento de mercadeo. Lo normal es que el prospecto corresponda al segmento de cliente que el área de mercadeo definió como el receptor del producto que vende la marca, pero, mientras que el segmento de mercado es amplio y no tiene nombre y apellidos porque son muchas personas, el prospecto es personalizado y sí los tiene. 
    p.mb-5 El prospecto es objetivo del vendedor y el segmento de cliente es objetivo del departamento de mercadeo. Lo normal es que el prospecto corresponda al segmento de cliente que el área de mercadeo definió como el receptor del producto que vende la marca, pero, mientras que el segmento de mercado es amplio y no tiene nombre y apellidos porque son muchas personas, el prospecto es personalizado y sí los tiene. 

    .row.justify-content-center.align-items-center.mb-5
      .col-10.col-md-10.col-lg-10.desktop(data-aos="fade-right")
        figure
          img.mb-3(src='@/assets/curso/temas/tema3/img-54-1.svg', alt='Se revelan 3 características del prospecto: - Poseer una necesidad que el producto puede solventar. - Poseer presupuesto, capacidad económica para adquirir el producto. - Poseer capacidad de decisión, o sea, la persona correcta y que decide una compra.')
             
    .row.mt-5.mb-2
      .col-10.col-md-10.col-lg-10.movil(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema3/img-54-2.svg', alt='Se revelan 3 características del prospecto: - Poseer una necesidad que el producto puede solventar. - Poseer presupuesto, capacidad económica para adquirir el producto. - Poseer capacidad de decisión, o sea, la persona correcta y que decide una compra.') 

    p.mb-5 Evidentemente, y con base en lo anterior, no todo prospecto es igual a otro, por eso es vital hacer una precisa calificación para ejecutar una excelente tarea comercial; gestión que es clave en época de crisis, cuando el mercado es poco y la competencia mucha, algo que entorpece la captación de clientes rentables.

    .row.justify-content-center.align-items-center.mb-4
      .col-10(data-aos="fade-down-right")
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img-55.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La vía para convertir prospectos en clientes puede comenzar en el momento en el que un navegante llega al sitio <em>web</em> y hace un registro de algo; en este momento la marca ha capturado un <em>lead.</em> Una vez se tengan más datos de esta persona y se sabe que cumple con ciertos parámetros de compra, pasa a estar ubicado en la lista de clientes potenciales calificados. 

        p.mb-5 Es el momento en el que el equipo de ventas intercede; mientras que los vendedores trabajan para crear oportunidades logrando convertir prospectos en clientes generadores de ganancias. Las etapas pueden quedar de la siguiente manera:

    .row.justify-content-center.align-items-center.mb-5
      .col-10.col-md-10.col-lg-10.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 6.] <em>¿Cómo convertir prospectos en clientes?.</em>
        figure
          img.mb-3(src='@/assets/curso/temas/tema3/img-56-1.svg', alt='En la figura 6 se describe el proceso de convertir prospectos en clientes. Inicia con la captura del lead, pasa a calificado, continua con la aceptación del equipo de ventas, pasa a oportunidad de negocio y finalmente se consigue el cliente.')
          figcaption Nota. Tomada y adaptada de https://tudashboard.com/como-convertir-prospectos-en-clientes/
          
    .row.mt-5.mb-2
      .col-10.col-md-10.col-lg-10.movil(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 6.] <em>¿Cómo convertir prospectos en clientes?.</em>
        figure
          img(src='@/assets/curso/temas/tema3/img-56-2.svg', alt='En la figura 6 se describe el proceso de convertir prospectos en clientes. Inicia con la captura del lead, pasa a calificado, continua con la aceptación del equipo de ventas, pasa a oportunidad de negocio y finalmente se consigue el cliente.')
          figcaption Nota. Tomada y adaptada de https://tudashboard.com/como-convertir-prospectos-en-clientes/

    Separador 

    #t_3_7.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.7  Características de los prospectos

    p.mb-5 Para prever las características que poseen los prospectos, se destacan los siete tipos más importantes:

    .BGIMG01.p-4.mb-5
      SlyderB.mb-5(:datos="datosSlyder")













</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    datosSlyder: [
      {
        titulo: 'Prospectos potenciales',
        texto:
          'Cuando está interesado en el producto y ya ejecutó alguna acción para conocer el precio, particularidades, funciones y beneficios, a pesar de que aún no ha comprado.',
        imagen: require('@/assets/curso/temas/tema3/img-57.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Prospectos analíticos',
        texto:
          'Cuando se toman tiempo para desarrollar una acción de compra. Investigan el producto, la empresa e incluso los clientes de la marca para conocer su experiencia. Hacen preguntas sobre detalles muy concretos que son de mucha importancia para sus metas, pero que no son tan habituales. O sea, son muy cautelosos. Una vez tomen la decisión de compra, lo harán sin ninguna duda.',
        imagen: require('@/assets/curso/temas/tema3/img-58.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Prospectos amables',
        texto:
          'Cuando le interesa construir una buena relación con alguien de la marca antes de efectuar transacciones comerciales. Busca un contacto humano durante las diferentes fases del ciclo de vida del comprador. Antes que investigar sobre la oferta y la marca, preferirá tener una reunión con un representante que solucione sus inquietudes.',
        imagen: require('@/assets/curso/temas/tema3/img-59.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Prospectos asertivos',
        texto:
          'Cuando tiene menos tiempo para iniciar una conversación y su interés se centra en saber sobre las ventajas del producto. Es propenso a lo pragmático y a lograr sus metas, por lo que motivarlo para convertirlo en cliente dependerá de darle la información concisa, seductora y clara. Por lo general, toma decisiones de forma rápida.',
        imagen: require('@/assets/curso/temas/tema3/img-60.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Prospectos expresivos',
        texto:
          'Cuando tiene en cuenta la manera en que su decisión de compra impacta a las demás personas. O sea, la trascendencia que tiene su compra con gente cercana a él, como, por ejemplo, empleados, compañeros, vecinos, amigos, familiares. Aprecia mucho que las promesas de venta sean cumplidas.',
        imagen: require('@/assets/curso/temas/tema3/img-61.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Prospectos sospechosos',
        texto:
          'Cuando muestran interés en la marca de una manera poco obvia, como la visita al <em>sitio web,</em> y no se contactan para requerir un demo o una cotización <em>online.</em>',
        imagen: require('@/assets/curso/temas/tema3/img-62.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Prospectos calientes',
        texto:
          'Cuando preguntan de forma directa datos como precio, tiempo de entrega o beneficios del producto, pero no toman una decisión de compra. ',
        imagen: require('@/assets/curso/temas/tema3/img-63.png'),
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
