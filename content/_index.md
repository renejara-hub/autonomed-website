# Homepage
type: landing

sections:
  - block: hero
    demo: true
    content:
      title: |
        **Ecosistemas de Medios Nativos Digitales Chile**
      text: |
        AUTONOMED analiza de manera exhaustiva el panorama de medios digitales chilenos: 
        sus modelos de negocio, audiencias, impacto social y sostenibilidad en el ecosistema informativo nacional.
      
      primary_action:
        text: Explorar Investigación
        url: '/investigacion/'
        icon: rocket-launch
      
      secondary_action:
        text: Ver Directorio de Medios
        url: '/medios/'
        icon: sparkles
      
      announcement:
        text: "Proyecto en desarrollo - Primera fase: Mapeo del ecosistema"
        link:
          text: "Conoce más"
          url: "/proyecto/"
    design:
      background:
        gradient_angle: 0
        gradient_start: '#4f46e5'
        gradient_end: '#7c3aed'
        text_color_light: true

  - block: stats
    content:
      items:
        - statistic: "50+"
          description: |
            **Medios digitales**  
            analizados en Chile
        - statistic: "2019-2025"
          description: |
            **Período de investigación**  
            Post-estallido social
        - statistic: "15"
          description: |
            **Regiones**  
            del país cubiertas
        - statistic: "100%"
          description: |
            **Datos abiertos**  
            para la comunidad
    design:
      background:
        color: 'white'

  - block: features
    content:
      title: Investigación Integral
      subtitle: Análisis multidimensional del ecosistema de medios nativos digitales
      text: |
        Nuestro enfoque combina metodologías cuantitativas y cualitativas para comprender 
        la evolución, sostenibilidad e impacto de los medios nativos digitales en Chile.
      items:
        - name: Mapeo Territorial
          description: Identificación geográfica y análisis regional de medios digitales en todas las regiones de Chile
          icon: map
          icon_pack: fas
        - name: Modelos de Negocio
          description: Análisis de estructuras de financiamiento, sostenibilidad económica y estrategias de monetización
          icon: chart-line
          icon_pack: fas
        - name: Impacto Social
          description: Evaluación del rol en movimientos sociales, participación ciudadana y agenda pública
          icon: users
          icon_pack: fas

  - block: contact
    content:
      title: Colabora con AUTONOMED
      subtitle: Únete a nuestra red de investigación
      text: |
        Si diriges un medio digital, eres investigador en comunicaciones o trabajas en políticas públicas, 
        nos interesa conocer tu perspectiva y establecer colaboraciones.
      email: contacto@autonomed.cl
      coordinates:
        latitude: '-33.4489'
        longitude: '-70.6693'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Síguenos en Twitter
          link: 'https://twitter.com/autonomed_cl'
        - icon: github
          icon_pack: fab
          name: Código abierto en GitHub
          link: 'https://github.com/renejara-hub/autonomed-website'
      autolink: true
      form:
        provider: netlify
        netlify:
          captcha: false
