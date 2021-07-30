<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 Satisfacción del usuario
    p.mb-5 La satisfacción del usuario con los servicios médicos recibidos depende de muchos factores; se presenta una relación directa entre la atención brindada, el valor y las expectativas del usuario; esto determina el uso, la conexión y el resultado del servicio. Todo esto se relaciona con varios aspectos del servicio o atención de primera línea, en la que se incluyen todas las interacciones personales, desde el personal de vigilancia hasta el gerente y los especialistas más mencionados. 
    figure.px-3
      img(src='@/assets/tema1/img-1-.svg')

    separador
    #t_1_1.titulo-segundo
      h2 1.1	Métodos proactivos

    p Son los procedimientos que posibilitan identificar las necesidades y el grado de satisfacción del usuario/cliente con la atención que le ha sido brindada; se lleva a cabo a través de herramientas como entrevista postventa, buzón de sugerencias y encuesta de satisfacción, los cuales se podrán conocer a continuación:
    .contenedor.contenedor__bbg1
      .mb-5
    .row
      PasosA.color-acento-contenido.mb-5(tipo="n")
        .row.justify-content-around
          .col-md-6.mb-4.mb-md-0.align-self-center
            h3 Entrevista postventa
            p El sistema de información y atención al usuario puesto en marcha por las instituciones de salud.

          .col-md-6
            figure
              img.img-300(src='@/assets/tema1/img-2-.svg')
              

        .row.justify-content-around
          .col-md-6.mb-4.mb-md-0
            figure
              img.img-300(src='@/assets/tema1/img-3.svg')
          .col-md-6.align-self-center
            h3 Buzón de sugerencias
            p Herramienta utilizada para conocer las necesidades, quejas y sugerencias que pueden tener los usuarios, expresadas de manera libre, privada y autónoma. 

            

        .row.justify-content-around
          .col-md-6.mb-4.mb-md-0
            h3 Encuesta de satisfacción
            p Datos estadísticos que utilizan las instituciones al encuestar clientes internos y externos para obtener los distintos niveles de satisfacción en los servicios, infraestructura, atención prestada y trato de los empleados hacia el usuario.

        
          .col-md-6
            figure
              img.img-300(src='@/assets/tema1/img-4.svg')

    separador
    #t_1_2.titulo-segundo
      h2 1.2 Métodos reactivos 
    p.mb-5 Estos métodos se establecen de manera dinámica por medio de un mecanismo legal que los usuarios pueden utilizar para presentar quejas y reclamos, cuyo objetivo es brindar una respuesta rápida y satisfactoria a sus quejas, procesando la información del usuario. Es común que todas las organizaciones públicas o privadas denuncien o resuelvan una situación de manera oportuna y efectiva. A continuación, se podrá conocer las definiciones de estos métodos: 

    .row.justify-content-around.align-items-center
      .col-lg-6
        ImagenInfografica.mb-5

          template(v-slot:imagen)
            figure
              img(src='@/assets/tema1/img-5-.svg')
              

          .tarjeta.tt-n.p-3(x="17%" y="41%")
            .h5.mb-2 Peticiones de información 
            p Se solicita acceso a la información ante las autoridades, para el conocimiento de una actuación en un acto concreto y determinado.  
          .tarjeta.tt-n.p-3(x="50%" y="13%")
            .h5.mb-2 Quejas
            p Se ponen en conocimiento de las autoridades las conductas irregulares de empleados oficiales o particulares, a quienes se ha adjudicado la prestación de un servicio público.
          
          .tarjeta.tt-n.p-3(x="82%" y="41%")
            .h5.mb-2 Reclamos 
            p Manifestación de inconformidad con la prestación de un servicio o con la atención prestada por parte de un funcionario.      

          .tarjeta.tt-n.p-3(x="72%" y="80%")
            .h5.mb-2 Sugerencias
            p Es la proposición o indicación que se ofrece, con el propósito de influir en el mejoramiento de un proceso, relacionado con la prestación de un servicio.

          .tarjeta.tt-n.p-3(x="27%" y="80%")
            .h5.mb-2 Felicitaciones
            p Agradecimiento por la atención brindada, luego de recibir un trato digno y resolver una situación de salud.
    separador
    #t_1_3.titulo-segundo
      h2 1.3	Mecanismos establecidos por la Constitución para garantizar el cumplimiento de los derechos fundamentales en salud
    .row
      figure
        img(src='@/assets/tema1/img-6.svg')
    #base.row.justify-content-around.align-items-center
      .row.col-11
        .row.mt-5
          .col-md-6.col-lg-4
            .anchorBtn
              a(href="#1")
                .anchorBtn__tag
                  .anchorBtn__number
                    h3 1
                .anchorBtn__body
                  p Derecho de petición 
          .col-md-6.col-lg-4
            .anchorBtn
              a(href="#2")
                .anchorBtn__tag
                  .anchorBtn__number
                    h3 2
                .anchorBtn__body
                  p Entidades que asesoran para presentar peticiones
          .col-md-6.col-lg-4
            .anchorBtn
              a(href="#3")
                .anchorBtn__tag
                  .anchorBtn__number
                    h3 3
                .anchorBtn__body
                  p ¿Qué incluye un derecho de petición?
       
          .col-md-6.col-lg-4
            .anchorBtn
              a(href="#4")
                .anchorBtn__tag
                  .anchorBtn__number
                    h3 4
                .anchorBtn__body
                  p Acción de tutela 
          .col-md-6.col-lg-4
            .anchorBtn
              a(href="#5")
                .anchorBtn__tag
                  .anchorBtn__number
                    h3 5
                .anchorBtn__body
                  p Características de una acción de tutela:
          .col-md-6.col-lg-4
            .anchorBtn
              a(href="#6")
                .anchorBtn__tag
                  .anchorBtn__number
                    h3 6
                .anchorBtn__body
                  p Características, requisitos y quien la presenta
                    
        .row.justify-content-around.align-items-center
          .col-md-6.col-lg-4
            .anchorBtn
              a(href="#7")
                .anchorBtn__tag
                  .anchorBtn__number
                    h3 7
                .anchorBtn__body
                  p ¿Quién puede presentar una acción de tutela? 
          .col-md-6.col-lg-4
            .anchorBtn
              a(href="#8")
                .anchorBtn__tag
                  .anchorBtn__number
                    h3 8
                .anchorBtn__body
                  p Autoridades Judiciales ante las cuales se puede presentar la acción de tutela

                    


    #1.row.fond-1.p-5.mb-5
      .anchorHeader
        .anchorHeader__number
          h3 1
        .anchorHeader__body
          p Derecho de petición
          .anchorHeader__btn
            a(href="#base")
              .fas.fa-chevron-up
      .row
        .col-md-5.mb-5
          figure
            img(src='@/assets/tema1/img-7.svg')
               
        .col-md-7.mb-4.mb-md-0
         
          p La Constitución Política de Colombia en su Artículo 23 ha concedido a toda persona natural o jurídica, ciudadanos colombianos o extranjeros, la facultad que tiene toda persona para presentar peticiones respetuosas ante las autoridades o entidades públicas o privadas. ya sea por motivos de interés general o particular. 
          p Un derecho de petición sirve para: 
          .ul.lista-ul--color
            li 
              i.ii.fas.fa-atom
              p Solicitar información, documentos o copias de documentos. 
            li 
              i.ii.fas.fa-atom
              p Pedir que se preste un servicio. 
            li 
              i.ii.fas.fa-atom
              p Reclamar sobre un servicio recibido.
            li 
              i.ii.fas.fa-atom
              p Quejarse sobre el servidor o funcionario que lo atendió. 
            li 
              i.ii.fas.fa-atom
              p Sugerir mejor calidad en el servicio. 



    #2.row.fond-1.p-5.mb-5
      .anchorHeader
        .anchorHeader__number
          h3 2
        .anchorHeader__body
          p Entidades que asesoran para presentar peticiones
          .anchorHeader__btn
            a(href="#base")
              .fas.fa-chevron-up
      
      .row
        .col-md-5
          figure.mb-3
            img(src='@/assets/tema1/img-8.svg')
               
        .col-md-7.mb-4.mb-md-0
          
          p Existen entidades públicas y privadas que asesoran la presentación de peticiones: 
          .ul.lista-ul--color
            li 
              i.ii.fas.fa-atom
              p Defensoría del Pueblo. 
            li 
              i.ii.fas.fa-atom
              p Procuraduría General de la Nación. 
            li 
              i.ii.fas.fa-atom
              p Personerías distritales y municipales. 
            li 
              i.ii.fas.fa-atom
              p Consultorios jurídicos de las universidades.

    
      p Si el derecho de petición no es respondido dentro de estos plazos, el funcionario público incurre en causal de mala conducta, y permite al peticionario recurrir a la acción de tutela para exigir el amparo de sus derechos.

      p Todas las entidades están obligadas a recibir, informar o responder su petición en los siguientes plazos: 
      .row
        .col-3
          figure
            img(src='@/assets/tema1/img-9-1.svg')
        .col-3
          figure
            img(src='@/assets/tema1/img-9-2.svg')
        .col-3
          figure
            img(src='@/assets/tema1/img-9-3.svg')
        .col-3
          figure
            img(src='@/assets/tema1/img-9-4.svg')                                    
               
    #3.row.fond-1.p-5.mb-5
      .anchorHeader
        .anchorHeader__number
          h3 3
        .anchorHeader__body
          p ¿Qué incluye un derecho de petición?
          .anchorHeader__btn
            a(href="#base")
              .fas.fa-chevron-up
      
      .row
        .col-md-5.mb-3
          figure
            img(src='@/assets/tema1/img-10.svg')
               
        .col-md-7.mb-4.mb-md-0
          
          ol.lista-ol--cuadro
            li 
              .lista-ol--cuadro__vineta.fms
                span a
              | La entidad o persona a quien va dirigida la petición.
            li 
              .lista-ol--cuadro__vineta.fms
                span b
              | El nombre completo de la persona que presenta la petición. 
            li 
              .lista-ol--cuadro__vineta.fms
                span c
              | El número de cédula, tarjeta de identidad o pasaporte de quien presenta la petición.
            li 
              .lista-ol--cuadro__vineta.fms
                span d
              | La explicación clara de lo que pide, solicita o necesita (queja clara y concreta).
            li 
              .lista-ol--cuadro__vineta.fms
                span e
              | Los motivos o razones por los cuales realiza la petición. 
            li 
              .lista-ol--cuadro__vineta.fms
                span f
              | Firma del peticionario.
            li 
              .lista-ol--cuadro__vineta.fms
                span g
              | Una dirección física o un correo electrónico en donde se desea recibir la respuesta.
            li 
              .lista-ol--cuadro__vineta.fms
                span h
              | Pruebas o documentos que soporten la petición (anexos).
    #4.row.fond-1.p-5.mb-5
      .anchorHeader
        .anchorHeader__number
          h3 4
        .anchorHeader__body
          p Acción de tutela
          .anchorHeader__btn
            a(href="#base")
              .fas.fa-chevron-up
      
      .row
        .col-md-5
          figure.mb-5
            img(src='@/assets/tema1/img-11.svg')
               
        .col-md-7.mb-4.mb-md-0
          
          p Procede para exigir el cumplimiento o respuesta de un derecho de petición cuando, como consecuencia de su no atención, se viola un derecho fundamental del peticionario. Por regla general, la tutela no se puede interponer para conseguir que se le dé respuesta a un derecho de petición, pero si el hecho de no atender un derecho de petición vulnera o afecta un derecho constitucional considerado fundamental, la tutela procede de forma excepcional.

          .cajon.color-primario.fond3.p-4.mb-4
            p La acción de tutela protege derechos como: la vida, salud, seguridad social, dignidad humana, igualdad, no discriminación, consulta previa, trabajo, ambiente sano, seguridad social, libre desarrollo de la personalidad, libertad de conciencia, culto, expresión, circulación, educación, asociación, manifestarse pública y pacíficamente, derechos de los niños, familia, debido proceso, entre otros.
            p.mb-0
              b Artículo 86 de la Constitución Política de 1991 
            p
              b Artículo 10 del Decreto 2591 de 1991
    #5.row.fond-1.p-5.mb-5
      .anchorHeader
        .anchorHeader__number
          h3 5
        .anchorHeader__body
          p Características de una acción de tutela:
          .anchorHeader__btn
            a(href="#base")
              .fas.fa-chevron-up
      
      .row
        .col-md-5
          figure.mb-5
            img(src='@/assets/tema1/img-12.svg')
               
        .col-md-7.mb-4.mb-md-0
          
          .ul.lista-ul--color
            li 
              i.ii.fas.fa-atom
              p La #[strong informalidad] no requiere de abogado y la exigencia probatoria es mínima.
            li 
              i.ii.fas.fa-atom
              p La #[strong subsidiariedad] debido a que procede cuando no se dispone de otro medio de defensa judicial.
            li 
              i.ii.fas.fa-atom
              p La #[strong celeridad], ya que su propósito es el de garantizar, sin demora, la protección solicitada. 
    #6.row.fond-1.p-5.mb-5
      .anchorHeader
        .anchorHeader__number
          h3 6
        .anchorHeader__body
          p Características, requisitos y quien la presenta
          .anchorHeader__btn
            a(href="#base")
              .fas.fa-chevron-up
      
      .row
        .col-md-5
          figure.mb-5
            img(src='@/assets/tema1/img-13.svg')
               
        .col-md-7.mb-4.mb-md-0
          h3 Requisitos mínimos de una acción de tutela
          .ul.lista-ul--color
            li 
              i.ii.fas.fa-atom
              p El acto o la omisión que motivó la acción de tutela con la mayor claridad posible.
            li 
              i.ii.fas.fa-atom
              p El derecho a ser infringido o amenazado.
            li 
              i.ii.fas.fa-atom
              p El nombre de la autoridad pública o el nombre de la persona que infringió o amenazó el derecho subyacente, si corresponde; otras circunstancias relacionadas en la solicitud.
            li 
              i.ii.fas.fa-atom
              p El nombre del solicitante, el lugar de residencia, la dirección, etc.
            li 
              i.ii.fas.fa-atom
              p Juramento que indica que no se ha presentado otra acción de tutela por los mismos hechos.
    #7.row.fond-1.p-5.mb-5
      .anchorHeader
        .anchorHeader__number
          h3 7
        .anchorHeader__body
          p ¿Quién puede presentar una acción de tutela?
          .anchorHeader__btn
            a(href="#base")
              .fas.fa-chevron-up
      
      .row
        .col-md-5
          figure.mb-5
            img(src='@/assets/tema1/img-14.svg')
               
        .col-md-7.mb-4.mb-md-0
          h3 ¿Quién puede presentar una acción de tutela?
          .ul.lista-ul--color
            li 
              i.ii.fas.fa-atom
              p Cualquier persona a nombre propio.
            li 
              i.ii.fas.fa-atom
              p A través de representante legal, por ejemplo, el padre o la madre respecto a sus hijos.
            li 
              i.ii.fas.fa-atom
              p Por medio de abogado, y se hace necesario anexar el documento mediante el cual se transfiere a este, la facultad de actuar en su nombre. 
            li 
              i.ii.fas.fa-atom
              p A través de agente oficioso, o sea, una persona cercana a aquella que sufre la vulneración, cuando esta última no se encuentre en condiciones físicas, mentales o cualquier circunstancia que le impida promover su propia defensa.
            li 
              i.ii.fas.fa-atom
              p El Defensor del Pueblo, los Personeros Distritales o Municipales y la Procuraduría General de la Nación pueden presentar acciones de tutela para la defensa de los derechos fundamentales de las personas que lo requieran.
    #8.row.fond-1.p-5.mb-5
      .anchorHeader
        .anchorHeader__number
          h3 8
        .anchorHeader__body
          p Autoridades Judiciales ante las cuales se puede presentar la acción de tutela
          .anchorHeader__btn
            a(href="#base")
              .fas.fa-chevron-up
      
      .row.mb-5
        .col-md-6.d-flex
          .crd_01.mb-sm-5
            .crd_01__icon
              img(src="@/assets/tema1/img-15.svg", alt="alt").class          
            .crd_01__txt
              p Ante los jueces municipales se presenta la acción de tutela contra cualquier autoridad de orden departamental, distrital o municipal.
               
        .col-md-6.d-flex

          .crd_01.mb-sm-5
            .crd_01__icon
              img(src="@/assets/tema1/img-15.svg", alt="alt").class          
            .crd_01__txt
              p Ante los jueces del circuito se interpone la acción de tutela contra cualquier autoridad del orden nacional.


      .crd_01.mb-5
            .crd_01__icon
              img(src="@/assets/tema1/img-15.svg", alt="alt").class          
            .crd_01__txt
              p Ante los Tribunales Superiores de Distrito Judicial o los Tribunales Administrativos se instauran las acciones de tutela contra las actuaciones del Presidente de la República, Contralor General de la República, Procurador General de la Nación, Fiscal General de la Nación, Registrador Nacional del Estado Civil, Defensor del Pueblo, Auditor General de la República, Contador General de la Nación y Consejo Nacional Electoral.

      .row.mb-5
        .col-md-6.d-flex
          .crd_01.mb-sm-5
            .crd_01__icon
              img(src="@/assets/tema1/img-15.svg", alt="alt").class          
            .crd_01__txt
              p Ante la Corte Suprema de Justicia o el Consejo de Estado se promueven las acciones contra el Consejo Superior de la Judicatura y la Comisión Nacional de Disciplina Judicial.
               
        .col-md-6.d-flex

          .crd_01.mb-sm-5
            .crd_01__icon
              img(src="@/assets/tema1/img-15.svg", alt="alt").class          
            .crd_01__txt
              p Ante el Superior Funcional de la autoridad judicial donde intervienen se presenta la acción de tutela contra los Fiscales o los Procuradores.


      .row.mb-5
        .col-md-6.d-flex
          .crd_01.mb-sm-5
            .crd_01__icon
              img(src="@/assets/tema1/img-15.svg", alt="alt").class          
            .crd_01__txt
              p Ante los Tribunales Superiores de Distrito Judicial o Sala Disciplinaria del Consejo Seccional de la Judicatura se interpone la acción de tutela contra Fiscales que intervienen ante Tribunales o Altas Cortes.
               
        .col-md-6.d-flex

          .crd_01.mb-sm-5
            .crd_01__icon
              img(src="@/assets/tema1/img-15.svg", alt="alt").class          
            .crd_01__txt
              p Ante los Tribunales Administrativos o la Sala Disciplinaria del Consejo Seccional de la Judicatura se promueve la acción de tutela contra Procuradores que intervienen ante Tribunales o Altas Cortes.
      .row.mb-5
        .col-md-6.d-flex
          .crd_01.mb-sm-5
            .crd_01__icon
              img(src="@/assets/tema1/img-15.svg", alt="alt").class          
            .crd_01__txt
              p Ante el superior funcional de la autoridad accionada se presenta la acción de tutela contra los Jueces o Tribunales.
               
        .col-md-6.d-flex

          .crd_01.mb-sm-5
            .crd_01__icon
              img(src="@/assets/tema1/img-15.svg", alt="alt").class          
            .crd_01__txt
              p Ante los Tribunales Superiores de Distrito Judicial se presenta la acción de tutela contra los Consejos Seccionales de la Judicatura y las Comisiones Seccionales de Disciplina Judicial. Asimismo, conocerán de las acciones de tutela contra las autoridades administrativas que ejerzan funciones jurisdiccionales.

      .row.mb-5
        .col-md-6.d-flex
          .crd_01.mb-sm-5
            .crd_01__icon
              img(src="@/assets/tema1/img-15.svg", alt="alt").class          
            .crd_01__txt
              p Ante la Corte Suprema de Justicia o el Consejo de Estado se interpone la acción de tutela contra estas entidades respectivamente. Su reparto será ante la misma Corporación y se resolverá por la Sala de Casación, Sección o Subsección que corresponda.
               
        .col-md-6.d-flex
          .crd_01.mb-sm-5
            .crd_01__icon
              img(src="@/assets/tema1/img-15.svg", alt="alt").class          
            .crd_01__txt
              p Ante la autoridad judicial que conozca del recurso extraordinario de anulación se promueve la acción de tutela contra los Tribunales de Arbitramento.









</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
  data: () => ({
    // variables de vue
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

<style lang="sass" scoped></style>
