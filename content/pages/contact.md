---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >-
      ¡Hola! Muchas gracias por su interés en trabajar juntos. Por favor
      complete el formulario de contacto a continuación o envíenos un correo electrónico a
      [info@wladimirmoya.com](mailto:info@wladimirmoya.com).
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu dirección de correo electrónico
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: seleccione por favor
        options:
          - Error en el sitio
          - Patrocinio
          - Otro
      - input_type: textarea
        name: message
        label: Message
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario está almacenando mi información enviada para que pueda ser contactado.
    submit_label: Send Message
seo:
  title: Contacto
  description: Página de contacto
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: Página de contacto
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: Página de contacto
layout: advanced
---
